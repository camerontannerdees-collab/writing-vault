# Agent Brief

This file is the first thing you read every session. Everything you do flows from what is in it.

## Who uses this folder

A founder/operator who writes a mix of public essays and internal company communications. Audiences vary by piece — public readers, investors, the team, customers. Voice is analytical and measured: careful, data-grounded, restrained.

This folder is personal. It is a thinking and writing workspace, not a company knowledge base. Do not assume it belongs to any specific company unless the user introduces one.

## What this folder exists to produce

Long-form drafts and the thinking that leads to them. The primary output is finished pieces — essays, memos, updates, reports — organized by topic in `docs/`. The secondary output is the accumulated context that makes each next piece sharper than the last: source material, notes, recurring themes.

## How to operate

**Plan-first for big work. Just do small work.**

- Big = creating new top-level documents, restructuring the folder, starting a new topic area, anything that touches multiple files. Write a plan, get approval, then execute.
- Small = edits inside an existing draft, fixing typos, tightening prose, adding a section the user explicitly asked for. Just do it and show the result.
- When in doubt, plan.

**Cite source material whenever you draw on it.** Inline, by file path. Example: "according to `source-material/2026-q1-meeting-notes.md`, the team decided to..." Every claim that came from a source file should be traceable to it. If you cannot find the source, say so rather than making something up.

**Never invent facts.** No fabricated quotes, no invented names, no guessed numbers. If the user has not given you the information, ask or flag it as missing.

## Folder layout

- `CLAUDE.md` — this file
- `AGENTS.md` — same brief, for other agents (Cursor etc.)
- `README.md` — human entry point
- `Home.md` — Obsidian dashboard
- `context/` — slow-changing context the agent should always have: writing guide, source index. Read these on every session.
- `docs/` — finished and in-progress writing, organized by topic
- `source-material/` — raw inputs: meeting notes, transcripts, articles, decks converted to markdown. Read-on-demand.
- `scripts/` — ingestion and utility scripts
- `.claude/` — Claude Code config
- `.obsidian/` — Obsidian config

## Writing voice — the short version

The long version lives in `context/writing-guide.md`. Read it before writing anything substantive. The short version:

- Analytical, measured, data-grounded. Restraint over flourish.
- No em dashes. No emojis. No exclamation points unless quoting someone.
- Banned vocabulary: leverage, utilize, game-changer, revolutionary, disruptive, at the end of the day, moving forward, it's important to note, it's worth mentioning, delve, navigate, unleash, unlock. The full AI-tell vocabulary is out.
- Openings are flexible — match the piece. Do not default to a formula.
- Short paragraphs. Concrete nouns. Numbers where numbers belong.

## On the user

The user is the founder/operator. Treat their corrections as durable: if they correct a phrasing, a fact, or a preference, that correction applies going forward, not just to the current draft. Surface durable corrections to them so they can be saved to the memory folder (`~/.claude/projects/<encoded-path>/memory/`) as feedback files.

## On what you do not know

The user has chosen to keep people, companies, and glossary terms out of the initial scaffold. You will learn them organically as the writing happens. If a name or term appears repeatedly, suggest adding it to `context/` so future sessions inherit it.
