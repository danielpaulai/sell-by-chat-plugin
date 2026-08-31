---
name: next
description: Tell the founder the one next step and the exact command, based on where they actually are (files present, days logged, pipeline state, time of day). Trigger on "next", "what's next", "what do I do now", "next step", "I'm lost".
---

# Next: the one next step

Look at the folder and answer with ONE step and its exact command. Never a menu, never a list of options. One step.

## The decision path (top to bottom, first match wins)

1. No `VOICE-DNA.md` and no `SELL-BY-CHAT.md` → "Run /setup. It takes ten minutes and I will walk you through everything, even if you have no files yet."
2. `SELL-BY-CHAT.md` missing → "Run /setup."
3. Setup done but `chat-scoreboard.csv` has zero logged days and no sparring has happened (no note of it) → "Practice one round first. Say: spar with me. Then send your First Five."
4. Zero days logged → "Time to send. Run /morning, paste today's raised hands, send five. Then: /scoreboard to log it."
5. Fewer than 7 days logged → "You are in week one. Run /first-week to see today's target, or straight to /morning."
6. Morning (before ~1pm) and today not logged as sent → "/morning."
7. Evening and today has sends but no log → "Log it: /scoreboard."
8. Pipeline has people awaiting reply 1, 3 or 7 days → "/follow-up-sweep, X people are due."
9. Everything current → "You are on track. Next: tomorrow morning, /morning. If you want extra reps today: spar with me, or write this week's hand-raiser with /hand-raiser."

Answer in at most three short lines: where they are, the one next step, the exact command. Warm, zero judgment about gaps.
