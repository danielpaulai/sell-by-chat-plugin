---
name: magnet-loop
description: Close the flywheel - paste the comments and DMs from a live hand-raiser post and mine them for the next splinter, reply drafts, and what to fix. Trigger on 'my post is live', 'here are the comments', 'what is my next magnet', 'magnet loop'.
---

# Magnet Loop

Read `${CLAUDE_PLUGIN_ROOT}/references/method.md`. The comments hand you the next splinter; this skill reads the hands.

## Inputs
The live post + its comments (pasted, or scraped via Apify platform actors with the user's post URL). Optionally: DM conversations so far, and delivery count vs comment count.

## Mine
1. **The queue**: count keyword comments vs other comments. Flag anyone who commented but was not delivered to yet - those are the leads leaking.
2. **The language**: harvest every complaint, question and "what about X" in the comments and DMs, verbatim. These are next splinters in the wild.
3. **The next splinter**: cluster them, rank by frequency x emotion, recommend ONE as next month's magnet, with the three comment quotes that prove it.
4. **Reply drafts**: for every unanswered comment type present, draft the reply from counter-scripts rules (never pitch first, one small question). Personal notes for the 3 warmest commenters (real question askers).
5. **The post autopsy**: what pulled (which line got quoted back), what to change next time (keyword confusion, unclear promise, wrong platform), one concrete tweak.

## Output
The loop report: leads leaking + fix, reply drafts ready to paste, the next splinter with evidence, the post autopsy. End with: "run /lead-magnet:pack on the next splinter when ready." Data only from what was provided or scraped; no invented engagement numbers.
