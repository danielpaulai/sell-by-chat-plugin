---
name: score-my-dm
description: Grade a draft DM in two seconds against the five human-opener rules (or the ladder rules for mid-conversation messages) before it gets sent. Trigger on "score this", "check this DM", "is this good to send", or when the user pastes a draft message and asks for a verdict.
---

# Score My DM: the two-second gate

The founder pastes a draft. You return a verdict, fast and short.

## For an opener

Five checks, one line each, YES or NO with the fix baked into the reason:
1. About THEM, not the sender
2. Mentions something specific only they could have done
3. Sounds like a person, not a template
4. Exactly one easy question at the end
5. Zero pitch, zero link, zero call ask

Then: **SEND** (5 yes), **FIX FIRST** (3 to 4, show the rewritten version), or **REWRITE** (worse, show the rewritten version). The rewrite matches their `VOICE-DNA.md` and their platform's register (from `SELL-BY-CHAT.md`).

## For a mid-conversation message

Check instead: does it MIRROR them (roughly their message length and energy)? One question max, under 30 words, matches the prospect's pace, gives before asking, no pitch before the gap is in the prospect's own words, and if it is an ask, two concrete times. Same three verdicts.

Total output: under 10 lines. This is a gate, not an essay.

## Words

Very simple words, the kind a 12 year old knows. Short sentences. If a word sounds like a business book, swap it for the word a friend would use. Never use an em dash.

## Learn from what works

Before drafting, read (when present in the plugin and folder):
- `${CLAUDE_PLUGIN_ROOT}/references/voice-rules.md`: the sound. These rules beat everything.
- `${CLAUDE_PLUGIN_ROOT}/references/example-bank.md`: imitate the shapes, never the words.
- `chat-wins.md` in the working folder: the founder's own messages that got replies and booked calls. Their proven lines beat any fresh guess. Reuse their winning shapes first.

## Platform register

Read `SELL-BY-CHAT.md` for the founder's platform, then `${CLAUDE_PLUGIN_ROOT}/references/platforms.md` for that platform's raised hands, sound, give, ask and quirks. Write in that register.
