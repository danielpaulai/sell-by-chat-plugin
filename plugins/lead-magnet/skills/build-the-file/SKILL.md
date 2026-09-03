---
name: build-the-file
description: Output engine - build the finished lead magnet as a real, branded, single-file deliverable (HTML that prints to a clean PDF, or a working interactive tool). The room and the moves decide; this skill ships. Trigger on 'build the file', 'make the actual magnet', 'produce my lead magnet', or when a Tiny Win Pack is pasted in.
---

# Build the File

Read `${CLAUDE_PLUGIN_ROOT}/references/method.md`. This is where the magnet becomes a thing someone can be handed.

## Inputs
The decisions (from a Tiny Win Pack, the Build Room export, or the move skills): name, headline, splinter, person, format, the 5-step fix, the pointer. Brand: read BUSINESS-BRAIN.md / brand tokens if present; otherwise ask for a site URL or logo to sample colors from, or default to Purely Personal-style ink/cream/red with their name on it.

## The build
ONE self-contained HTML file, no external assets except Google Fonts:
- A4 pages (`.page`, 210mm x 297mm, page-break-after) with print CSS (@page margin 0, print-color-adjust exact) and a comment at the top: print with margins none, backgrounds on.
- Page order: cover (name huge, headline, their name and positioning line, one CSS-only shape, no stock images) → "what this is / who it is for / how long it takes" → the fix, laid out properly (script blocks in mono on tinted panels, fill-in lines people can write on when printed, checklists with drawn boxes, callout boxes with accent border) → the pointer page, exactly as written → about/contact.
- For interactive formats (calculator, scorecard): the same file is a WORKING tool (vanilla JS, self-contained) plus a printable fallback view.
- Typography: heading font + body font, nothing under 9pt, body max 72 characters wide. Max 3 type sizes per page.
- Content rule (the one that matters): use ONLY the copy provided or approved. No filler sentences, no invented stats, no fake testimonials. A sparse page gets flagged, not padded.

## Deliver
1. The file, saved and named `the-<slug>.html`.
2. A page-by-page list of what is on each page and where it came from.
3. The print settings, and the reminder to read it end to end on a phone before it goes anywhere near a post.
4. Offer next: /lead-magnet:landing-kit and /lead-magnet:seven-day-echo.
