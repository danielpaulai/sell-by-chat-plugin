---
name: template-magnet
description: Build a TEMPLATE-format tiny win - a fill-in-the-blank asset (email, post, plan, doc) the person completes in minutes. Trigger on 'template magnet', 'fill in the blank', 'swipe template'.
---

# Template magnet

Read `${CLAUDE_PLUGIN_ROOT}/references/method.md`.

Build spec:
1. One finished artifact type (an email, a one-page plan, a bio, a proposal section), never a bundle.
2. Write the template with [BRACKETED SLOTS], each slot labeled with what goes in it and one real example under it. 7 slots maximum; more means it became homework.
3. Include one completely filled example so they see the finished thing before they start (the worked example does half the selling).
4. Add a 3-line "make it yours with AI" note: paste the template plus their facts into Claude and ask it to fill the brackets in their voice.
5. End with the pointer.

Anti-patterns: templates that need a strategy decision before slot one; more than one page; explaining the theory behind each slot.
