# Writing Workspace

A personal knowledge base and writing workspace, set up following the pattern of an Obsidian vault paired with Claude Code.

## What this is

A folder of plain markdown files that serves two purposes at once:

1. **An Obsidian vault** for me to write, link, and navigate notes
2. **A Claude Code workspace** where the agent can read, write, and edit the same files

Both tools point at the same folder. No upload, no sync, no plumbing.

## How to use it

Open this folder in Obsidian to write and navigate. Open Claude Code in the terminal (`cd` into this folder, run `claude`) to work with the agent against everything in here.

## Where things live

- `Home.md` — the dashboard. Start here.
- `docs/` — finished and in-progress writing, organized by topic
- `context/` — the writing guide and other slow-changing context
- `source-material/` — raw inputs: notes, transcripts, articles
- `CLAUDE.md` — the agent's brief. Edit this to change how the agent behaves.

## When the agent gets something wrong

Correct it in the chat. If the correction is a durable preference (not specific to this one piece), tell the agent to save it as a feedback file. The agent stores those in a memory folder at `~/.claude/projects/<encoded-path>/memory/` and reads them on every session. The fix only has to happen once.

## Setup notes

This folder was scaffolded from a template. Next step: open `context/writing-guide.md` and tailor it. Twenty lines is enough to start.
