---
name: improve-system
description: Review the current session for durable signals (preferences, corrections, decisions, new facts about Paul or his businesses) and save them to the right place in the repo. Use at the end of a session or when Paul types /improve-system.
---

# Improve system

1. Scan the session for signals worth keeping. Only these count:
   - **Preference** — how Paul wants work done (tone, format, length, tools). → `CLAUDE.md` "How to work with Paul"
   - **Correction** — something Claude got wrong that Paul fixed. → `CLAUDE.md` "Rules"
   - **Fact** — new/changed info on Paul or a business (numbers, team, goals). → `knowledge/me/*.md`, date-stamped
   - **Decision** — something decided, with reasoning. → `knowledge/decisions/log.md`
   - **Advisor refinement** — a framework that proved useful/useless. → the advisor's file
2. Ignore one-off task details. If nothing qualifies, say "Nothing worth saving" and stop.
3. Before writing, check for an existing entry that covers it — refine it rather than duplicating.
4. Keep each entry to one line where possible.
5. Report back as a short list: what was saved, where. Flag any judgement calls for Paul to confirm.
