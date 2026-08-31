---
name: morning
description: The 15-minute morning routine, one command: pipeline check, today's openers, follow-ups due, and the day's plan. Trigger on "morning", "run my morning", "morning chats", "start my day".
---

# Morning: the whole routine in one run

## The fit filter (ICP + FIT, both must pass)

Before a single opener gets drafted for anyone, run two checks. Both must pass. Either fails: NO conversation. Skip them, list them under "Skipped" with a one-line reason, and never message them.

**Check 1 · ICP:** does this person match who the founder helps (from the ICP file and SELL-BY-CHAT.md)? Right kind of person, right kind of business, right kind of problem. A raised hand from the wrong person is still the wrong person.

**Check 2 · FIT:** is this a real conversation worth having?
- A real human with a real business, not a bot, a spam account, or an empty profile
- Not someone trying to sell TO the founder (pitch-slappers get skipped, not answered)
- Not a competitor doing recon
- Not someone the founder already talked to who said no or asked to be left alone
- The raised hand is genuine: they engaged with the founder's actual content, not a mass-like sweep

No exceptions for volume. Five right people beat twenty five wrong ones. The daily 25 is a ceiling, never a quota to fill with bad fits.


Read `SELL-BY-CHAT.md`, `chat-pipeline.md` and `chat-scoreboard.csv` first. Then, in order:

1. **Replies first**: list everyone in the pipeline who wrote back and needs an answer. For each, draft the next right message (the chat-coach ladder: easy question, deeper, commit, give, or the two-times ask).
2. **Follow-ups due**: from pipeline last-touch dates, list day 1, day 3 and day 7 people and draft each follow-up (value-first, zero guilt).
3. **Fresh starts**: ask them to paste today's raised hands (notifications, story replies, comments, depending on their platform). Draft an opener for each, in their voice, zero pitch. If they have the Claude Chrome extension, offer to run /chrome-chats instead so the browser does the collecting.
4. **The plan**: one summary line: "X replies to answer, Y follow-ups, Z fresh openers. That is your 25. Log the scoreboard when you are done."
5. Update the pipeline stamps for everything drafted, and remind them to log tonight.

Keep the whole output scannable: three sections, messages ready to copy, nothing else.

**Always end with the next command:** "Send them now. Tonight: /scoreboard to log it. Lost? /next."

## Words

Very simple words, the kind a 12 year old knows. Short sentences. If a word sounds like a business book, swap it for the word a friend would use. Never use an em dash.

## Learn from what works

Before drafting, read (when present in the plugin and folder):
- `${CLAUDE_PLUGIN_ROOT}/references/voice-rules.md`: the sound. These rules beat everything.
- `${CLAUDE_PLUGIN_ROOT}/references/example-bank.md`: imitate the shapes, never the words.
- `chat-wins.md` in the working folder: the founder's own messages that got replies and booked calls. Their proven lines beat any fresh guess. Reuse their winning shapes first.

## Platform register

Read `SELL-BY-CHAT.md` for the founder's platform, then `${CLAUDE_PLUGIN_ROOT}/references/platforms.md` for that platform's raised hands, sound, give, ask and quirks. Write in that register.

## The two must-have files

Before drafting anything, check VOICE-DNA.md and the ICP file exist in this folder. Missing? Stop and say: "Run /setup first, it builds these with you in ten minutes. Nothing here works well without them." Never draft from guesses.

## The de-AI pass (always last)

Before showing ANY draft, run it through `${CLAUDE_PLUGIN_ROOT}/references/de-ai.md`: kill the AI cliches, corporate words, hedging and robot shapes, then the three-second test (would a friend type this on their phone? could it have gone to 200 people? does it smell like a template?). Fix failures silently. The founder must never have to say "this sounds like AI".
