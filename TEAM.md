# TEAM.md — Feeding the 256 Brain (5-minute quickstart)

Copy-paste everything below the line into your hackathon group chat, then follow it yourself.

---

## One-time setup (2 minutes)

```bash
git clone https://github.com/256foundation/public-brain.git
cd public-brain
npx add-skill Astro-Han/karpathy-llm-wiki   # teaches your agent the workflow
```

Accept the GitHub collaborator invite first (check email / github.com/notifications) or pushes will fail.

## The loop — repeat for every source

**1. Sync first, always:**

```bash
git pull --rebase
```

**2. Give your agent the source.** Open your agent (Claude Code / Cursor / Codex / OpenCode) in the `public-brain` folder and paste one of these:

> **Web page / PDF / file:**
> `Ingest this source: https://example.com/some-article`

> **Pasted text (interview notes, docs, chat logs):**
> `Ingest this as a source. Context: <what it is>. Text: """<paste>"""`

> **Whole topic at once (agent searches + ingests multiple sources itself):**
> `Research <topic> and ingest the best sources into the wiki`

**3. Let it finish.** The agent saves the raw source, decides if it's new/updated/disputed knowledge, writes or updates wiki articles, and logs it. If it says "No material," the source added nothing new — that's fine, it's logged and you move on.

**4. Push immediately:**

```bash
git push
```

If push is rejected: `git pull --rebase`, then push again. That pull is what keeps us from duplicating each other's articles — never skip it.

## Rules that keep us sane

- **Small batches.** Ingest a few sources, push, repeat. No end-of-day mega-dumps.
- **One agent, one clone.** Never run two ingest sessions on the same checkout.
- **Don't hand-edit `wiki/` or `raw/`.** The agent owns those folders. Fixes go through a prompt: *"Lint the wiki and fix what's safe."*
- **Conflicts in raw/?** Keep both versions (add `-2` to your filename) and let the librarian sort it.
- **Check `wiki/log.md`** to see what teammates already ingested before researching the same topic.
- **Never force-push.** `main` won't let you anyway.

## Asking the brain questions (read-only, safe anytime)

> `What do we know about <topic>?`
> `Compare <A> and <B> based on the wiki`

Queries never modify files — no pull/push needed.
