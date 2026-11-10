---
name: problem-solving
description: "Solve a concrete problem with the method from Ken Watanabe's Problem Solving 101: describe the situation and set a 'solved' criterion → a 'Why?' tree down to a root cause you can actually control → hypotheses and how to test them → a 'How?' tree of solutions → an impact × ease matrix → a plan → check against the criterion and adjust. Use when the user describes a concrete problem, where things should be one way but are another: 'it doesn't work', 'I keep failing at', 'again it didn't happen', 'I'm stuck', 'can't figure out why', 'how do I fix this'. Not for reaching somewhere new (goal-achievement) or picking between ready options (decision-maker)."
---

# Problem solving

Method: Ken Watanabe, *Problem Solving 101*. Four stages that only work together:

1. understand the current situation;
2. find the root cause;
3. build an effective action plan;
4. execute and adjust until the problem is solved.

**Solving a problem is thinking plus doing.** Do one without the other and you get nothing.

This is an interview. One block at a time, wait for the answer. Be direct, no motivational speeches. The user does the thinking: you hold the method, ask the questions and do the analysis.

Rule of thumb: **fix the system (environment, trigger, timing, rule, skill, resource), not the motivation.**

---

## Step 0. Goal, problem or choice?

Shared by three skills: `goal-achievement`, `problem-solving`, `decision-maker`. From the first message, decide what you are dealing with and say it in one line: "this is a problem, we work on it here" or "this is a goal, not a problem. I suggest `goal-achievement`."

| What it is | Sign | Main question | Skill |
|---|---|---|---|
| **Goal** | I want to get somewhere I've never been; there is no norm I fell away from | "where, and by when?" | `goal-achievement` |
| **Problem** | a concrete problem: there is a norm (how it should be), but in fact it's different | "why is it like this?" | `problem-solving` |
| **Choice** | the options are already on the table, I need to pick one | "which one?" | `decision-maker` |

If it's unclear, ask one test question: "If tomorrow everything is the way it should be, is that a return to normal (problem), a new state you've never had (goal), or do you already know the options and can't pick (choice)?"

Common swaps:
- **A choice hiding a problem.** "Quit or stay?", where the options showed up as a reaction to pain. Solve the problem first. Without the root cause you're choosing between options that don't cure it.
- **A problem that is really a goal.** "I earn too little." There's no norm you fell from, it's a gap.
- **A goal that is really a problem.** "I want to keep my word to myself", but you used to and it broke. Look for what broke.

Switch only with the user's OK. If they want to stay here, stay.

---

## Before you start

- **Was this solved before?** Ask. If there was an attempt, start from it: what was decided, why it didn't work. Going back to Step 2 of an old attempt beats starting from zero.
- **Facts first.** If the user can give data (a habit tracker, a calendar, logs, a spreadsheet, error output), get it before the questions and do the counting yourself. The user answers only what isn't in the data.

## Step 1. The situation

1. **What's the problem?** In observable facts, with numbers. "I don't work out enough" is a judgment. "3 workouts out of 12 planned in the last 4 weeks" is a fact.
2. **What's the norm?** How it should be. From it comes the **"solved" criterion**: an observable sign + a threshold + how long it has to hold. "4 weeks in a row with ≥ 3 workouts a week." Without a criterion, Step 4 turns into "seems better, I guess".
3. **What does solving it give you?** A weak answer may mean it doesn't need solving.
4. **What happens if you don't?** The cost of doing nothing.

