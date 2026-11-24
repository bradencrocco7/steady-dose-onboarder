# The Steady Dose Onboarder

A folder that takes a new part-time NAPLEX tutor through their first day at Steady Dose Tutoring, a small one-on-one pharmacy exam tutoring business. Point Claude at it and Claude becomes the person who has been there for years: it takes the new tutor through the day part by part, answers from the folder, sends them to the right person, and says so when it doesn't know.

Steady Dose and the team around me are made up, built from the pharmacy tutoring business I actually run. The owner is me, and the teaching methods are mine, so the details are real even where the other names aren't.

## How to start

Point Claude at this folder and say "Hi, it's my first day." The onboarder takes it from there.

`AGENTS.md` is what tells Claude to be the onboarder, and `CLAUDE.md` is one line that loads it. If your setup doesn't pick it up, say "read `AGENTS.md` first".

For a real new hire, it goes in a Claude project: add every file in this folder to the project, paste the text of `AGENTS.md` into the project's instructions, and share the project with them.

## Who it's for

A newly licensed pharmacist starting as a part-time tutor. They may have tutored a little before. They've probably never worked somewhere that runs on one shared folder.

## What the day looks like

Six parts, about three hours, all in the chat and at the new tutor's pace: get set up, how we teach, the workspace, a past session to read, a practice homework to grade, and a wrap-up. The onboarder runs every part, so nobody else has to be online. The practice homework comes with a student's answers, the key, and a senior tutor's grading to compare with.

Braden, Marcus and Priya are in the folder as who to ask for what the onboarder can't answer or decide: pay, a login that won't work, anything going to a real student.

## Things to ask

- "Hi, it's my first day. What do I do?"
- "What's in the workspace, and which parts are mine?"
- "Can we do the practice homework now?"
- "Who do I ask about my pay?"

## What's in the folder

`identity.md`, `rules.md` and `examples.md` make Claude the onboarder. The eight pages in `reference/` are everything it knows. Each of them opens with a line that says its one job.

In the Steady Dose workspace, this folder is `onboarder/`. It sits beside the students' folders and the library of sheets, and `reference/the-workspace.md` has the map.

## The one thing I wish I'd been told

When I started tutoring, I thought one good explanation would work for every student. It doesn't. The principles stay the same, and the explanation has to change for the student in front of you. Nobody told me that on my first day.

That's why `reference/how-we-teach.md` exists. It's the second part of the day, before a new tutor reads a session or grades anything, and it opens with this lesson. The rest of the page is what stays the same: the stance, the four methods, how the sheets build, how a session runs. So every new tutor is told on their first day what I had to work out for myself.

## Credit

The folder follows ICM (Interpretable Context Methodology) by Jake Van Clief and David McDermott. The teaching methods (calc-CARE, STAT, CASE, MAPP) are Braden Crocco's.
