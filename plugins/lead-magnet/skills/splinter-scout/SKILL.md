---
name: splinter-scout
description: Research engine - mine REAL splinters in the market's own words using Apify (Reddit, Instagram, TikTok, web) plus what is already working for competitors, ranked by evidence. Trigger on 'find splinters in the wild', 'research my lead magnet', 'what is my market complaining about', 'splinter scout'.
---

# Splinter Scout

Read `${CLAUDE_PLUGIN_ROOT}/references/method.md`. The goal: a splinter board built from VERBATIM market language, not brainstormed guesses. Comments are the leads; complaints are the splinters.

## Inputs
Ask only for: the niche/person, and 3 to 5 places they hang out (subreddits, hashtags, creators, forums). If BUSINESS-BRAIN.md or an ICP doc exists, read it first and propose the places yourself.

## Sweep (use Apify MCP actors when connected; WebSearch as fallback)
Run 2 to 4 of these, matched to where the person lives:
1. **Reddit** (reddit-scraper-lite): pull top + recent posts from the subreddits; harvest complaint sentences and questions, with upvote counts.
2. **Instagram / TikTok** (instagram-scraper, tiktok-scraper): pull recent posts from 5 to 8 creators serving this buyer; collect giveaway posts (keyword-comment posts especially), their COMMENT counts (not likes), and complaint language from captions and comments.
3. **Web/forums** (rag-web-browser or website-content-crawler): niche forums, review sites, "why is X so hard" searches.
4. Log every source. Never invent a quote; every splinter cites where it came from.

## Synthesize
1. Cluster raw complaints into 3 problem areas x 3 splinters, each splinter a VERBATIM or lightly trimmed quote, with source + signal strength (upvotes/comments/frequency).
2. Note which giveaway formats are pulling comments right now in this niche, and which are tired (appears 3+ times, below-median engagement).
3. Rank the 9 splinters by: frequency x emotion x fixability-with-owned-assets. Recommend ONE with a two-sentence case.
4. Flag gaps: promises nobody in the niche is making (from the competitor giveaways seen).

## Output
The evidence board as markdown: sources swept, the 3x3 splinter board with quotes and signals, format heat-check, the recommended splinter, and the one-line handoff to /lead-magnet:pack. If scraping fails or returns thin data, say so plainly and fall back to guided brainstorming - never pad with invented quotes.
