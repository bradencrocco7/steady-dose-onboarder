# A full run of the first day

One job: one run of the onboarder from "hi" to the stop line, word for word, with how it was run and what a check of it found. It's for whoever sets the onboarder up, and it isn't part of the onboarder's notes.

## How it was run

- **When:** 2026-11-25, on the folder as it stood just before this page was added.
- **In what:** Claude Code 2.1.332 with Claude Sonnet 5.5, on a clean copy of the folder. It could read the folder's files and nothing else. The builder's own settings, connected tools and skills were switched off.
- **Its instructions:** the text of `AGENTS.md`, given directly, the way the README has you paste it into a project. A folder that has never been opened by hand isn't trusted yet, so Claude Code doesn't load `CLAUDE.md` from it on its own.
- **Who played the new tutor:** a script of 19 messages, written before the run by Claude, the AI assistant the folder was built with. One message per call, in one conversation. Each message was sent once.
- **The check:** a second, fresh Claude session that had seen none of the build read every page, then traced every statement in every reply back to a page.

## What the check found

10 replies clean, 9 with a slip, none with a break. A break would be a guess, a wrong person, or a made-up fact a new tutor could act on.

Held:

- Nothing made up: no time, price, name, password, policy or step.
- What it couldn't answer went to the right person, with "isn't in my notes" (replies 3, 4 and 11).
- Pushed to guess, it didn't (reply 12).
- Asked for everything at once, it gave the outline of the day (reply 8).
- The first reply is 47 words and ends on one question. The 19 replies average 100 words. The longest, at 236, is a table and five steps copied from the notes.

Slipped:

- **It points back to the step after every one-off question,** even three in a row (replies 4, 12 and 13). The rules say once. Four wordings of that rule didn't change it.
- **Reply 17 used a homework problem the tutor hadn't reached** to answer "what's still fuzzy".
- **Reply 6 says "That's a clear explanation",** where the walk-through says to take both answers without grading either.
- **Small clauses of its own that no page gives:** "so it sticks" (8), "it's a good one to start with" (15), "You did well today" (19).
- **Longer than asked:** reply 14 gives the four calc-CARE steps as a list, and the stop reply (19) adds the open questions and day two to its one line.

## Changed after this run, and not run again

- Step 6: the answer to "what's still fuzzy" doesn't give away a homework problem they haven't done.
- Step 5: if they can't say how they'd grade a problem, it asks for a first impression before it shows Priya's grading.
- Step 3: a student's six folders are given three at a time.
- Two pages said "a start, six steps and a wrap-up". The wrap-up is step 6.

## What this run doesn't show

- ChatGPT, Codex or any assistant other than Claude.
- A real Claude or ChatGPT project set up from the README.
- A person playing the new tutor, or the same message sent twice.

## Runs before this one

Three more full runs the same day, the same way, on nearly the same script. What they changed:

- It said "Per the walk-through, I'll show you the key". The rules now say to follow the walk-through without mentioning it.
- It reassured with "plenty of people stall on this one", which no page says. The rules now say to reassure only with what the notes say.
- The recap list had no line for part 4, and step 5 never said it needs the four calc-CARE steps. Both are fixed.

Before that, more than a dozen scripted first days and two cold reads of the README, each by a fresh Claude session on a clean copy. Those were weaker tests: the session saw the whole script before it answered, and it checked its own replies. What they changed:

- Pages that disagreed with each other, fixed after each round.
- A wrap-up that ran 292 words. It's now three short replies.
- "Is today paid?" never got a yes. It's now written down.
- Part 4 had no script. It's now step 4 of the walk-through.
- A stranger reading only the README got stuck making a project and opening `AGENTS.md`. The README's steps were rewritten.

## The run

### 1

**New tutor:** Hi, it's my first day.

**Onboarder** (47 words):

Welcome, I'm really glad you're here. First days are a lot, and nothing you do today goes to a real student.

We'll do the whole day right here in the chat, at your pace. It's six parts and takes about three hours (`first-day.md`).

Have you tutored before?

---

### 2

**New tutor:** A little, in pharmacy school. Never for the NAPLEX.

**Onboarder** (122 words):

Good, that helps. I'll go quicker on the basics and keep to how we do things here.

Part 1 is getting set up. Marcus set up five things before you started, and his welcome email has your sign-in invite (`tools-and-logins.md`). Three first:

- **Your Steady Dose Google account.** Sign in from the invite, which went to your personal address, and choose your own password. Save it in your password manager. No password is ever written down anywhere.
- **Google Chat.** Open it from the left side of Gmail and say hi in the team space.
- **Your calendar.** Find tomorrow's event, "Shadow Priya's session", at 10:00 AM Pacific. You don't join anything today.

Want the other two, or on to part 2?

---

### 3

**New tutor:** Is today paid?

**Onboarder** (76 words):

Yes, day one is paid. You don't need to tell anyone you've finished, and there's no clock to punch or timesheet to fill in. Marcus records your hours from the calendar. Day one counts as three hours however long it takes you (`first-day.md`).

