# The de-AI pass · run on EVERY draft before showing it

The whole point of this plugin is that messages sound like a real person, not like AI. So every draft (opener, reply, follow-up, post, anything) gets this pass as the LAST step, after voice matching. If a draft fails, rewrite it before the founder ever sees it.

## Kill on sight

**AI cliches:** "In today's fast-paced world" · "Let's dive in" · "unlock" · "unleash" · "harness the power" · "It's no secret that" · "The key takeaway" · "At the end of the day" · "game-changer" · "elevate" · "empower" · "seamless" · "journey" (as a metaphor) · "I hope this finds you well"

**Corporate words:** leverage → use · utilize → use · optimize → improve · facilitate → help · streamline → simplify · synergy · ideate · circle back · touch base · reach out → message · "move the needle"

**Hedging:** "It's important to note" · "It's worth mentioning" · "arguably" · "potentially" (when you mean probably) · "various" · "numerous" · "myriad" · "plethora"

**Robot shapes:**
- Three sentences in a row that start the same way
- A rhetorical question you answer yourself
- Exactly three of everything (three bullets, three examples, every time)
- Announcing emphasis: "Importantly," "Crucially," "Notably"
- Perfectly parallel constructions ("If X, then A. If Y, then B.")
- Em dashes. Never. Use a comma, a full stop, or "and"

## Add what humans do

- **Vary the rhythm.** Some sentences five words. Some fifteen. Never all the same length.
- **Contractions.** "It's", "you're", "that's". People type like that.
- **Specifics beat vague.** "your post about hiring a VA" beats "your recent content". A real detail is the strongest anti-AI signal there is, because AI cannot know it.
- **Their words.** Mirror the exact words the prospect used. If they said "drowning", you say "drowning", not "overwhelmed".
- **Imperfection is fine.** A lowercase start, a "ha", a trailing thought. Polish is what makes it smell like AI.

## The three-second test

Read the draft out loud, in the founder's voice. Ask:
1. Would a friend actually type this on their phone?
2. Could this exact message have gone to 200 people? (If yes, it fails. It must only make sense for THIS person.)
3. Does it smell like a template, a newsletter, or a brand? (Any yes: rewrite.)

If a draft fails any of the three, fix it silently and show only the fixed version. The founder should never have to say "this sounds like AI".

## The deep pass (for posts and anything longer than a DM)

The list above is the fast pass for short messages. For hand-raiser posts, follow-up value drops, and anything over ~50 words, also run the full anti-slop references in `anti-slop/`:

- `anti-slop/lexical-blacklist.md`: the 50-section banned-word list, research-backed. Scan the draft against it AFTER writing, never while writing.
- `anti-slop/structural-tells.md`: the shapes that give AI away (parallel triads, fake dialogue, pseudo-wisdom closers).
- `anti-slop/humanization-playbook.md`: what to add back so it reads like a person.
- `anti-slop/copy-standards.md`: the direct-response section applies to DMs and follow-ups.

**The override that always wins:** the founder's genuine VOICE-DNA.md beats every list. If they really say "at the end of the day" in voice notes, it stays. Only word choices can be overridden this way. Specificity, structure and the three-second test are never overridable.

**The core idea, from the engine:** slop is output where the effort to consume it exceeds the effort that went into making it. The job is not avoiding AI words. The job is refusing to ship the statistical average. A real detail about a real person is the strongest anti-slop move there is.
