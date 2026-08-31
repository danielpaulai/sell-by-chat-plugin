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

## No Voice DNA yet? One prompt builds it

Run this in the Claude app (claude.ai, where your chat history lives), save the answer as `VOICE-DNA.md` in your folder:

```
You know me from every conversation we have ever had. Build my VOICE-DNA.md from that evidence.

Study how I actually write and talk across our chats, then write the file with these sections:

1. MY SOUND: casual or formal, warm or dry, fast or slow. How long my sentences run (count a few). How I open a message and how I end one.
2. MY WORDS: the 15 words and phrases I use most, each with a real quote from our chats. Include my fillers ("so", "okay", "you know", whatever I actually use) and how often they show up.
3. MY MOVES: how I explain things (stories? numbers? examples?), how I show excitement, how I disagree, how I ask for things. Quote me doing each one.
4. GREETINGS AND GOODBYES: exactly how I say hello and how I sign off, per situation (friend, client, stranger).
5. PUNCTUATION AND EMOJI: my real habits. Dashes or commas, exclamation marks or not, which emoji and how often.
6. NEVER: 10 things I would never write. Words that are not me, tones that are not me, shapes that are not me.
7. WRITE LIKE ME: finish with 5 short rules someone could follow to sound like me, and then prove it: take these three lines and rewrite them in my voice:
   - "I hope this message finds you well. I wanted to reach out regarding your recent post."
   - "Thank you for your interest. I will send over the information shortly."
   - "Just following up on my previous message."

Rules: only real evidence from our conversations. Quote me at least 12 times. If you are not sure about something, leave it out instead of guessing. No inventing, no flattering. Output everything as one markdown file called VOICE-DNA.md.
```

**Order matters:** install → both files in the folder → `/setup` (this is where Notion / Excel get created) → practice → `/morning`. Never `/morning` before `/setup`.

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
