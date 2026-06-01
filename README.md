# AI Second Brain Boilerplate

A tiny starter repo for building an AI Second Brain: persistent context, reusable workflows, and memory write-back.

The goal is not to build a huge knowledge base. The goal is to stop re-explaining your business to AI from scratch.

## What This Includes

```text
ai-second-brain-boilerplate/
  CLAUDE.md
  memory/
    profile.md
    goals.md
    projects.md
    decisions.md
    examples.md
  skills/
    daily-priorities.md
    decision-memo.md
  inbox/
    messy-week-notes.md
  demo/
    my-second-brain-opener.md
    opening-second-brain-answer.md
    session-checklist.md
  tools/
    allowed-tools.md
```

## How To Use It

Open this folder in Claude Code or any AI coding assistant that can read project files.

The easiest starting point is the adaptive copy-paste mega prompt:

- `MEGA_PROMPT_V2.md`

Use it when you want Claude to inspect this repo, research your public context, play back what it understood, ask only what is missing, propose workflow candidates, and personalize the boilerplate for you.

`MEGA_PROMPT.md` is the shorter v1. Start with v2 unless you want a simpler setup.

If you want a shorter first prompt, use:

```text
Load my operating context from this repo.

Then read inbox/messy-week-notes.md and run the daily priorities workflow from skills/daily-priorities.md.
```

## Seven-Day Setup

1. Day 1: Edit `CLAUDE.md` with who you are and how AI should work with you.
2. Day 2: Fill in `memory/profile.md`, `memory/goals.md`, and `memory/projects.md`.
3. Day 3: Add examples of good and bad output to `memory/examples.md`.
4. Day 4: Turn one repeated prompt into a reusable workflow in `skills/`.
5. Day 5: Add one real source of truth to `inbox/` or `memory/`.
6. Day 6: Add a quality gate to your workflow.
7. Day 7: Add a memory write-back step so each session improves the next one.

## Core Idea

A prompt is useful once. A workflow is useful every week.

Your AI Second Brain should answer five questions:

1. Who am I?
2. What am I trying to accomplish?
3. What context matters?
4. What workflows repeat?
5. What should be remembered for next time?

## First Prompt

```text
Load this repo as my AI Second Brain.

Explain what context you found, what is missing, and the first workflow I should customize.
```

## Live Demo Materials

If you are presenting this concept to others, use:

- `demo/my-second-brain-opener.md` to explain your own Second Brain in numbers before the demo.
- `demo/opening-second-brain-answer.md` for the opening before/after moment.
- `demo/session-checklist.md` for the full 60-minute storytelling flow.

The simplest story:

1. Show what generic AI says with no context.
2. Show what AI says after reading your Second Brain.
3. Turn the repeated prompt into a workflow.
4. Save what was learned back into memory.
5. Give people this boilerplate so they can build their first version.
