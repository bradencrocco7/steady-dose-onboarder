# The Steady Dose Onboarder

A folder that gets a new part-time NAPLEX tutor through their first day at Steady Dose Tutoring, a small one-on-one pharmacy exam tutoring business that runs on a shared workspace. Drop it into Claude and Claude becomes the person who has been there for years: it answers from the folder, sends you to the right person, paces the day, and says so when it doesn't know.

Steady Dose and the team around me are made up, built from the pharmacy tutoring business I actually run. The owner is me, and the teaching methods are mine, so the details are real even where the other names aren't.

## Who this is for

A newly licensed pharmacist starting as a part-time tutor. You may have tutored a little before. You've probably never worked in a workspace like this one, a folder where each part has its own place. This onboarder covers both: the job, and the folder the job runs on.

## How to start

**In a Claude project (claude.ai):**
1. Make a new project.
2. Add every file in this folder to the project's files, including everything in `reference/`. Leave out `extras/`.
3. In the project's instructions, paste: *Follow `identity.md` and `rules.md`. Answer only from `reference/`.*
4. Start a chat and say you're starting today.

**In Claude Code:** open this folder and say the same thing, after telling it to read `identity.md` and `rules.md` first.

## What to ask first

- "It's my first day. What do I do first?"
- "Who do I ask about my pay?"
- "What does `awaiting-send` mean?"
- "How do you teach here?"

## What's in the folder

| File | What it does |
|---|---|
| `identity.md` | who the onboarder is, the business, the role, what's out of scope |
| `rules.md` | how it answers, what it does when the answer isn't here, who it sends you to, how it paces the day |
| `examples.md` | three short exchanges, including one it can't answer |
| `reference/first-day.md` | the day, in order, and what waits until later |
| `reference/who-is-who.md` | the team, and who to ask about what |
| `reference/how-we-teach.md` | the teaching stance, the four methods, how sheets build, how a session runs |
| `reference/the-workspace.md` | what each folder name means, and the one rule about `awaiting-…` folders |
| `reference/policies.md` | packages, homework, the guarantee, consent, what we never say |
| `reference/tools-and-logins.md` | each tool and who sets you up (no passwords, ever) |
| `extras/` | three one-page pictures of ICM in general, for people curious about the method; not part of what the onboarder answers from, and some names differ from this workspace |

## The one thing I wish I'd been told

What all the folder names meant, and what each one held. When I first learned to run my business on a workspace like this, the names were the wall. What finally made it click: the folder is one big prompt cut into pieces, and each folder name tells you which piece it is. That's `reference/the-workspace.md`.

## Credit

The workspace follows ICM (Interpretable Context Methodology) by Jake Van Clief and David McDermott. The teaching methods (calc-CARE, STAT, CASE, MAPP) are Braden Crocco's.
