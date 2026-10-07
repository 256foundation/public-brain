# 256 Foundation Public Brain

The public knowledge base ("brain") of the [256 Foundation](https://256foundation.org) — a 501(c)(3) public charity on a mission to dismantle the proprietary mining empire and make Bitcoin and freedom tech accessible to anyone.

This repo is an **LLM wiki**: a knowledge system where an LLM maintains structured, curated markdown pages instead of re-searching raw documents on every question. It follows the [karpathy-llm-wiki](https://github.com/Astro-Han/karpathy-llm-wiki) structure (from [Karpathy's LLM Wiki idea](https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f)).

## Structure

```
public-brain/
├── raw/            ← Immutable source material (web pages, docs, papers), organized by topic
│   ├── <topic>/YYYY-MM-DD-source-slug.md
│   └── pod256/transcripts/<collected-date>/ ← Immutable transcript snapshots
├── scripts/        ← Reusable source downloaders
├── wiki/           ← Compiled knowledge articles, maintained by the LLM
│   ├── <topic>/<article>.md
│   ├── index.md    ← Global table of contents
│   └── log.md      ← Append-only operation log
├── brand/          ← Official 256 Foundation logo kit (PNG + EPS) — see brand/README.md
└── .agents/skills/karpathy-llm-wiki/   ← The skill that defines the workflow
```

| Operation | What it does |
| --- | --- |
| **Ingest** | Saves a source into `raw/`, triages it, compiles durable knowledge into `wiki/` |
| **Query** | Searches the wiki and answers with citations — never writes files |
| **Lint** | Checks index integrity, links, and source fidelity; auto-fixes what's safe |

## Source collections

- [POD256 transcript archive](raw/pod256/transcripts/2026-10-07/README.md): 49 published transcripts from the October 7, 2024–October 7, 2026 window, with original HTML, SRT, and VTT files, episode metadata, and checksums. The index covers all 70 feed episodes in the window and identifies the 21 without published transcripts. This collection complements the episode descriptions in [raw/pod256](raw/pod256).

### Collecting POD256 snapshots

Run from the repository root with Python 3.9+ and curl:

```sh
python3 scripts/download_pod256.py
```

This selects the past two years ending today and saves a dated snapshot under `raw/pod256/transcripts/`. Existing raw snapshots are immutable; use a new `--output` directory for another collection on the same day. See the [archive README](raw/pod256/transcripts/2026-10-07/README.md) for refresh and reproduction options. Original source URLs and SHA-256 checksums are recorded in the manifest. Machine transcripts retain the publisher's wording; names, technical terms, quotations, and speaker identities need verification against the audio when accuracy matters.

## Using the brain

Work in this repo with any agent tool that supports [Agent Skills](https://agentskills.io). The skill is vendored at `.agents/skills/karpathy-llm-wiki/` (MIT, © Astro-Han) and is picked up automatically by compatible tools (Codex CLI, and others following the standard).

- **Claude Code**: `npx add-skill Astro-Han/karpathy-llm-wiki` (or symlink `.agents/skills/karpathy-llm-wiki` into `.claude/skills/`)
- **Cursor / OpenCode**: `npx add-skill Astro-Han/karpathy-llm-wiki` from the repo root
- **Any other tool**: read `.agents/skills/karpathy-llm-wiki/SKILL.md` — it's the full spec

Then just ask:

- *"Ingest this article: `<url>`"*
- *"What do we know about mining firmware?"* → wiki-grounded answer with citations
- *"Lint the wiki"*

The full workflow rules (triage, source fidelity, cascade updates, log format) are defined in [`.agents/skills/karpathy-llm-wiki/SKILL.md`](.agents/skills/karpathy-llm-wiki/SKILL.md). See also [AGENTS.md](AGENTS.md) for contributor guidance.

## Feeding the brain

**Teammates start here: [TEAM.md](TEAM.md)** — setup + copy-paste prompts for ingesting sources.

## Working concurrently

Multiple people feed this brain at once, so it is hardened against collision:

- `wiki/log.md` and `wiki/index.md` use **union merge** (`.gitattributes`) — concurrent appends from teammates auto-merge instead of conflicting.
- **Always `git pull --rebase` before you start an ingest, and push right after.** The full protocol is in [AGENTS.md](AGENTS.md#concurrent-work-multiple-operators).
- CI runs the **evidence check** on every push/PR and fails if an article's link to its source breaks, so unverifiable knowledge can't land on `main`.

## Why an LLM wiki instead of RAG?

Knowledge lives in curated markdown pages, synthesized at ingest time — so it compounds: cross-links strengthen, contradictions get annotated, and answers cite durable pages instead of raw chunks. The brain gets smarter every time someone feeds it.

## License

Content: [CC0](https://creativecommons.org/public-domain/cc0/) (public domain) unless noted otherwise. Vendored skill: MIT (see `.agents/skills/karpathy-llm-wiki/LICENSE`).

POD256 publisher files and transcript text in `raw/pod256/transcripts/2026-10-07/` retain their source copyright and licensing; this repository does not assign a new license to that material.