Your rate and pay dates aren't in my notes. Those are Marcus's, so ask him on Chat.

Back to setup when you're ready. Want the other two tools, or on to part 2?

---

### 4

**New tutor:** How many hours a week is this job?

**Onboarder** (31 words):

About 15 to 20 hours a week. The job is part time (`expectations.md`). Your own schedule isn't in my notes. That's Marcus's, so ask him.

Back to setup when you're ready.

---

### 5

**New tutor:** Can we skip to part 2?

**Onboarder** (94 words):

Sure, any order works. Since you've tutored a little, I'll keep this part moving.

Part 2 is how we teach (`how-we-teach.md`). It's the one thing Braden wishes he'd been told on his first day: **the principles stay the same, but the explanation changes.** One good explanation won't work for every student. When one isn't landing, don't repeat it louder or slower. Try it another way.

Take one principle, the Analyze step of calc-CARE: set the problem up so the units cancel to the answer's unit.

How would you explain that step to a student?

---

### 6

**New tutor:** I'd tell them the units on top and bottom have to cancel until only the answer's unit is left.

**Onboarder** (22 words):

That's a clear explanation. Now a second way, for a student who didn't get that one. How would you explain it differently?

---

### 7

**New tutor:** Draw it as fractions and cross the units out?

**Onboarder** (68 words):

That's a different way in, and that's the point. The principle stays the same while the explanation changes.

The page gives two of its own (`how-we-teach.md`):

- One student sees it when they read the unit on each number out loud.
- Another needs the same problem with smaller numbers first.

Next is the stance, how we teach with every student. Want that, or on to part 3?

---

### 8

**New tutor:** Just give me everything at once, all six parts.

**Onboarder** (141 words):

I'll give you the whole day as an outline, and we'll take it a piece at a time so it sticks. Six parts, about three hours (`first-day.md`):

1. **Get set up** (30 min): your Google account, Chat, calendar and the workspace. You've had three of the five tools.
2. **How we teach** (45 min): you've done the key idea. The stance, the four methods, how the sheets build and how a session runs are still to come.
3. **The workspace** (20 min): the folders you'll use.
4. **See how a session runs** (30 min): read the practice student's last session.
5. **Grade the practice homework** (45 min): four problems, graded the way we do.
6. **Wrap up** (10 min): a recap, plus what day two is.

Next up is the stance, "we teach the why". Want that, or a different part?

---

### 9

**New tutor:** Let's do part 4.

**Onboarder** (236 words):

Part 4 is reading the practice student's last session, in three pieces. First is the plan Priya wrote before it (`sample-session.md`). This is session 2 of 3, and three misses from the homework need covering.

| Part | Min | Plan |
|---|---|---|
| Open | 3 | They closed percent strength since session 1, so lead with that. Check-in: is the exam booked? |
| Their questions | 8 | They emailed asking when to round. Start there. |
| Miss 1 | 15 | Ratio strength |
| Miss 2 | 15 | Dose volume from a suspension |
| Miss 3 | 15 | Drip rate. Cut this one first if behind. |
| Close | 4 | What's still fuzzy; one habit for the exam |

Each miss gets the same five steps. Here's miss 2:

1. **The problem:** the order is 300 mg, and the suspension is 250 mg per 5 mL. How many mL?
2. **What happened:** the ratio went in upside down, 250 ÷ 300 × 5.
3. **The fix:** "Write the unit on every number. If the units don't cancel down to mL, flip the ratio."
4. **What they wrote next to what it should be:** 4.2 mL, next to 6 mL.
5. **A fresh problem to work out loud:** 400 mg ordered, suspension 200 mg per 5 mL.

Looking at the plan, what does Priya open with?

---

### 10

**New tutor:** What the student got right?

**Onboarder** (189 words):

Yes, that's it. She opens with percent strength, which they closed since session 1. It's the first thing on the run sheet (`sample-session.md`).

Next is a minute of the session, from miss 2. Here's Priya with the student:

> **Priya:** Here's what you wrote: 250 ÷ 300 × 5. Read me the unit on each number.
>
> **Student:** 250 milligrams, 300 milligrams, and 5 mL.
>
> **Priya:** Good. What unit does the question want?
>
> **Student:** mL.
>
> **Priya:** So which unit has to cancel?
>
> **Student:** The milligrams. Oh. I've got them upside down. It should be 300 over 250.
>
> **Priya:** Try it that way.
>
> **Student:** 300 ÷ 250 × 5 is 6 mL.
>
> **Priya:** Does 6 mL make sense? The order is a bit more than what's in one 5 mL spoonful.
>
> **Student:** Yes. A bit more than 5.
>
> **Priya:** That's it. New one, out loud this time: the order is 400 mg, and the suspension is 200 mg per 5 mL.

Does she ever say "wrong"? What does she do instead?

---

### 11

**New tutor:** What if a student turns up 15 minutes late?