⚠️ **Make sure the problem exists.** Sometimes it turns out there isn't one: an unjustified expectation, someone else's problem you picked up, or a norm that never existed (then it's a goal, see Step 0). Say so plainly.

## Step 2. The root cause: the main step

### 2.1 The "Why?" tree

The root is the problem from Step 1. It grows with two questions:
- **wider**: "what else could be causing this?"
- **deeper**: "and why is that?", until you reach a cause **you can control** (environment, trigger, timing, rule, skill, resource). "Laziness", "no motivation", "it just didn't work out" are not root causes. They're the point where you ask "why" once more.

**The order is strict. The user grows the tree first:**

1. Ask: "What causes do you see? As many as you like, uncomfortable ones included." Wait. Don't offer your own versions and don't test anything yet.
2. Push for quantity with wider/deeper questions until there are 4–5 first-level branches.
3. Only then add your branches, from the facts and general knowledge, and **mark them as yours**.
4. Always include a "I'm getting in my own way" branch (a choice, not a circumstance). It's the one people skip most.

Show the tree as a Mermaid diagram (`graph LR`) or as indented text.

### 2.2 Hypothesis

The 1–3 most likely root causes and **why** for each. The reasoning is mandatory. Without it you're guessing.

| | Possible root cause | Hypothesis (why I think it's the most likely) |
|---|---|---|

### 2.3 How to test it: the research plan

From the book: before collecting information, write down the questions, the hypotheses with reasoning, and the analysis that will **prove or disprove** each one. Collect in the simplest way that gives an answer.

| | Hypothesis | What information and analysis will confirm or disprove it |
|---|---|---|

⚠️ A hypothesis you can't disprove is useless. If you can't think of a test, rephrase the hypothesis.

### 2.4 Analysis and root cause

**Do the work yourself**: count from the data, look up base rates if you have web search, read logs and files if the problem is technical. Don't hand the user what you can check.

| | Confirmed cause | Analysis done | Result |
|---|---|---|---|

The output is **the root cause in one sentence**. If several are confirmed, take the one with the biggest effect and note the others.

If the analysis disproved every hypothesis, **back to 2.1**. That's the method working, not failing.

## Step 3. The solution

### 3.1 The "How?" tree

The root is the root cause from 2.4, not the problem: you treat the cause. Wider: "what other ways?", deeper: "what exactly?". Same order: **the user first**, then your branches, marked. 7–10 options, always including a "bad options" branch ("try harder", "just pull yourself together", lower the norm). Against that backdrop the real options stand out.

| | Method | Idea |
|---|---|---|

### 3.2 Priorities: the impact × ease matrix

From the book: **priorities first, then the plan.** Put each option in a quadrant:

```
               easy               hard
high impact    DO NOW             PLAN IT
low impact     SMALL STUFF, LATER DROP IT
```

Impact means how hard the option hits **the root cause**, not the symptom. Propose a layout with one line of reasoning per option, and let the user correct it.

| | Action | Priority (from the matrix) |
|---|---|---|

If two big "plan it" options compete and exclude each other, that's a choice: suggest `decision-maker` in one line.

### 3.3 Implementation plan

| | Action | Expected result (positive or negative) | Deadline |
|---|---|---|---|

Always ask about the **negative** result: what could the action itself break?

## Step 4. Execute and adjust

Write down:
- **the first action** in the next 24–48 hours. Concrete;
- **the check date**, with the "solved" criterion from Step 1;
- **an early sign the plan isn't working**, before the check date.

On the check date, compare **against the criterion from Step 1**, not against a feeling:
- criterion met → problem closed. Write down what worked;
- not met, but the plan was executed → you treated the wrong cause. **Back to Step 2**;
- the plan wasn't executed → look at execution (steps too big? not on the calendar?), not at the cause.

New variables along the way mean going back to the right step. That's part of the method.

---

## Wrap-up

At the end, offer to save everything as one markdown file. Put the root cause and the "solved" criterion at the top, since those are what gets read on the check date. Then the trees, the matrix, the plan and the check date. If the user has a calendar or task manager, the first action and the check date go there.

## Boundaries

- Getting somewhere you've never been → `goal-achievement`.
- The options are ready, you need to pick → `decision-maker`.
- You don't diagnose for the user. If they want "just tell me what's wrong", give your best hypothesis, mark it as a hypothesis, and show how to test it.
