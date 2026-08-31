# How to use the Sell By Chat plugin

Twelve skills and a practice partner that run your daily chats in your own voice. Simple words, short guide. The full master guide with the method, the Chat Path, platforms and troubleshooting: https://sell-by-chat-session.vercel.app/master-guide.html

## 1. Install it (once, two minutes)

Open Claude Code in the folder where your `VOICE-DNA.md` and ICP file live (no files yet? `/setup` builds starter ones with you):

```
/plugin marketplace add danielpaulai/sell-by-chat-plugin
/plugin install sell-by-chat@ai-founder-circle
/setup
```

Fastest way: in the Build Room, press **Take It To Claude** on the Scoreboard page and paste the message it copies. That does the whole setup.

## 2. Your day, three commands

| When | Type | What happens |
|---|---|---|
| Morning, 15 min | `/morning` | Replies drafted, follow-ups drafted, openers for today's raised hands. You read, tweak, send. |
| During the day | `/chat-coach` | Paste a stuck chat, get the one next right message in LVO shape. |
| Evening, 1 min | `/scoreboard` | "Log my day: sent 25, replies 8, calls 1." Streak kept. Friday: honest diagnosis. |

## 3. All the skills

| Skill | What it does |
|---|---|
| `/next` | Lost? It tells you the one next step and the exact command. |
| `/setup` | One-time wiring: files, platform, give, ask, optional Notion. |
| `/morning` | The whole morning routine in one command. |
| `/daily-chats` | Paste notifications, get one personal opener per person. Zero pitch. |
| `/chrome-chats` | Chrome extension collects names and types drafts. YOU press send. Always. |
| `/chat-coach` | The next right message for any live chat. |
| `/follow-up-sweep` | Day 1 / 3 / 7 follow-ups, value first, zero guilt. |
| `/hand-raiser` | One ask post a week that feeds tomorrow's chats. |
| `/score-my-dm` | Paste a draft: SEND, FIX FIRST, or REWRITE, in two seconds. |
| `/scoreboard` | Logs sent, replies, calls. CSV opens in Excel. Syncs to Notion if connected. |
| `/pipeline` | Where every chat stands. "Move Sarah to booked." "Who needs what today?" |
| `/chat-ladder` | Draws the six-step method as The Chat Ladder visual in The Studio. |
| `/first-week` | Just starting? The gentle 7-day ramp from 5 to 25 starts a day. |
| "spar with me" | A practice partner plays your exact prospect, then scores you. Practice before real sends. |

## 4. Which platform? All of them

The method never changes, only the doorbell. Tell `/setup` your platform (LinkedIn, Instagram, WhatsApp, Facebook or TikTok) and every draft comes out in the right register: what a raised hand looks like there, how the chat sounds, how the give and the ask travel. The full map: [platform guide](https://sell-by-chat-session.vercel.app/platform-guide.html) (also in `references/platforms.md`).

## 5. It learns what works for YOU

When you log a booked call, the scoreboard asks one question: "which message got that?" Your answer is saved to your wins bank, and from then on every draft starts from your own proven lines. The longer you use it, the more it sounds like you on your best day.

## 6. The rules it lives by

- Serve first. Message one never has a pitch, a link, or "quick call?" in it.
- LVO in every reply. Lube: make them feel seen. Value: give something they can use, free, no catch. Offer: open one door.
- You press send. It drafts and types, never sends, never runs unattended.
- Your voice. Everything comes from your VOICE-DNA.md. Say "more like me" to rewrite.

## 7. If something goes wrong

| It says | Do this |
|---|---|
| repository not found | Check spelling: `danielpaulai/sell-by-chat-plugin` |
| Drafts sound generic | Your VOICE-DNA.md is not in this folder. Move it here, run `/setup` again. |
| Cannot find SELL-BY-CHAT.md | Wrong folder. Open Claude Code in your sell-by-chat folder. |
| Chrome skill has no browser tools | Install Claude in Chrome, or use `/daily-chats` and paste. |
| Want the newest version | `/plugin marketplace update ai-founder-circle`, restart Claude Code. |

The only number you control is how many chats you start. 25 a day, about 30 minutes. Roughly 3 in 10 reply, roughly 1 client per 100 chats. The scoreboard never lies, and that is exactly why it works.

## Desktop vs web

The plugin works best in the Claude Code desktop app or terminal. In the web version the install commands may not run; use the manual upload instead: download the zip from sell-by-chat-session.vercel.app/sell-by-chat-plugin.zip and use Upload a plugin, or run it on desktop.
