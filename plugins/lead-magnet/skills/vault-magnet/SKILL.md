---
name: vault-magnet
description: Build a VAULT-format tiny win - a curated database (30-60 real entries, each annotated with your judgement) for the buyer who thinks "I do not know what good looks like". Volume plus judgement. Trigger on 'vault magnet', 'database lead magnet', 'curated list magnet'.
---

# Vault magnet

Read `${CLAUDE_PLUGIN_ROOT}/references/method.md`. Careful: a raw list is Dust. The judgement column is the product.

Build spec:
1. One entry type (hooks, tools, subject lines, niches, prompts...), 30 to 60 real entries. Gather from the user's own archive first, then Apify research (platform scrapers, rag-web-browser) with sources kept.
2. Every entry carries the judgement fields: what it is, when to use it, the one-line why-it-works, and a rating or tag in the user's own taxonomy. An entry without judgement gets cut.
3. Sort by the buyer's situation, not alphabetically. Add a "start with these 5" strip at the top so the vault has a five-minute win inside it.
4. Ship via /lead-magnet:build-the-file as a filterable single-file HTML table (search box, tag filters, works offline) plus print view; or hand off a CSV if they prefer a spreadsheet/Notion.
5. The pointer rides at the top and bottom: "the vault shows you what good looks like; [OFFER] makes yours."

Anti-patterns: padded entry counts, missing sources, no judgement column, alphabetical sorting.
