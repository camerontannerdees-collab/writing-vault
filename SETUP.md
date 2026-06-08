# Setup — start here

You're looking at a freshly scaffolded vault. A few things to do before it's fully live.

## 1. Drop these files into your Obsidian vault

Unzip the archive into your vault. The folders will merge with whatever you already have — there's almost nothing in your vault yet, so this should be clean.

If your vault is, for example, at `~/Documents/MyVault/`, the files should end up like:

```
~/Documents/MyVault/
  CLAUDE.md
  AGENTS.md
  README.md
  SETUP.md          ← this file
  Home.md
  .gitignore
  context/
    writing-guide.md
    source-index.md
  docs/
    index.md
  source-material/
    README.md
  scripts/
    README.md
```

You can delete `SETUP.md` once you've done everything in it.

## 2. Tell `CLAUDE.md` where it lives (optional)

`CLAUDE.md` is the agent brief. It doesn't need to know its own path, but if you want, you can add a one-liner at the top noting which machine and vault path it lives at. The agent will see it.

## 3. Install Claude Code

If you haven't already:

- Quickstart: https://docs.claude.com/en/docs/claude-code/quickstart
- Once installed, `cd` into the vault and run `claude` to open a session against the folder.

The first session will read `CLAUDE.md`, then `context/writing-guide.md`. You don't have to tell it to — that's the default.

## 4. Read and tweak `context/writing-guide.md`

This is the single highest-leverage file in the vault. Mine is a starter version — it codifies what you told me during setup (no em dashes, no emojis, analytical-and-measured voice, full AI-buzzword ban, flexible openings).

Spend ten minutes reading through it and adjusting anything that doesn't match how you actually want to sound. Add specific words you do or don't like. Add phrases you tend to overuse. The guide gets sharper every time you use it.

## 5. First real session

When you're ready, open Claude Code in the vault and try something concrete. For example:

> "Read CLAUDE.md and the writing guide. Then write me a 200-word draft about [topic you've been meaning to write about] in my voice. Plan it first, then draft."

Review what comes back. When you correct anything, ask the agent to save the correction as a feedback file in the memory folder so it sticks across sessions.

## 6. Memory folder (the second kind of memory)

Claude Code stores per-project memory at `~/.claude/projects/<encoded-path>/memory/`. You don't have to create this yourself — Claude Code does it on first run. After your first few sessions, ask the agent to write feedback files there for any corrections that should apply across sessions. The pattern is:

- `user_*.md` — who you are, how you work
- `project_*.md` — what this folder is for
- `feedback_*.md` — corrections, one per correction
- `reference_*.md` — pointers to things outside the folder

Each file: rule at the top, "Why" line, "How to apply" line.

## What's deliberately missing

You asked me to skip these in the scaffold:

- **People roster** (`context/people.md`) — skipped. Add when recurring names start appearing.
- **Glossary** (`context/glossary.md`) — skipped. Add when recurring terms start appearing.
- **Company-specific context** — skipped. This folder is personal, not company-bound.
- **Drafts/published split by status** — skipped in favor of organizing `docs/` by topic, per your choice.

If any of these become useful later, ask the agent to scaffold them.
