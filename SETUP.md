# Setup

Two ways in. The fast one is better.

---

## Fast path: start from your resume (5 minutes)

Drop your current resume into this folder and tell your agent:

> Read SETUP.md. Here's my resume — bootstrap my OS from it, then interview me on the gaps.

The agent will extract your roles, dates, skills, and every number you've claimed, fill in
`01-context/`, and then ask you only about what a resume can't hold: which numbers you can
actually defend, how you talk, what you want next, and where you'd never work.

## Slow path: pure interview (20 minutes)

No resume handy, or starting fresh:

> Read SETUP.md and interview me.

---

# Instructions for the agent

You are onboarding someone into their Career OS. Rules:

1. **One question at a time.** Wait for the answer. Never paste a questionnaire.
2. **Write as you go.** Update the file after each answer. Don't batch to the end.
3. **Push back on vague answers.** "Improved engagement" is not a metric. Ask what it was,
   what it became, over what period. If they don't know, it goes under "gaps to close" in
   `metrics.md`, never into the defensible list.
4. **Invent nothing.** Leave the placeholder and move on.
5. **Keep their words.** Their plain phrasing almost always beats your polish.
6. At the end: say what's filled in, what's thin, and what to do next.

## If they gave you a resume first

Extract into the OS, then say which parts you filled and which you need from them:
- Roles, companies, dates, titles → `01-context/roles/<company>.md`
- Every number on the resume → `01-context/metrics.md` as **UNVERIFIED**
- Skills and tools → `01-context/expertise.md`
- Education, certs, links → `01-context/profile.md`

Then your first question is always: **"Here are the numbers on your resume. For each one,
can you defend it if someone asks two follow-up questions?"** Move the yeses to defensible,
the noes to retired. This single pass is the most valuable thing in the setup.

## The interview

### Profile → `01-context/profile.md`
1. Name, city, and where you're willing to work.
2. Current title, company, how long. One line on what the company does.
3. Years in your field? (From your first role in it.)
4. What are you looking for next, in your own words?
5. Hard constraints: comp floor, industries you won't work in, visa, schedule.
6. Links: LinkedIn, portfolio, GitHub, personal site.
7. Anything confidential you must never let into an application?

### Roles → `01-context/roles/<company>.md`, one file each
For each of the last 3–4 jobs:
8. What did you actually own? Not the title, the surface area.
9. The thing you built or changed that you're proudest of. Tell it like a story.
10. A time you were wrong, or shipped something that didn't work.
11. Who you worked with: team size, functions, reporting line.
12. What you learned there that you still use.

### Metrics → `01-context/metrics.md`
13. For each story: what number survives two follow-up questions?
14. Which numbers have you used before that you're NOT confident about?
15. What number do you wish you had but don't?

### Positioning → `01-context/positioning.md`
16. If you had to compete on two or three things, what are they?
17. What roles are an obvious yes? An obvious no?
18. What's the honest gap a sharp interviewer will find?

### Voice → `01-context/voice.md`
19. Paste something you wrote that sounds like you.
20. What phrasings make you cringe in professional writing?
21. Format rules: font, length, anything you always want or never want.

### Targets → `02-work/target-companies.md`
22. Five to ten companies you'd be excited about, and why each.
23. Any anti-targets?
24. Who do you already know at any of them?

## After

Tell them:
- `metrics.md` is the firewall. Read it before writing any bullet, ever.
- Say **"update the OS"** at the end of every work session, or run the `recap` skill.
- Fastest next step: drop in a job description and ask for a tailored resume.
