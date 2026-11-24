# The workspace

One job: what the Steady Dose workspace is, what each folder name means, and which parts a new tutor touches. Braden walks through this page with you in the late morning, after how we teach.

## The one sentence

**The workspace is one big prompt, cut into pieces, and each folder name tells you which piece it is.**

If you've ever typed a long prompt into ChatGPT ("You are... here is what we're working on... follow these rules... here's an example... do these steps... save it as..."), you already know every part of this folder. Here, each part lives in its own place, written once, so nobody has to type it again and Claude never has to guess.

The workspace is built on ICM (Interpretable Context Methodology), made by Jake Van Clief and David McDermott. You don't need to know ICM to work here; this page is all you need on day one.

## What each name means

| A normal prompt says... | Here it lives in | What it holds at Steady Dose | You, on day one |
|---|---|---|---|
| "You are..." (who Claude is, the house rules) | `AGENTS.md` | who the business is, the rules every job follows, where to go next | read it once |
| "Go here for this kind of work" | `CONTEXT.md` (one in most folders) | a signpost: "if the work is X, go to folder Y" | follow them |
| "Here's where things stand today" | `STATUS.md` | the whiteboard: what's waiting for Braden, which students have gone quiet; rebuilt by a script, never edited by hand | glance at it |
| "Follow these rules" | `_config/` | the rulebook: packages and prices, what we never say, the voice for student emails | read, never change |
| "Here's an example to copy" | `_templates/` | blanks: a new student's folder, a session record | Priya shows you |
| "Do step 1, then step 2..." | `operations/tutoring/CONTEXT.md` | the session loop, steps 1 to 8: grade, prep, the session, the record, the next homework | read it with Priya |
| "Only look at this student" | the folder you're in | `operations/students/<first-last>/` holds one student; working in it means you can't mix students up | where you work |
| "Save the result here" | each student's subfolders, and the `awaiting-…` trays | the grading goes in the student's `grading/`; anything for a student waits in `operations/email/awaiting-send/` | drop it in, never take it out |

One thing that tripped Braden up: **if you read about ICM online, some people use `CONTEXT.md` as the whiteboard. Here it is always the signpost, and `STATUS.md` is the whiteboard.** Same idea, different file.

## The folders, top to bottom

```
steady-dose/
├── AGENTS.md            who we are, the house rules
├── CONTEXT.md           the signpost to each department
├── STATUS.md            the whiteboard (made by a script)
├── _config/             the rulebook
├── _templates/          the blanks
├── operations/          everything after a student pays (your home)
│   ├── tutoring/          the session loop, steps 1 to 8
│   ├── students/          one folder per student
│   │   └── <first-last>/
│   │       ├── sessions/            run sheets, session records
│   │       ├── homework-sent/       what we sent, and its key
│   │       ├── homework-returned/   what they sent back
│   │       ├── grading/             our grading of it
│   │       ├── emails/              every email, once sent
│   │       └── paperwork/           recording consent
│   ├── curriculum/        the library: the method sheets, every worksheet and its key
│   ├── studio/            where new sheets are made (Braden only)
│   └── email/
│       ├── awaiting-send/     drafts waiting for Braden
│       ├── approved-to-send/  Braden moved it here: it goes out
│       └── discarded/         Braden said no
├── sales/               leads and the free consult (Braden)
├── marketing/           posts and the website (Braden)
└── finance/             payments and refunds (Marcus)
```

## The one rule about `awaiting-…` folders

Anything that waits for Braden sits in a folder whose name starts with `awaiting-`. **His moving the file out is the approval.** You may put a draft in. You never move one out, and neither does Claude. If something has been waiting a long time, tell Braden; don't move it to help.

## When someone tells you something new

Everyone on the team learns things that should be kept. Where it goes depends on what kind of thing it is:

| It's... | For example | Where it goes | Who puts it there |
|---|---|---|---|
| a fact for today | "Priya is out Thursday" | `STATUS.md` or a message | Marcus or Braden |
| a rule from now on | "homework is due 12 hours before, not 24" | `_config/` | Braden |
| a new check in the loop | "check the student's exam date before the prep" | a step in `operations/tutoring/CONTEXT.md` | Braden |
| a whole new kind of work | "we're starting group sessions" | a new folder of its own | Braden |

On day one and for a while after, your part is the same every time: **tell Braden.** You don't change the rulebook or the steps yourself, even when you're sure.

## If you want the pictures

Braden drew three one-page sheets of the ICM idea when he was learning it himself. Ask him for them. They show ICM in general, so a few names differ from ours; for Steady Dose, this page is the one to go by.
