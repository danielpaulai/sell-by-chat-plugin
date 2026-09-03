---
name: prompt-magnet
description: Build a PROMPT-format tiny win - a copy-paste AI prompt that does the client's work for them. The strongest format right now. Trigger on 'prompt magnet', 'give away a prompt', 'AI tool lead magnet'.
---

# Prompt magnet

Read `${CLAUDE_PLUGIN_ROOT}/references/method.md`. This format wins because they end with a working thing, not knowledge about a thing.

Build spec:
1. The prompt does ONE job (the splinter's fix), takes ONE input the person already has (a transcript, a post, a voice note, a URL), and produces a finished usable output in one run.
2. Structure the prompt itself: role line, the input slot marked [PASTE HERE], numbered instructions, output format spec, 3-5 quality rules in the user's methodology (this is what makes it uncopyable), and one line telling the AI to ask if input is missing.
3. Wrap it for delivery: a one-paragraph "how to use" (open Claude or ChatGPT, paste, replace the slot), the prompt in a copy block, one worked example of real output, and the pointer.
4. Test before shipping: run the prompt yourself on a plausible input; if the output is weak, tighten the quality rules, never lengthen the instructions.

Anti-patterns: prompts that need 5 inputs, prompts that teach instead of produce, "mega prompts" over a page.
