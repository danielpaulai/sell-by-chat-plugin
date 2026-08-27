# Sell By Chat · The Conversation Engine plugin (v2)

The AI Founder Circle daily chat engine for Claude Code. Ten skills, one method: stop selling, start serving. Works on LinkedIn, Instagram, Facebook and TikTok.

## Install (founders)

In Claude Code:

```
/plugin marketplace add danielpaulai/sell-by-chat-plugin
/plugin install sell-by-chat@ai-founder-circle
```

Then run `/setup` once. Drop your existing `VOICE-DNA.md` and ICP file into the folder, pick your platform, and setup creates your scoreboard (a CSV that opens straight in Excel), your pipeline file, and optionally wires both into Notion if your Notion connector is on.

## Daily flow

```
morning:  /morning        → replies to answer, follow-ups due, fresh openers. 15 min.
          /chrome-chats   → same thing, but the Chrome extension collects the raised
                            hands from your real browser and types each DM in.
                            You press send on every message. Always.
anytime:  /score-my-dm    → paste a draft, get SEND / FIX FIRST / REWRITE in 2 seconds
          /chat-coach     → paste a live conversation, get the one next right message
weekly:   /hand-raiser    → one ask post that feeds tomorrow's chats
evening:  /scoreboard     → log sent, replies, calls. Friday: automatic week diagnosis
```

## All skills

| Skill | What it does |
|---|---|
| `/setup` | One-time wiring: your files, platform, give, ask, scoreboard, pipeline, Notion. |
| `/morning` | The full 15-minute routine in one command. |
| `/daily-chats` | Paste raised hands, get 25 personal openers, zero pitch. |
| `/chrome-chats` | Claude in Chrome works your real inbox: collects, drafts, types. You send. |
| `/chat-coach` | The ladder: easy question, deeper, commit, give, two-times ask. |
| `/follow-up-sweep` | Day 1 / 3 / 7 follow-ups drafted, value-first, zero guilt. |
| `/hand-raiser` | Writes the weekly ask post, platform-native. |
| `/score-my-dm` | The two-second gate before anything gets sent. |
| `/scoreboard` | CSV + Notion + Excel logging, streaks, and the Friday diagnosis. |
| `/pipeline` | New → Awaiting → In conversation → Booked, one markdown file, Notion mirror. |

## Data: yours, portable

- `chat-scoreboard.csv`: opens in Excel and Numbers directly.
- `chat-pipeline.md`: readable anywhere, synced to Notion when connected.
- `SELL-BY-CHAT.md`: your config. Delete it and rerun `/setup` to start clean.

## Automation policy (important)

`/chrome-chats` never sends messages by itself and never runs unattended. It collects, filters against your ICP, drafts in your voice, and types the message in. The founder presses send on every single message. Platforms ban automation; they do not ban people having conversations.

## Updating (Danny)

Push to this repo, bump `version` in `plugins/sell-by-chat/.claude-plugin/plugin.json`. Founders get it via `/plugin marketplace update ai-founder-circle`.

## The method inside

Serve first. Openers about them, one easy question, zero pitch. Three questions: easy, deeper, commit. Find the A to B gap in their words. Give before you ask. Ask small with two concrete times. Follow up day 1, 3, 7. 25 starts a day, about 30 minutes. Roughly 3 in 10 reply, roughly 1 client per 100 conversations. The only number you control is how many you start.
