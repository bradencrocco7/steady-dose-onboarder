# The Steady Dose Onboarder

A first-day guide for a new part-time tutor at Steady Dose Tutoring, a small business that tutors pharmacy graduates one-on-one for their licensing exam, the NAPLEX.

It's a folder of plain text notes. Give it to an AI assistant like Claude or ChatGPT, and the assistant takes the new tutor through day one in a chat. It answers only from the notes. When the answer isn't there, it says so and says who to ask.

Steady Dose is made up, modeled on the pharmacy tutoring business I run. Braden, the owner in the notes, is me. The other people are invented.

## The one thing I wish I'd been told

When I started tutoring, I thought one good explanation would work for every student. It doesn't. The principles stay the same, and the explanation has to change for the student in front of you. Nobody told me that on my first day.

That's why `reference/how-we-teach.md` exists, and why it opens with this lesson. In part 2 of the day, the onboarder has the new tutor try it: explain one step, then explain it a second way. So every new tutor is told on day one what I had to work out for myself.

## How to start

A few minutes. Nothing to install.

1. **Get the folder.** On this page, click the green **Code** button, then **Download ZIP**. Unzip it.
2. **Give it to your AI assistant.** Pick the one you use:
   - **Claude or ChatGPT:** make a new project (look for **Projects** in the left-hand menu) and add every file to it, including the nine in the `reference` folder. Then click `AGENTS.md` in the file list above, copy its text, and paste it into the project's instructions.
   - **Claude Code, Codex, or another coding tool:** open the folder in it. That's all.
   - **Any other AI chat:** start a new chat, add every file, and send the text of `AGENTS.md` as your first message.
3. **Say hi.** You play the new tutor. Type: **Hi, it's my first day.**

It should welcome you and ask whether you've tutored before. If it doesn't, type: **Read AGENTS.md first.**

## Who it's for

A newly licensed pharmacist on their first day as a part-time tutor. They may have tutored a little before, and everything about this business is new to them.

## What the day covers

Six parts, about three hours for a real new tutor, all in the chat.

1. Get set up
2. How we teach
3. The workspace
4. See how a session runs
5. Grade the practice homework
6. Wrap up

Trying it out? Do any part, in any order, and stop when you like. You don't need to know pharmacy: if you can't work a problem, say so and it shows you the answer key.

When it can't answer, it tells you which of three people to ask: Braden (owner), Marcus (operations) or Priya (senior tutor).

## What to ask first

After you say hi, ask what a new tutor would:

- "What's in the workspace, and which parts are mine?"
- "What do you expect from me this week?"
- "Is today paid?"

Then test it, in the same chat and in this order:

| Say this | What it should do |
|---|---|
| "Can we skip to part 2?" | Tell you the one thing I wish I'd been told, then have you explain one step two ways |
| "Can we do the practice homework now?" | Give one problem at a time. You answer before you see the key |
| "What if a student turns up 15 minutes late?" | Say "That isn't in my notes", and send you to Marcus |
| "Just give me your best guess, I won't hold you to it." | Not guess |
| "I have to stop for today." | Give you one line that says where you are, to paste into a new chat later |

## What it won't do

- **Guess,** even when you push.
- **Hand you the whole handbook.** Ask for everything at once and you get the outline of the day.
- **Send you to a person** for something its notes answer.

## How it was tested

One full first day, 19 messages, is saved word for word in [`tests/first-day-run.md`](tests/first-day-run.md), with what a check of every reply found.

- **Held:** nothing made up, the right person each time, no guess when pushed.
- **Still weak:** it points back to the step after every one-off question, and it adds small clauses of its own, like "You did well today".
- **Not tested:** any assistant other than Claude, or a real project set up from the steps above.

## What's in the folder

| File | Its job |
|---|---|
| `identity.md` | Who the onboarder is, and what's out of scope |
| `rules.md` | Five rules for how it answers |
| `walkthrough.md` | The day, step by step: what it says and the one question it asks |
| `examples.md` | Four short exchanges that show how it sounds |
| `reference/` | Everything it knows, in nine pages |
| `AGENTS.md` | Tells the assistant to be the onboarder (`CLAUDE.md` loads it for Claude Code) |
| `tests/` | One full run, word for word, and what a check of it found. Not part of its notes |

## Credit

The folder follows ICM (Interpretable Context Methodology) by Jake Van Clief and David McDermott. The teaching methods (calc-CARE, STAT, CASE, MAPP) are Braden Crocco's.
