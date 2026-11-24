# The workspace

One job: where things are in the Steady Dose workspace, which parts a new tutor touches, and the one rule about `awaiting-…` folders. Braden walks through this page with you in the late morning, after how we teach.

The workspace is the shared folder the business runs on. You open it in Obsidian (`tools-and-logins.md` has the steps). Every student, every sheet and every step lives in it, each in its own place. It's built on ICM (Interpretable Context Methodology, by Jake Van Clief and David McDermott), but you don't need to know ICM to work here.

## The map

```
steady-dose/
├── AGENTS.md            who we are and the house rules; read it once
├── CONTEXT.md           signposts: "for this kind of work, go to this folder"
├── STATUS.md            the whiteboard: what's waiting, which students have gone quiet
├── _config/             the rulebook: prices, what we never say, the voice for emails
├── _templates/          blanks: a new student's folder, a session record
├── operations/          everything after a student pays (your home)
│   ├── tutoring/          the session loop, steps 1 to 8; read it with Priya
│   ├── students/          one folder per student
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

You read `AGENTS.md`, `CONTEXT.md`, `STATUS.md` and `_config/`, but you never change them. Nobody edits `STATUS.md` by hand; a script rebuilds it.

## A student's folder

Each student has a folder at `operations/students/<first-last>/`. Working inside one student's folder means you can't mix students up. It has six subfolders:

| Folder | Holds |
|---|---|
| `sessions/` | run sheets and session records |
| `homework-sent/` | the homework we sent, with its key kept beside it for grading; the key itself is never sent |
| `homework-returned/` | what the student sent back |
| `grading/` | our grading of it; on day one, your grading of the practice homework goes here |
| `emails/` | every email to and from the student; ours are filed once they're sent |
| `paperwork/` | the recording consent form |

The practice student's folder is `operations/students/practice-student/`. It's set out like any real student's: its last run sheet and session record are in its `sessions/` (also on `sample-session.md`), the homework you grade on day one is in its `homework-returned/`, the key is in its `homework-sent/`, and your grading goes in its `grading/` (the homework, the key and how to grade are on `practice-homework.md`).

## The one rule about `awaiting-…` folders

Anything that waits for Braden sits in a folder whose name starts with `awaiting-`. **His moving the file out is the approval.** You may put a draft in. You never move one out, and neither does Claude. If something has been waiting a long time, tell Braden; don't move it to help.

## When something seems wrong or missing

A rule that looks wrong, a step that's missing, a key you think is off (tell Priya about that one too), or something new you've been told that should be kept: **tell Braden.** You don't change the rulebook, the steps or a sheet yourself, even when you're sure.
