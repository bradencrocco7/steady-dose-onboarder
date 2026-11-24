# The practice homework

One job: the homework a new tutor grades on day one, how to grade it, and Priya's grading of the same homework to compare with. This is part 5 of your first day.

The practice student is made up, so nothing here can reach a real student. In the workspace it all sits in `students/practice-student/`: the homework and its key in `homework-sent/`, and what the student sent back in `homework-returned/`. Everything is also on this page, so you do the whole thing right here in the chat.

## The homework: Calculations practice 1

1. A child weighs 44 lb. The order is amoxicillin 40 mg/kg/day, divided every 8 hours. How many milligrams is each dose? Round to the nearest whole milligram.
2. An order reads: 1,000 mL of normal saline over 8 hours. What is the rate in mL/hr?
3. How many grams of dextrose are in 500 mL of D5W (dextrose 5% in water)?
4. A patient weighing 70 kg is to receive heparin at 18 units/kg/hr. The bag holds 25,000 units in 250 mL. What is the rate in mL/hr? Round to the nearest tenth.

## What the practice student sent back

| Problem | Their work | Their answer |
|---|---|---|
| 1 | 44 × 40 = 1,760 mg a day; 1,760 ÷ 3 = 586.7 | 587 mg |
| 2 | 1,000 mL ÷ 8 hr | 12.5 mL/hr |
| 3 | 5 g in 100 mL, so 5 × 5 | 25 g |
| 4 | 18 × 70 | 1,260 |

## How to grade it

Take one problem at a time.

1. Work the problem yourself first, with calc-CARE (`how-we-teach.md`), before you look at the key.
2. Check your answer against the key. If they disagree, work it once more. A key that still looks wrong goes to Braden, and you tell Priya too; you never change one yourself.
3. Put the student's work and answer next to the key.
4. If they match, write "got it".
5. If it's a miss, write three things:
   - what happened: where each number in the question went
   - which calc-CARE step would have caught it
   - the fix, as one short rule the student can keep
6. At the end, list the gaps to carry into the next session.

There's no score and no percentage, and you never write "wrong". The grading is for the tutor who runs the next session: it tells them what to spend the hour on.

## The key

Tutors only. The key is never sent to a student.

| Problem | Answer | How |
|---|---|---|
| 1 | 267 mg per dose | 44 lb ÷ 2.2 = 20 kg; 20 kg × 40 mg/kg/day = 800 mg a day; 800 ÷ 3 doses = 266.7 |
| 2 | 125 mL/hr | 1,000 mL ÷ 8 hr |
| 3 | 25 g | 5 g per 100 mL × 500 mL |
| 4 | 12.6 mL/hr | 18 units/kg/hr × 70 kg = 1,260 units/hr; the bag is 25,000 units ÷ 250 mL = 100 units/mL; 1,260 ÷ 100 |

## Priya's grading, to compare with yours

Read this only after you've written your own.

**Problem 1: a miss.**
- What happened: the 44 went in as kilograms. It's pounds.
- The step that catches it: Analyze. Written with its units, lb doesn't cancel against mg/kg.
- The fix: "Change the weight to kg before you do anything else."

**Problem 2: a miss.**
- What happened: the setup is right, and the answer is ten times too small.
- The step that catches it: Review. A liter over 8 hours has to be more than 100 mL an hour.
- The fix: "Before you commit, ask whether the number could be real."

**Problem 3: got it.**

**Problem 4: a miss.**
- What happened: 1,260 is the dose in units per hour. The question asks for mL/hr, so the bag's strength was never used.
- The step that catches it: Classify. What is it asking for, and in what unit?
- The fix: "Write the unit the question asks for at the top, and don't stop until your answer is in it."

**Gaps to carry into the next session:** changing lb to kg; checking the size of an answer; finishing in the unit the question asks for.

## When you've compared

If your grading and Priya's differ, that's what this part is for. The onboarder shows you the two side by side.

More than one calc-CARE step can catch the same miss. If you named a different step from Priya's and can say how it would have caught the miss, your grading is fine. What has to agree is the answer on the key and what happened.

If you still think yours is right and hers isn't, that's a grading question for Priya (`who-is-who.md`). There's nothing to save today; gradings of real homework go in the student's `grading/` folder, from day two.
