---
name: goal-achievement
description: "Work through a goal with the method from Ken Watanabe's Problem Solving 101: a clear goal and the real reason behind it → measure the gap between where you are and where you want to be → grow a logic tree of ways to close the gap → pick the strongest hypothesis → test it → a dated plan and the first action. Use when the user sets a new goal or is stuck on an old one: 'I want to', 'how do I get to', 'set a goal', 'I'm not moving toward', 'stuck on my goal', 'what exactly should I do to reach'. Not for choosing between options (decision-maker) or fixing something that broke (problem-solving)."
---

# Goal achievement

Method: Ken Watanabe, *Problem Solving 101*, the goal-setting steps. The point of all of it:

**Result = quality of the plan × quality of execution.** A zero in either one gives zero. A beautiful plan you never execute and hard work on the wrong plan are equally useless.

This is an interview. Ask one block at a time and wait for the answer. Be direct, no motivational speeches, no praise for the obvious. The user does the thinking: you hold the method, ask the questions and do the math.

---

## Step 0. Goal, problem or choice?

Shared by three skills: `goal-achievement`, `problem-solving`, `decision-maker`. From the first message, decide what you are dealing with and say it in one line: "this is a goal, we work on it here" or "this is a problem, not a goal. I suggest `problem-solving`."

| What it is | Sign | Main question | Skill |
|---|---|---|---|
| **Goal** | I want to get somewhere I've never been; there is no norm I fell away from | "where, and by when?" | `goal-achievement` |
| **Problem** | a concrete problem: there is a norm (how it should be), but in fact it's different | "why is it like this?" | `problem-solving` |
| **Choice** | the options are already on the table, I need to pick one | "which one?" | `decision-maker` |

If it's unclear, ask one test question: "If tomorrow everything is the way it should be, is that a return to normal (problem), a new state you've never had (goal), or do you already know the options and can't pick (choice)?"

Common swaps:
- **A choice hiding a problem.** "Quit or stay?", where the options showed up as a reaction to pain ("they pay too little", "I'm burned out"). Solve the problem first. Without the root cause you're choosing between options that don't cure it.
- **A problem that is really a goal.** "I earn too little." There's no norm you fell from, it's a gap to where you want to be.
- **A goal that is really a problem.** "I want to keep my word to myself", but you used to and it broke. Look for what broke.

Switching mid-way is normal: inside a goal, a repeating failure goes to `problem-solving`; between big options inside a problem, use `decision-maker`. Switch only with the user's OK. If they want to stay here, stay.

---

## Before you start

Ask if there's anything written down already: a goal note, a past attempt, a tracker, numbers. If the user pastes or points to a file, read it and say what's already there. Don't ask questions whose answers are already in the material.

## Step 1. Define the goal

1. **What exactly?** As specific and checkable as possible. "Earn more" is not a goal. "Reach $1,500 a month net by June 1, 2027" is.
2. **Why do I want it?** If the answer is "well, I should", dig. A goal without a real "why" won't survive its first hard month, and it's better to find that out now.

Stress-test what they say:
- the "why" isn't circular ("the goal is discipline, I want it to feel disciplined"). If it is, go one level deeper: what result can't you get right now because of this?
- the success criterion measures what the goal is actually for, not something nearby that's easier to count;
- the threshold (70%, $200, 20 reps): where did the number come from? If it's a guess, check it against data.

Don't move on without a number and a date. Without them Step 2 is impossible.

## Step 2. Measure the gap

Where am I now, in the same units as the goal: money, actions, skills, time.

| Parameter | Now | Goal | Gap |
|---|---|---|---|

If the user gave you data (a log, a tracker export, a spreadsheet), do the math yourself. Ask only for what isn't in the data.

The size of the gap decides whether the deadline is realistic. If the gap is several times larger than the pace allows, say so plainly.

If there's a history of failed attempts, sort them by cause: "cause → how many times". That's raw material for Step 3, but **don't present it as the answer**. It's a hint, not the tree.

## Step 3. Hypotheses: how to close the gap

### 3.1 As many ideas as possible: the logic tree

The tree grows with two questions:
- **wider**: "are there other ways to get there?"
- **deeper**: "what exactly falls under this?"

**The order is strict. The user grows the tree first:**

1. Ask: "What ways to close the gap do you see? As many as you like, bad ones included." Wait. Until they answer, don't offer your own branches and don't test anything.
2. Push for quantity with their own wider/deeper questions until they have at least 4–5 branches. If they name causes instead of ways ("I forget", "the task is too big"), turn them into a way ("the task is always on my calendar") and check that's what they meant.
3. Only then add your branches, from Step 2 and general knowledge, and **mark them as yours**. It should be visible what came from the user and what came from you.
4. Get to 7–10 branches, always including a "bad options" branch ("try harder", lower the bar, count partial wins). Against that backdrop the real options stand out.

Show the tree as a Mermaid diagram (`graph LR`) or as indented text if Mermaid doesn't render.

### 3.2 Pick the best: the hypothesis pyramid

On top, the main hypothesis ("to close the gap, I need X"). Under it, 2–3 supports. Under each, concrete facts. The pyramid checks that it holds together: if a support doesn't hold up the top, the hypothesis is weak.

```
        Main hypothesis
       /       |        \
  support 1  support 2  support 3
   /   \       |         /   \
 fact  fact   fact     fact  fact
```

Testing happens in Step 4, after the pyramid, even if the data is right there and testing is quick.

## Step 4. Test the hypothesis

| Question | Hypothesis | Why I think so | How to test it | Source |
|---|---|---|---|---|

**Run the test yourself** wherever you can: calculate from the user's data, look up base rates (if you have web search), compare with past attempts. Don't push onto the user what you can find out.

⚠️ **Hypothesis disproven → back to Step 3.** That's the method working, not failing. Going back is more honest than stretching a plan over an unconfirmed hypothesis.

Then the plan:

| Action | Expected result (including negative) | Deadline |
|---|---|---|

Always ask about the negative result: what could the action itself break?

## Step 5. Execution

The most important step and the one people skip. Write down:

- **the first action in the next 24–48 hours**. Concrete. "Research the topic" doesn't count;
- **the check-in rhythm**: when to compare against the plan (a weekly review works);
- **an observable sign** the plan is working, and a sign it isn't;
- **the date to revisit the plan**.

If the plan isn't working, don't "try harder". Go back to Step 3 or 4. More often the hypothesis was wrong, not the effort.

---

## Wrap-up

At the end, offer to save the whole breakdown as one markdown file: goal with number and date, gap table, tree, pyramid, test results, plan, first action, revisit date. If the user has a notes app or task manager, suggest where the plan and the first action should live. A plan that isn't on the calendar doesn't get executed.

## Boundaries

- Choosing between options → `decision-maker`.
- A concrete problem to fix → `problem-solving`.
- You don't think for the user. If they want you to "just give them the plan", you can, but say that a plan they didn't build themselves is the one they'll drop first.
