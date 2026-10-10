---
name: recap
description: End-of-session maintenance for the Career OS. Trigger on "recap", "update the OS", "wrap up", "log this", or any signal the session is ending.
---

# recap

The OS only works if it stays current. Turn a working session into durable, routed updates.

## Step 1 — Harvest
Review the session for anything that changed ground truth:
- An application sent, or a status change
- A newly confirmed or corrected metric, story, or fact
- A correction the person made to voice, positioning, or format — anything to never repeat
- A new target or anti-target
- A new artifact worth filing
List what you found before writing anything.

## Step 2 — Route each change to exactly ONE home
| Change | Goes to |
|---|---|
| Application sent / status change | `02-work/application-log.md` + artifacts in `02-work/applications/` |
| A correction or pattern to never repeat | `02-work/lessons.md` |
| New or confirmed metric | `01-context/metrics.md` |
| Voice, positioning, or format refinement | `01-context/voice.md`, `positioning.md` |
| New role detail or story | `01-context/roles/*.md` |
| New target or anti-target | `02-work/target-companies.md` |
| What a fresh chat needs to know | `02-work/HANDOFF.md` |

One source of truth per fact. Cross-link, don't duplicate.

## Step 3 — Discipline
- **Never invent a metric.** An unknown number is a follow-up item.
- **Preserve history.** When a fact supersedes an old one, note "supersedes X (date)".
- **Date everything.** Convert "last week" to an absolute date.
- **Don't loosen a standing rule** without being told to.

## Step 4 — Log it
Append a dated entry to `CHANGELOG.md`: what changed, why, open follow-ups.

## Step 5 — Show, don't silently ship
Present a compact diff-style summary grouped by file, with the exact lines added. Let them
approve or adjust. Only then is the recap done.
