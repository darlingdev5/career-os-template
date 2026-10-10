---
name: resume-evaluator
description: Run a finished resume through four reviewer personas before it is sent — the ATS keyword screen, the AI first-pass screen, the recruiter six-second scan, and the hiring manager. Also runs an honesty audit. Trigger after any resume is built, or when someone says "check this", "will this pass", or "evaluate before I send".
---

# resume-evaluator

Never deliver a resume without running this. Report findings as PASS / FIX / RISK with the
specific line to change.

## Pass 1 — ATS and keyword screen (mechanical)
Extract the resume text programmatically, then:
- Build the term list from the JD: every noun phrase in the responsibilities and
  qualifications, plus the exact job title.
- Report **hits / total** and list every miss.
- For each miss, decide: can this be added **honestly**? If yes, work it in. If it would
  require claiming experience they don't have, leave it out and name it as a known gap.
- Structural check: standard section headers, parseable dates, contact line present, no
  text trapped in tables or images, no markdown artifacts (stray brackets, raw URLs).

## Pass 2 — AI first-pass screen
Many companies state that AI reviews first, a human second. Assume a model is asked
*"does this candidate meet the stated qualifications?"*
- Walk each listed qualification and mark **met / partially met / not met**, citing the
  line that proves it.
- Anything "not met" that's a stated minimum is a real risk. Say so out loud.
- Years of experience, required domain, and location are the three that get auto-filtered.

## Pass 3 — Recruiter, six seconds
They read: name, current title, current company, most recent bullet, education, keywords.
- Does the top third answer "why this person for this job"?
- Is the summary doing work, or could it belong to anyone?
- Any formatting that makes them squint? Two-line bullets, dense blocks, orphan lines.

## Pass 4 — Hiring manager
Read it as the person who will manage this role.
- Which bullet is the strongest proof they can do the job? Is it in the top three?
- Which bullet is the weakest? Cut or replace it.
- What question would this resume make them ask? Is the candidate ready for it?
- Verdict: **interview / maybe / pass**, and the single change that would move it up a tier.

## Pass 5 — Honesty audit (never skip)
- Every number traced to `metrics.md`? Flag any that isn't.
- Any claim of experience in a domain, tool, or seniority they don't have?
- Any detail the person didn't actually state? Floated ideas are not facts.
- Anything confidential from `profile.md` that leaked in?

## Output
A short report, then the fixes applied. Lead with anything red.
