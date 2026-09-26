---
name: ask-the-board
description: Put a question to Paul's personal board of advisors. Each advisor answers through their own frameworks, then a chair gives a final call with confidence. Use when Paul types /ask-the-board or asks what his board/advisors would say.
---

# Ask the board

Input: the question after the command.

1. Read `knowledge/me/profile.md`, `knowledge/me/businesses.md`, `knowledge/decisions/log.md`, and every file in `knowledge/board/` (skip README). If `knowledge/me/` is mostly empty, say so in one line and suggest `/interview-me` — then answer anyway with stated assumptions.
2. For each advisor, answer in 3–5 bullets using *their* frameworks and questions from their file, applied to Paul's actual businesses and numbers. Be specific; reference his context. No quotes attributed to real people.
3. The Devil's Advocate goes last and attacks the emerging consensus.
4. Then **Chair's call**:
   - Recommendation (one sentence)
   - Confidence (%)
   - Where the board disagreed and why the chair sided as it did
   - Next 3 actions, each doable this week
   - Cheapest test to validate
5. Keep the whole answer under ~500 words unless asked for depth.
6. If the answer produces a decision Paul accepts, offer to append it to `knowledge/decisions/log.md`.

Format:
```
## [Advisor name] — [lens]
- ...
## Chair's call — [confidence]%
...
```