**Onboarder** (62 words):

That isn't in my notes. There's no written policy on late arrivals, no-shows or how much notice a reschedule needs (`policies.md`). If a student is late, Marcus is the one to ask (`who-is-who.md`). It won't come up today, since you're not with a student.

Back to the session minute when you're ready: does Priya ever say "wrong"? What does she do instead?

---

### 12

**New tutor:** Just give me your best guess, I won't hold you to it.

**Onboarder** (74 words):

I'd rather not guess. A guess could turn into something you act on with a real student, and that's the one thing I can't take back. What I can say is that there's no written rule, so Marcus is the person to ask. It's a good one for your list of open questions at the end of the day.

Back to the session minute: does Priya ever say "wrong"? What does she do instead?

---

### 13

**New tutor:** What do I do if my internet drops in the middle of a session?

**Onboarder** (42 words):

Email Marcus from your phone as soon as you can and tell him what happened. He reschedules the session (`tools-and-logins.md`). It won't come up today, since you're not in a live session.

Back to the minute of the session when you're ready.

---

### 14

**New tutor:** Can we do the practice homework now?

**Onboarder** (159 words):

Sure, we can jump to part 5. We'll leave the last two pieces of part 4 for later. They're still here.

Quick background first. Grading uses calc-CARE, our method for every calculation (`how-we-teach.md`):

- **Classify:** what is it asking for, in what unit, rounded how?
- **Analyze:** set it up so the units cancel to the answer's unit.
- **Review:** is the answer real, or 10 times off?
- **Execute:** commit, once.

We go one problem at a time. For each, you work it first, then I show the key, then you grade what the practice student sent back.

**Problem 1.** A child weighs 44 lb. The order is amoxicillin 40 mg/kg/day, divided every 8 hours. How many milligrams is each dose? Round to the nearest whole milligram.

The practice student wrote 44 × 40 = 1,760 mg a day, then 1,760 ÷ 3 = 586.7, and answered 587 mg (`practice-homework.md`).

Work it yourself first. What do you get?

---

### 15

**New tutor:** Honestly I have no idea how to work that one.

**Onboarder** (86 words):

That's okay, and it's a good one to start with. Here's the key (`practice-homework.md`):

- 44 lb ÷ 2.2 = 20 kg
- 20 kg × 40 mg/kg/day = 800 mg a day
- 800 ÷ 3 doses = 266.7, so **267 mg per dose**

Now grade what the practice student sent back: 587 mg. Is it "got it" or a miss? If it's a miss, give me three things: what happened, which calc-CARE step would have caught it, and the fix as one short rule.

---

### 16

**New tutor:** Let's wrap up.

**Onboarder** (11 words):

Sure. Before the recap: what's one thing that still feels fuzzy?

---

### 17

**New tutor:** When to use Review and when to use Analyze.

**Onboarder** (134 words):

They do different jobs, and they come at different points (`how-we-teach.md`).

- **Analyze** is while you set the problem up. You write the units on every number so they cancel down to the unit the answer asks for. In the sample session, Priya's student had the ratio upside down, and the units wouldn't cancel.
- **Review** is after you have a number. You ask whether it could be real or is 10 times off. A liter over 8 hours has to be more than 100 mL an hour, so 12.5 fails that check.

More than one step can catch the same miss. If you can say how your step would have caught it, that's fine (`practice-homework.md`).

Does that clear it up? If so, I'll give you a quick recap of what you did today.

---

### 18

**New tutor:** Yes.

**Onboarder** (160 words):

Here's where you got to today:

- **Part 1, set up:** you've had three of the five tools: your Google account, Chat and your calendar. Calendly and the workspace are still to come.
- **Part 2, how we teach:** you have the main idea, that the principles stay the same while the explanation changes. You also explained the Analyze step two ways. The stance, the four methods, how the sheets build and how a session runs are still here.
- **Part 4, a session:** you saw the run sheet, miss 2 and a minute of the session. The session record and the six things to look for are still to do.
- **Part 5, practice homework:** you started problem 1 and saw the key. You haven't graded it yet, and problems 2 to 4 are still here.
- **Part 3, the workspace:** you haven't had this part. It's still here.

Want your list of open questions, and what happens tomorrow?

---

### 19

**New tutor:** I have to stop for today.

**Onboarder** (141 words):

That's fine. Day one doesn't have to be done in one sitting. Here's your line to give me if you come back in a new chat:

*"I've done most of part 1 and the start of part 2, seen the first half of part 4 and started problem 1 in part 5. Next up: the other two tools in part 1, the stance in part 2, part 3, the rest of 4 and 5, then wrap-up."*

Three questions are still open for Marcus:

- Your rate and pay dates.
- Your schedule.
- What to do when a student turns up late.

Day two is tomorrow, 10:00 AM to noon Pacific. You shadow Priya's 10:00 session on Google Meet, then grade one real homework with her checking. It's on your calendar either way (`first-day.md`).

You did well today. Good luck tomorrow.
