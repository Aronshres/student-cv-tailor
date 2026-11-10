# Student CV Tailor

A Claude skill for students that builds your master CV once, then tailors it to every internship, placement or graduate role you apply for.

Built for UK students in placement season, by a student who was applying to placements with three pieces of coursework due and a flight to catch.

## What it does

1. **Builds your master CV.** Upload your current CV (or start from nothing) and it asks you a few questions at a time to fill the gaps: projects, jobs, societies, numbers and skills. Everything you've done ends up in one place.
2. **Tailors it to each role.** Paste a job description and you get a one-page, ATS-friendly CV for that role as a Word file and a PDF.
3. **Reviews it like a recruiter.** A strict recruiter-style gap analysis, a simulated ATS scan and a fit score out of 5.
4. **Tells you what to do next.** 2 or 3 specific things to do to become a stronger candidate, with rough time costs. If the same gap keeps coming up across applications, it tells you that's the one to fix first.

There's a **quick mode** too, if you just want the CV without the full review.

## What it won't do

It never makes up experience, numbers, grades or tools. Anything it isn't sure about is marked **[check]** for you to confirm. Everything on your CV can come up at interview, so honesty comes first.

## Install

1. Download `student-cv-tailor.zip` from the [latest release](../../releases/latest). Don't unzip it.
2. In Claude, open **Settings** and find the **Skills** section, then upload the zip. You'll need code execution and file creation turned on.
3. Optional but recommended: connect **Google Drive** in Claude, so your master CV is saved and kept up to date automatically.

## Getting started

Start a new chat and say:

> Help me make my master CV

Setup takes about 10 to 15 minutes and only happens once. It's quicker if you have these ready:

- Your current CV, even an old or rough one (a LinkedIn profile export works too)
- Your grades: predicted or achieved, plus A-levels or equivalent
- Links: GitHub, portfolio, LinkedIn, anything you've built or run
- Rough numbers: sales, users, team sizes, money raised, followers
- A list of jobs, societies, volunteering, awards and hackathons, with rough dates

Then, for each application:

> Tailor my CV for this role: [paste the job description]

Or for the fast version:

> Quick CV for this role: [paste the job description]

## Format

Every CV comes out the same way: Calibri, single column, clear section headings with a line under each, no tables, icons or photos, and one page by default. Section order changes with your experience level, so a first-year with no jobs yet and someone who's done an internship each get a structure that suits them.

Files are named like `Julian Smith - CV - Google Software Engineering Placement`.

## Privacy

Your CV stays in your own Claude account and, if you connect it, your own Google Drive. I never see it. Don't share your master CV file if you pass the skill on to someone else.

## A note on the ATS score

The ATS check is a simulated scan, not a real Applicant Tracking System. Treat the match score as an estimate. Real systems vary, and a person still reads your CV.

## Feedback

Found something that doesn't work, or got an interview with it? Open an issue or message me. If it helped you, a ⭐ on the repo would mean a lot.

## Licence

MIT
