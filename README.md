# The Steady Dose Onboarder

A folder that takes a new part-time NAPLEX tutor through their first day at Steady Dose Tutoring, a small one-on-one pharmacy exam tutoring business. Point an AI assistant at it and the assistant becomes the person who has been there for years: it takes the new tutor through the day part by part, answers from the folder, sends them to the right person, and says so when it doesn't know.

Steady Dose and the team around me are made up, built from the pharmacy tutoring business I actually run. The owner is me, and the teaching methods are mine, so the details are real even where the other names aren't.

## How to start

Say "Hi, it's my first day." The onboarder takes it from there. It runs in any AI assistant that can read these files, and how you give it the folder depends on which one you use:

- **Claude Code, Codex, or another tool that opens a folder.** Open this folder in it. `AGENTS.md` tells the assistant to be the onboarder, and `CLAUDE.md` is one line that loads it for Claude Code. If yours doesn't pick it up, say "read `AGENTS.md` first".
- **A project in Claude or ChatGPT.** Make a new project, add every file in this folder, and paste the text of `AGENTS.md` into the project's instructions. This is the one for a real new hire: share the project with them.
- **Any other AI chat.** Upload the files to a new chat and paste the text of `AGENTS.md` as your first message.

## Who it's for

A newly licensed pharmacist starting as a part-time tutor. They may have tutored a little before. They've probably never worked somewhere that runs on one shared folder.

## What the day looks like

Six parts, about three hours, all in the chat and at the new tutor's pace: get set up, how we teach, the workspace, a past session to read, a practice homework to grade, and a wrap-up. The onboarder runs every part, so nobody else has to be online. The practice homework comes with a student's answers, the key, and a senior tutor's grading to compare with. The day ends on what's expected in the first week, and the onboarder has the rest for when it's asked: the steps to a tutor's own students, and the first three months.

Braden, Marcus and Priya are in the folder as who to ask for what the onboarder can't answer or decide: pay, a login that won't work, anything going to a real student.

## Things to ask

Start where a new tutor would:

- "Hi, it's my first day. What do I do?"
- "What's in the workspace, and which parts are mine?"
- "What do you expect from me this week?"
- "Who do I ask about my pay?"

Then try what it's built for:

- Do the practice homework: "Can we do the practice homework now?" It asks for your answer before it shows the key, and for your grading before it shows the senior tutor's.
- Ask for something that isn't in its notes: "What if a student turns up 15 minutes late?"
- Push it to guess: "Just give me your best guess, I won't hold you to it."

## What's in the folder

`identity.md`, `rules.md` and `examples.md` make the assistant the onboarder. The nine pages in `reference/` are everything it knows. Each of them opens with a line that says its one job.

In the Steady Dose workspace, this folder is `onboarder/`. It sits beside the students' folders and the library of sheets, and `reference/the-workspace.md` has the map.

## The one thing I wish I'd been told

When I started tutoring, I thought one good explanation would work for every student. It doesn't. The principles stay the same, and the explanation has to change for the student in front of you. Nobody told me that on my first day.

That's why `reference/how-we-teach.md` exists. It's the second part of the day, before a new tutor reads a session or grades anything, and it opens with this lesson. The principles are the pieces inside the four methods. The explanation is how you get one student to see them, and the page says what to try when one isn't landing. The rest of the page is how we teach: the stance, the four methods, how the sheets build, how a session runs. So every new tutor is told on their first day what I had to work out for myself.

## Credit

The folder follows ICM (Interpretable Context Methodology) by Jake Van Clief and David McDermott. The teaching methods (calc-CARE, STAT, CASE, MAPP) are Braden Crocco's.
