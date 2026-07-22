---
title: "Worklog Week 10"
date: 2026-07-07
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---
### Week 10 Objectives:
* Build a local Generic Logging system for the Minigame to monitor player actions.
* Upgrade multi-layered Zero-Trust security architecture and finalize match lifecycle management APIs (error checking, submission, score calculation).

### Tasks to be implemented this week:
| Day | Task | Start Date | Completion Date | Reference Materials |
| --- | ---- | ---------- | --------------- | ------------------- |
| Tue | Build Generic Logging Architecture on Redux for Minigame: <br> - Design Log System: Create new Redux structure to store player action logs. <br> - Integrate into Sudoku Component: Update Sudoku Client, connect to Redux to automatically clear logs when starting a new session. | 07/07/2026 | 07/07/2026 |  |
| Wed | Anti-cheat Payload Optimization (Zero-Trust) and DynamoDB RCU Savings: <br> - Optimize Log Reducer: Change log storage mechanism from sequential history to overwrite mechanism, limiting log array length, reducing bandwidth load, and saving RCUs when compressed and sent to DynamoDB. | 08/07/2026 | 08/07/2026 |  |
| Thu, Fri, Sat | Update Anti-cheat System, Zero-trust Architecture & Full-stack Data Sync: <br> - Multi-layer Anti-cheat Optimization: Integrate timestamp-based move log analysis algorithm. <br> - Complete Match Lifecycle Management APIs: <br> + Process mid-game board validity checking, deduct and manage check count (checkCount) directly on DB. <br> + Process submission, calculate Rank Points, and issue rewards based on completion time and remaining checks. | 09/07/2026 | 11/07/2026 |  |



### Week 10 Results Achieved:
* Successfully applied Zero-Trust principles in Client-Server system design, ensuring all critical operations and resource mutations are monitored and decided by the Server.
* Advanced Cloud Cost Optimization skills, learning how to refine Frontend data structures to reduce overhead on Backend and Database (DynamoDB).
