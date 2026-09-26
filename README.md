# Paul OS

Personal operating system for Claude Code: a board of advisors that knows your businesses, and a memory that improves every session.

## Use
Open this repo in Claude Code (CLI, desktop, or claude.ai/code), then:

| Command | Does |
|---|---|
| `/interview-me` | Claude interviews you and fills `knowledge/me/`. Do this first. |
| `/ask-the-board <question>` | Each advisor answers through their frameworks; the chair gives a final call with confidence. |
| `/improve-system` | Saves preferences, facts and decisions from the session so the system gets sharper. |

## Make it better
- Drop real source material (transcripts, book notes) into `knowledge/board/sources/<advisor>/` and ask Claude to refine that advisor's file.
- Swap advisors freely — copy a file in `knowledge/board/`, keep the headings.
