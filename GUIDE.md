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

Run this in the Claude app or ChatGPT (wherever your chat history lives). Have meeting transcripts? Paste them below the prompt, it works on both. Save the answer as `VOICE-DNA.md` in your folder:

```
You are a voice analysis expert. Your job: extract my authentic communication patterns and build my VOICE DNA profile, so written content can sound exactly like me.

YOUR SOURCE MATERIAL, use whichever applies:
A) Every conversation you and I have ever had in this app: your memory of me plus our chat history. This is real evidence of how I write and think.
B) Any meeting transcripts I paste below this prompt. Transcripts of me actually talking are gold: analyze only MY lines, ignore other speakers.
If you have both, use both. If a pattern only shows up once, it does not count. Patterns must repeat.

METHOD: read everything twice. Extract patterns, not impressions. Quote me directly as evidence, at least 15 direct quotes across the profile. Natural speech beats formal writing. If you are not sure, leave it out. No inventing, no flattering.

BUILD THE PROFILE WITH THESE 8 SECTIONS:

1. CONVERSATIONAL MARKERS. My fillers ("so", "like", "you know", whatever I actually use) with how often they appear, and my transition phrases ("here's the thing...", "the problem is..."). Quote 2 to 3 real sentences for each. Say if I am a heavy user or a light user.

2. SENTENCE PATTERNS. Analyze 20 to 30 of my sentences. Average length, the mix of short punchy vs long flowing, how I open sentences, whether I ask questions. One quoted example per pattern.

3. VOCABULARY PROFILE. How technical I get (1 to 5, with evidence), the jargon I use without explaining, my reading level, and any unusual words I favor.

4. EMOTIONAL SIGNATURE. My default tone (direct? warm? hyped? measured?) with 3 quotes. My backup tone when things get hard. How I show certainty vs uncertainty, quoted.

5. TOP 10 SIGNATURE PHRASES. Phrases I repeat across conversations, each with a rough count, when I use it, and one full quoted sentence. These make content instantly recognizable as mine.

6. IDEA FLOW. How I naturally structure explanations (problem then solution? story then lesson? question then answer?). Quote one full explanation of mine showing the pattern. How I build credibility, how I handle complexity, how I wrap up.

7. AUTHENTICITY MARKERS. 5 to 7 quirks that would make someone say "that is exactly how they talk": my metaphors, my humor, my values that keep showing up, my personal touches. Each with evidence.

8. RED FLAGS: WHAT I WOULD NEVER SAY. Corporate words I never use, tones that are not me, structures that would feel fake in my name. List 7 to 10 specific violations with a one-line why for each.

FINISH WITH: "WRITE LIKE ME", 5 short rules a writer could follow, and then prove it: rewrite these three lines in my voice:
- "I hope this message finds you well. I wanted to reach out regarding your recent post."
- "Thank you for your interest. I will send over the information shortly."
- "Just following up on my previous message."

OUTPUT: one markdown file called VOICE-DNA.md, all 8 sections plus WRITE LIKE ME, with the quotes in place. Specific beats vague, everywhere.
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

The plugin works best in the Claude Code desktop app or terminal. In the web version the install commands may not run; use the manual upload instead: download the zip from sell-by-chat-session.vercel.app/sell-by-chat-plugin.zip (keep it zipped), then Settings, Plugins, Upload a plugin, pick the zip.
