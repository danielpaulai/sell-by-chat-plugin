---
name: scoreboard
description: Log a day of chat activity (sent, replies, calls) to chat-scoreboard.csv, keep the streak, sync to Notion or Excel if set up, and on Fridays or on request write a one-paragraph weekly diagnosis. Trigger on "log my day", "scoreboard", "I sent X today", "read my week".
---

# Scoreboard: the number that never lies

Source of truth: `chat-scoreboard.csv` in the current folder (`date,sent,replies,calls,note`). Config in `SELL-BY-CHAT.md`.

## Logging a day

1. Take their numbers (sent, replies, calls, optional note). Today's date unless they say otherwise.
2. Append the row to the CSV. If `SELL-BY-CHAT.md` records a Notion scoreboard database and Notion tools are available, add the same row there. The CSV opens directly in Excel, that IS their Excel sheet.
3. Reply with the running picture in 3 lines: today vs target, streak, total reply rate vs the ~30% benchmark.

## Reading the week ("read my week", or any Friday log)

Benchmarks: ~30% reply rate over time, ~1 client per 100 chats started, target from SELL-BY-CHAT.md (default 25/day), follow-ups day 1, 3, 7.

Diagnosis logic, one paragraph, warm and direct:
- Low reply rate with decent volume: the opener is the problem. Suggest one rewrite.
- Replies fine but no calls: the questions or the ask are the problem. Suggest which and one fix.
- Low volume: the rhythm is the problem, not the words. Suggest a smaller believable target.
- On target and converting: say so plainly and set next week's number.

Never guilt-trip missed days. Numbers are information, not judgment. No em dashes.
