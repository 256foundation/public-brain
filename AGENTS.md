# AGENTS.md — 256 Foundation Public Brain

This repo is an **LLM wiki** (see README.md). If you are an agent working here, read and follow the workflow defined in:

**`.agents/skills/karpathy-llm-wiki/SKILL.md`** — the authoritative spec. Templates are in `.agents/skills/karpathy-llm-wiki/references/`, and the evidence checker is `.agents/skills/karpathy-llm-wiki/scripts/check_evidence.py`.

## Non-negotiable rules

1. **`raw/` is immutable.** Read it, never modify existing files. New sources get new files: `raw/<topic>/YYYY-MM-DD-slug.md` with a metadata header (see `references/raw-template.md`).
2. **`wiki/` follows the article template** exactly (metadata block: Sources / Raw / Updated). One level of topic subdirectories only.
3. **Grounding invariant:** every number, date, and quote in `wiki/` must exist verbatim in the linked `raw/` files. Locate before you write; write exactly what the source says.
4. **Never silently rewrite history.** Outdated or contradicted claims stay, marked with a `Status: Outdated` / `Status: Disputed` block.
5. **`wiki/index.md` and `wiki/log.md` are updated on every ingest** (log-only for "No material" dispositions). `log.md` is append-only.
6. **Queries never write files** unless the user explicitly asks to archive the answer.
7. Use relative markdown links everywhere; paths inside wiki files are relative to the current file.

## Concurrent work (multiple operators)

Several people ingest at once. Follow this loop exactly — it is what keeps the repo from losing or dueling over content:

1. **Pull before every session:** `git pull --rebase` *before* starting an ingest (start from everyone's latest state), and **push immediately after** each completed ingest batch. Long-lived local state is how content gets lost.
2. **`wiki/log.md` and `wiki/index.md` are union-merged** via `.gitattributes` — concurrent appends auto-merge, nobody's entries get dropped. Never reorder, edit, or compact old log entries; append only.
3. **Never force-push, never rewrite history on `main`.** If a push is rejected: `git pull --rebase`, re-run your agent's *Post-Ingest* step if a file moved, push again.
4. **Raw collision race:** if you and a teammate ingest the same source simultaneously and git reports a raw-file conflict, keep both — rename yours with a `-2` suffix (per the fetch rules) and let lint flag the duplicate for a human.
5. **After any merge/rebase that touched `wiki/`: run a full lint** (safe fixes + `check_evidence.py`). Lint rebuilds missing `index.md` entries, repairs moved links, and reports anything a human must judge. CI also runs the evidence check on every push/PR and fails on evidence errors.
6. **One ingest at a time per working tree.** Index, log, and cascade updates are shared state; never run two agent ingests concurrently in the same clone. Different clones/POCs are fine — git + union merge reconcile them.
7. Small, frequent pushes beat one giant end-of-day dump.

## Lint

Safe fixes (index consistency, dead links, raw references, See Also) may be auto-fixed. Then run:

```
python3 .agents/skills/karpathy-llm-wiki/scripts/check_evidence.py <repo-root>
```

and report fidelity suspects, evidence errors, and unreferenced raw files — never auto-fix facts.

## 256 Foundation context

The brain covers the 256 Foundation's mission and work — open-source Bitcoin mining and freedom tech. Likely topics (create directories as needed at ingest time, don't pre-create):

- `mujina` — open-source mining firmware
- `hardware` — emberOne hashboards, libreboard control boards
- `hydrapool` — open-source mining pool
- `protocols` — RHAP, stratum, ASIC interfaces
- `foundation` — grants, governance, mission, operations
- `ecosystem` — bitaxe and allied open-mining projects
