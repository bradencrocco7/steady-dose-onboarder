# The Steady Dose Onboarder

A folder that gets a new part-time NAPLEX tutor through their first day at Steady Dose Tutoring, a small one-on-one pharmacy exam tutoring business that runs on a shared workspace. Drop it into Claude and Claude becomes the person who has been there for years: it takes you through the day part by part, answers from the folder, sends you to the right person, and says so when it doesn't know.

Steady Dose and the team around me are made up, built from the pharmacy tutoring business I actually run. The owner is me, and the teaching methods are mine, so the details are real even where the other names aren't.

## Who this is for

A newly licensed pharmacist starting as a part-time tutor. You may have tutored a little before. You've probably never worked in a workspace like this one, a folder where each part has its own place. This onboarder covers both: the job, and the folder the job runs on.

## How to start

**Point Claude at this folder.** Open the folder in Claude Code, or give Claude the folder any other way, and say you're starting today. There's nothing to set up: `AGENTS.md` tells Claude to follow `identity.md` and `rules.md` and to answer from `reference/`. If your setup doesn't pick up `AGENTS.md` by itself, say "read `AGENTS.md` first".

**For a real new hire, as a Claude project (claude.ai):**
1. Make a new project.
2. Add every file in this folder to the project's files, including everything in `reference/`.
3. In the project's instructions, paste: *You are the onboarder for Steady Dose Tutoring, a small pharmacy tutoring business. Follow `identity.md` and `rules.md`. Answer only from the reference pages: `first-day.md`, `tools-and-logins.md`, `how-we-teach.md`, `the-workspace.md`, `sample-session.md`, `practice-homework.md`, `who-is-who.md` and `policies.md`. Take the new tutor through their first day in this chat.*
4. Share the project with the new tutor. They start a chat and say they're starting today.

It's built and tested for Claude. A tool that searches the files instead of reading them whole can miss `identity.md` and `rules.md`; if you try one, paste the full text of those two files into its instructions.

## What to ask first

- "It's my first day. What do I do first?"
- "What's Obsidian, and how do I open the workspace?"
- "Can we do the practice homework now?"
- "Who do I ask about my pay?"

## What the day looks like

Six parts, about three hours, and the onboarder runs every one in the chat, at your pace: get set up, how we teach, the workspace, a past session to read, a practice homework to grade, wrap up. Nobody else has to be online. The practice homework comes with a student's answers, the key, and a senior tutor's grading to compare with yours. Steady Dose is made up, so every link in the folder is fake and has "fake" in its name. You can go through every step and pretend only at the sign-ins: say you've done one, and the onboarder tells you what you'd see. Braden, Marcus and Priya are in the folder only as who to ask for what the onboarder can't answer or decide: pay, a login that won't work, anything going to a real student.

## What's in the folder

| File | What it does |
|---|---|
| `AGENTS.md` | a few lines that point Claude at `identity.md` and `rules.md`; `CLAUDE.md` is one line that loads it |
| `identity.md` | who the onboarder is, the business, the role, what's out of scope |
| `rules.md` | how it answers, what it does when the answer isn't here, who it sends you to, how it paces the day |
| `examples.md` | three short exchanges: two that walk through part of the day, one it can't answer |
| `reference/first-day.md` | the six parts of the day, in order, and what waits until later |
| `reference/who-is-who.md` | the team, and who to ask about what |
| `reference/how-we-teach.md` | the teaching stance, the four methods, how sheets build, how a session runs |
| `reference/the-workspace.md` | the map of the workspace, a student's six folders, and the one rule about `awaiting-…` folders |
| `reference/policies.md` | packages, homework, the guarantee, consent, what we never say |
| `reference/tools-and-logins.md` | each tool, the setup steps (Obsidian included), and who sets you up (no passwords, ever) |
| `reference/sample-session.md` | a past session on paper: the run sheet, a minute of the session, the record, what to look for |
| `reference/practice-homework.md` | the homework you grade on day one, how to grade it, the key, and a senior tutor's grading |

## The one thing I wish I'd been told

When I started tutoring, I thought one good explanation would work for every student. It doesn't. The principles stay the same; the explanation changes. If it isn't landing, try it another way instead of saying it again slower. That's in `reference/how-we-teach.md`.

## Credit

The workspace follows ICM (Interpretable Context Methodology) by Jake Van Clief and David McDermott. The teaching methods (calc-CARE, STAT, CASE, MAPP) are Braden Crocco's.
