# Goals, problems, decisions: 3 agent skills

Three skills that turn Ken Watanabe's *Problem Solving 101* into an interview your AI runs with you.

| Skill | Use it when | What you get |
|---|---|---|
| `goal-achievement` | you want to get somewhere you've never been | goal with a number and a date → gap table → logic tree → hypothesis pyramid → tested plan → first action |
| `problem-solving` | you have a concrete problem: it should be one way, it's another | "solved" criterion → "Why?" tree → root cause you can control → "How?" tree → impact × ease matrix → plan → check date |
| `decision-maker` | the options are on the table and you can't pick | four-question square → weighted pros/cons → criteria scores → scenarios → pre-mortem → confidence % → decision card |

All three share a "step 0": before anything else, the skill figures out whether you have a goal, a problem or a choice. A lot of stuck people are solving the wrong type ("quit or stay?" is often a problem in disguise).

## What these skills don't do

They don't think for you. The model asks questions one at a time, makes you grow the trees yourself before it adds its own branches (marked as its own), refuses to skip the hypothesis test, and does the math. The answers are yours.

## Install

The skills use the open [Agent Skills](https://agentskills.io) format: a folder with a `SKILL.md` file. Claude Code, Codex, Cursor, Gemini CLI, GitHub Copilot and dozens of other agents read it.

**Any coding agent, one command** (needs Node.js):

```bash
npx skills add ganter112/goals-problems-decisions
```

It asks which skills and which agents to install to. Add `-g` to make them available in every project. This uses the open [skills CLI](https://github.com/vercel-labs/skills).

**By hand:** copy the folders from `skills/` into your agent's skills folder, for example `~/.claude/skills/` for Claude Code.

**Claude app (claude.ai):** zip each folder from `skills/` separately and upload it under Skills in settings.

**ChatGPT, Gemini, Grok or any other chat:** open `SKILL.md`, copy everything below the `---` header and paste it into the instructions of a Project, Custom GPT or Gem. Or just paste it as your first message and add "follow these instructions". One skill per project works best.

Then describe your goal, problem or choice in plain words. Trees and matrices are drawn in Mermaid where the app renders it, and as plain text everywhere else.

## Credits

- Ken Watanabe, *Problem Solving 101: A Simple Book for Smart People*: the goal steps, the root-cause steps, logic trees, the impact × ease matrix, weighted pros/cons and criteria tables.
- Annie Duke, *Thinking in Bets*: confidence in %, pre-mortem, judging the process rather than the outcome.
- Dan Koe, "How to fix your entire life in 1 day": why the goal matters before the method does.

The skills retell the methods in their own words. Read the books, they're short.

— @NoBigDeAI
