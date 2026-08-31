---
name: setup
description: One-time setup for the sell-by-chat system. Registers the founder's Voice DNA and ICP files, picks their main platform, creates the scoreboard and pipeline files, and optionally connects Notion. Trigger on "setup", "set up sell by chat", "get me started", or on first use when SELL-BY-CHAT.md does not exist.
---

# Setup: two minutes, once

Most founders already have their Voice DNA and ICP: just wire things up, no voice interview. Missing files are handled in step 1, never block.

## Flow

1. Ask where their files live (or find them): `VOICE-DNA.md` and any ICP / business-brain file, in the current folder or home folder. **Both files are a MUST before anything else works. But never send them away:** Follow `${CLAUDE_PLUGIN_ROOT}/references/voice-dna-quickstart.md`: pull from their Purely Personal brain if reachable, build from pasted real writing, or run the 5-question interview. Ten minutes, then continue. Do NOT move to step 2 until both VOICE-DNA.md and an ICP file exist in this folder. Fastest path: the extraction prompt in that reference, run in the Claude app where their chat history lives.
2. Ask their **main platform**: LinkedIn, Instagram, Facebook, or TikTok. One platform to start.
3. Ask their **give** (the free useful thing they send) and their **ask** (the booking line) in one line each, or pull them from their files if present.
4. Create `SELL-BY-CHAT.md` in the current folder recording: paths to voice and ICP files, platform, give, ask, daily target (default 25). Every other skill reads this file first.
5. Create `chat-scoreboard.csv` with the header `date,sent,replies,calls,note` and `chat-pipeline.md` with the four sections: `## New`, `## Awaiting reply`, `## In conversation`, `## Call booked`.
6. Ask if they use Notion. If Notion tools are available in this session, offer to create a "Chat Scoreboard" database (columns matching the CSV) and a "Chat Pipeline" database, and record their ids in SELL-BY-CHAT.md so `/scoreboard` and `/pipeline` can sync. If Notion tools are not available, tell them to connect the Notion connector in Claude settings and rerun `/setup` later. Never block on it: the CSV and markdown files are the source of truth either way.
7. **Finish with THE PATH, printed exactly like this, every time:**

```
Setup done. Here is your path:

  1. Practice one round      →  say: spar with me
  2. Send your First Five    →  /morning  (paste today's raised hands)
  3. Log tonight             →  /scoreboard
  4. Tomorrow and every day  →  /morning in the morning, /scoreboard at night
  5. Lost at any point?      →  /next tells you the one next step

Start with number 1, right now. It takes five minutes.
```

Never end setup without this card. The founder must always know the exact next command.
