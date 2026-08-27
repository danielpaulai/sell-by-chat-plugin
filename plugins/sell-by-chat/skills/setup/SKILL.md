---
name: setup
description: One-time setup for the sell-by-chat system. Registers the founder's Voice DNA and ICP files, picks their main platform, creates the scoreboard and pipeline files, and optionally connects Notion. Trigger on "setup", "set up sell by chat", "get me started", or on first use when SELL-BY-CHAT.md does not exist.
---

# Setup: two minutes, once

The founder already has their Voice DNA and ICP. Do not interview them about voice. Just wire things up.

## Flow

1. Ask where their files live (or find them): `VOICE-DNA.md` and any ICP / business-brain file, in the current folder or home folder. Confirm you can read both.
2. Ask their **main platform**: LinkedIn, Instagram, Facebook, or TikTok. One platform to start.
3. Ask their **give** (the free useful thing they send) and their **ask** (the booking line) in one line each, or pull them from their files if present.
4. Create `SELL-BY-CHAT.md` in the current folder recording: paths to voice and ICP files, platform, give, ask, daily target (default 25). Every other skill reads this file first.
5. Create `chat-scoreboard.csv` with the header `date,sent,replies,calls,note` and `chat-pipeline.md` with the four sections: `## New`, `## Awaiting reply`, `## In conversation`, `## Call booked`.
6. Ask if they use Notion. If Notion tools are available in this session, offer to create a "Chat Scoreboard" database (columns matching the CSV) and a "Chat Pipeline" database, and record their ids in SELL-BY-CHAT.md so `/scoreboard` and `/pipeline` can sync. If Notion tools are not available, tell them to connect the Notion connector in Claude settings and rerun `/setup` later. Never block on it: the CSV and markdown files are the source of truth either way.
7. Finish with: "Setup done. Tomorrow morning, run /morning."
