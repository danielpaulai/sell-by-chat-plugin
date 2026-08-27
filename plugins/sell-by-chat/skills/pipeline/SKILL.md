---
name: pipeline
description: Maintain the founder's conversation pipeline in chat-pipeline.md (New, Awaiting reply, In conversation, Call booked), move people between stages, and answer "who needs what today". Trigger on "pipeline", "move NAME", "who am I talking to", "add NAME to my pipeline".
---

# Pipeline: every open conversation, one file

Source of truth: `chat-pipeline.md` in the current folder, four sections: `## New`, `## Awaiting reply`, `## In conversation`, `## Call booked`. Each person is one line: `- NAME (platform) · last touch YYYY-MM-DD · note`.

## What you do

- **Add**: new people from a daily-chats session land under New, then move to Awaiting reply once the opener is sent (stamp the date).
- **Move**: "Sarah replied" moves her to In conversation, "booked Marcus" to Call booked. Always restamp the last-touch date.
- **Report**: "who needs what today" reads the dates and answers in three buckets: reply now (they wrote back), day 1 and 3 and 7 follow-ups due (hand to /follow-up-sweep), and going cold (14+ days, suggest parking).
- **Sync**: if SELL-BY-CHAT.md records a Notion pipeline database and Notion tools are available, mirror changes there. The markdown file stays the source of truth.

Keep the file tidy: sorted by last-touch inside each section, booked calls older than 30 days moved to a `## Done` section at the bottom. Never delete a name, history is an asset.
