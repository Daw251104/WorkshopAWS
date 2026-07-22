---
title: "Worklog Week 7"
date: 2026-06-16
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---
### Week 7 Objectives:
* Complete Backend API system for Minigame (Sudoku) using Serverless architecture (AWS Lambda).
* Handle complex resource transaction flows, ensuring data integrity within the database.
* Research and apply anti-cheat mechanisms to protect the system against unauthorized client-side interventions.

### Tasks to be implemented this week:
| Day | Task | Start Date | Completion Date | Reference Materials |
| --- | ---- | ---------- | --------------- | ------------------- |
| Tue, Wed | Detailed AWS Lambda System Deployment for minigame feature: <br> - Create API to retrieve list of game levels and personal Highscores. <br> - Initialize game sessions, handle Sanity fee deduction via Transactions, generate random Seed/Map. <br> - Validate results, compute Rank Points based on time, handle fee refunds or add eCoins. <br> - Create API to fetch Server-wide Leaderboard and Friends Leaderboard data. | 16/06/2026 | 17/06/2026 |  |
| Fri, Sat | Develop Anti-cheat Mechanisms & Optimize Gameplay Flow: <br> - Backend Security: completely hide answer arrays from payload sent to Client. Shift all answer-checking logic to server-side processing to prevent hack/code inspection. <br> - Add game completion time validation logic, automatically block and flag API requests with unrealistic completion times. | 19/06/2026 | 20/06/2026 |  |



### Week 7 Results Achieved:
* Enhanced Secure API Design mindset, learned to apply the principle of "Never trust the client".
* Mastered Transaction mechanisms in NoSQL databases to handle virtual currency transactions (eCoin/Sanity) with complete ACID compliance.
* Accumulated real-world experience in analyzing basic game cheat vulnerabilities and building effective anti-cheat solutions.
