# Career OS

A job search that compounds instead of starting over every time.

Most job searching is amnesia. You write a resume, learn something in an interview, then
the next application starts from a blank page. This is a folder that remembers: who you
are, what you're allowed to claim, what worked, and what you promised never to do again.
Point an AI agent at it and it can write *as* you instead of *about* you.

---

## Start here

Open this folder with an AI agent (Claude Code, Claude Cowork, Cursor, or similar).

**Fastest way in** — drop your current resume in this folder and say:

> Read SETUP.md. Here's my resume, bootstrap my OS from it, then interview me on the gaps.

It extracts your roles, dates, skills, and every number you've claimed, then asks you only
what a resume can't hold. About 5 minutes.

**No resume handy?**

> Read SETUP.md and interview me.

Twenty minutes, one question at a time. You never stare at a blank template.

---

## How it's built

Three folders, in the order an agent should read them.

**`01-context/`** — who you are. Stable for months.
- `profile.md` — basics, constraints, non-negotiables
- `positioning.md` — the two or three angles you compete on
- `voice.md` — how you write, and what makes a draft sound like a robot
- `metrics.md` — the only numbers you're allowed to use, and the ones you've retired
- `expertise.md` — skills, tools, domains
- `roles/` — one file per job you've held, with the real stories

**`02-work/`** — the search itself.
- `application-log.md` — where you applied, what angle, what happened
- `lessons.md` — mistakes made once, never again
- `target-companies.md` — your list and your anti-list
- `applications/<date>_<company>_<role>/` — every artifact for one application

**`03-automations/`** — four working skills.
- `resume-tailor` — strategic read of a JD, then a tailored resume in your format
- `resume-evaluator` — ⭐ runs the finished resume past the ATS, the AI first-pass screen,
  a six-second recruiter scan, and the hiring manager, plus an honesty audit
- `recap` — end-of-session maintenance so the OS stays current instead of rotting
- `job-scout` — find roles, apply hard gates, score, draft the strongest

---

## The four rules that make it work

**One source of truth per fact.** A metric lives in `metrics.md`. A story lives in its role
file. Everything else links. Duplication is how an OS starts lying to you.

**Never invent a number.** An unknown metric is a follow-up item, not a blank to fill.

**Write the lesson down the day you learn it.** Every correction you make to a draft is a
rule your future agent should already know.

**Recap every session.** Five minutes of filing beats an hour of reconstruction.

**Evaluate before you send.** Writing the resume is the easy half.

---

## Why bother

After a few weeks this folder knows your defensible numbers cold, the phrasings you reject,
which companies ghosted you and why, and what you said in every interview. Draft one starts
at the quality draft ten used to be.

Built by [Nataly C](https://linkedin.com/in/nataly-chacon). Free to copy and fork.
