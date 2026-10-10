---
name: resume-tailor
description: Tailor a resume to a specific job posting and draft application free-text answers. Trigger whenever a job description or a link to one is shared, when someone types /resume, or when they mention applying to a role. Trigger even on a bare URL with no instruction.
---

# resume-tailor

Default behavior: strategic read first, then a tailored resume, then run `resume-evaluator`.
Never skip step 1 and never skip step 5.

## Step 0 — Load the OS
Read in this order: `01-context/profile.md`, `01-context/metrics.md`,
`01-context/voice.md`, `01-context/positioning.md`, `02-work/lessons.md`, and the
relevant files in `01-context/roles/`.

If given a link, fetch it. If the page is client-rendered and returns a shell, say so and
ask for a paste rather than guessing at the content.

## Step 1 — Strategic read (do this before writing anything)
Report back, briefly:
- **What this role is actually for.** Not the title — the problem they're hiring to solve.
  It's usually visible in the first responsibility and the "success looks like" section.
- **Which angle wins** from `positioning.md`. Commit to one. Blends read as mush.
- **The honest gaps.** Stated minimums they don't meet. Say it plainly now, not after.
- **Verdict:** worth the effort, worth it only with a referral, or skip. Respect the skip.

## Step 2 — Write the summary
The summary names **where the company is headed and how this person closes that gap.**
Not a list of attributes. If the summary could appear on anyone else's resume, rewrite it.
Mirror the JD's own vocabulary where it's honest to do so.

## Step 3 — Write the bullets
- One idea per bullet, two lines max, metric at the end.
- Every bullet starts with a verb. Current role: present tense for ongoing
  responsibilities, past tense for completed achievements, grouped so it looks deliberate.
- Order the current-role bullets to mirror the JD's own responsibility order. A recruiter
  reading top-down should see their priorities in their sequence.
- **Numbers come only from `metrics.md`.** If the right number doesn't exist, flag it.

## Step 4 — Format
Follow `01-context/voice.md` exactly: font, color, length, bullet rules. Build the file
rather than pasting text into chat, and verify the page count after rendering.

## Step 5 — Hand off to `resume-evaluator`
Always. Then report what it found and fix anything red before delivering.

## Free-text answers
Application essays are read by humans and are an effort signal. Write them specific and
story-driven. De-duplicate story climaxes across a set — two answers ending on the same
win reads as one story stretched thin.
