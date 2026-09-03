---
name: segment-writer
description: Turn thank-you-page survey answers into segment-matched follow-up - email 3 and 4 rewritten per segment, plus the offer-page headline per segment. Trigger on 'segment my emails', 'survey answers came in', 'personalize the sequence', 'segment writer'.
---

# Segment Writer

Read `${CLAUDE_PLUGIN_ROOT}/references/method.md` and `${CLAUDE_PLUGIN_ROOT}/references/email-templates.md`. The survey told you who each subscriber is; now the emails should speak to their actual situation instead of a crowd.

## Inputs
The 4 survey questions with their answer options (from landing-kit), the base Seven-Day Echo sequence, and the offer. If segments are not defined yet, derive 2 to 4 from the answer combinations - a segment earns its place only if it changes what you would SAY (different example, different objection, different next step). More than 4 segments is admin, not marketing.

## Write
For each segment:
1. **Email 3 (belief shift)**: same teaching, but the example and the "here is how to see it in your business" swap to that segment's world. The passing offer mention names the segment's situation.
2. **Email 4 (story)**: pick or adapt the client story whose STARTING POINT matches the segment; the objection handled inside the story is that segment's objection. Real clients only; if no story fits a segment, say so and use the closest with an honest bridge line.
3. **Offer-page headline variant**: one line that mirrors what they just told you in the survey.
4. Days 0, 1 and 7 stay shared (one voice, one ask); note the single sentence in email 7 that could flex per segment if their tool supports it.

## Output
Per segment: name, who they are in one line, email 3, email 4, headline variant. Plus the setup note: which tag triggers which branch, phrased for Kit/Beehiiv/GHL generically. Same voice rules as always; ratio stays useful-useful-useful-proof-ask.
