---
name: magnet-radar
description: Competitive research - scrape 6-10 competitors' lead magnets and opt-in pages, plot them on the Magnet Map, find the empty promise nobody is claiming. Trigger on 'what are competitors giving away', 'magnet radar', 'competitor lead magnets'.
---

# Magnet Radar

Read `${CLAUDE_PLUGIN_ROOT}/references/method.md`. Copying a crowded promise buys a smaller slice of a shrinking pie; the money is in the promise nobody has claimed.

1. Get 6 to 10 competitors: people who sell to the SAME BUYER (not the same job title). Ask, or pull from BUSINESS-BRAIN.md / a quick WebSearch.
2. For each, fetch their opt-in (Apify rag-web-browser / website-content-crawler on their site and link-in-bio; WebFetch fallback): what they give away, the exact promise, the format, the friction (fields asked, steps).
3. Table: competitor | giveaway | promise | format | friction | where it is thin (be specific: "promises a system, delivers 6 tips", "no numbers", "written for anyone").
4. Plot each on the Magnet Map (Trap / Dust / Vault / Snap) and say why. Most will land in Vault or Dust.
5. Group by PROMISE, not format. Name the crowded promise and the valuable-but-empty one.
6. Deliver 3 to 5 gaps ranked by how well the user's owned assets can fill them, each with: the gap, why it is empty, what the user has that fills it, difficulty. Recommend one and hand off to /lead-magnet:pick or /lead-magnet:pack.

Never fabricate a competitor or a page you could not fetch; list failures honestly.
