# Live Session Checklist

Use this flow to teach AI Second Brain without scaring people.

## Goal

Show people the value of an AI Second Brain by building toward a real artifact: a resource page or follow-up asset where attendees can request this boilerplate.

Core story:

```text
I am not just teaching the concept.
By the end, I will point you to the resource you can use to start.
```

## Pre-Session Setup

- Prepare this boilerplate repo.
- Prepare a fictional demo founder.
- Prepare your real Second Brain opening prompt.
- Prepare fallback outputs for all live prompts.
- Open Claude or Claude Code with only safe demo files visible.
- Hide private tabs, notifications, bookmarks, email, and messaging apps.
- Have your resource page or draft CTA ready.

## Act 1: Show The Difference

### 0-5 min: Cold Open

Say:

```text
Before I explain what an AI Second Brain is, I want to show you the difference between normal AI and AI that has context.
```

Ask your real Second Brain:

```text
Given everything you know about my current business, what should I focus on this week?

Use my goals, current projects, open loops, and recent decisions.
Return:
- top 3 priorities
- why now
- what not to do
- what should be remembered
```

Checklist:

- Show the answer briefly.
- Point out why it is specific.
- Do not expose private details for too long.
- Say: "This is not magic. It is context, memory, workflows, and write-back."

Transition:

```text
Now I am going to rebuild the pattern from scratch using a safe demo, so you can copy it.
```

## Act 2: Make The Problem Obvious

### 5-10 min: Blank AI Failure

Prompt:

```text
Help me decide what to focus on this week.

I have a lot going on and need to know what to prioritize.
```

Checklist:

- Show the generic answer.
- Do not ridicule it.
- Say: "This is advice from someone who has never met me."
- Explain that the model is not the problem. Missing context is the problem.

## Act 3: Introduce The Tiny Brain

### 10-18 min: Show The Folder

Open:

```text
ai-second-brain-boilerplate/
  CLAUDE.md
  memory/
  skills/
  inbox/
  tools/
```

Explain in human language:

- `CLAUDE.md` = how AI should work with you.
- `memory/` = things you are tired of retyping.
- `skills/` = repeatable workflows.
- `inbox/` = messy raw inputs from life and work.
- `tools/` = boundaries for what AI can safely do.

Key line:

```text
If you have explained something to AI three times, it probably belongs in memory.
```

## Act 4: Show Context Working

### 18-28 min: Run The Brain-Aware Prompt

Prompt:

```text
Load the operating context from this folder.

Use:
- CLAUDE.md
- memory/profile.md
- memory/goals.md
- memory/projects.md
- memory/decisions.md
- memory/examples.md
- inbox/messy-week-notes.md

Then tell me the top 3 priorities for this week.

For each priority:
- explain why now
- give the next action
- time box it

Also tell me what not to do this week.
```

Checklist:

- Compare with the generic answer.
- Point out specificity.
- Point out "what not to do."
- Explain that context created the quality jump.

Key line:

```text
Same AI. Different context. Different quality.
```

## Act 5: Turn Prompt Into Workflow

### 28-38 min: Show The Skill

Open:

```text
skills/daily-priorities.md
```

Say:

```text
If I ask this once, it is a prompt.
If I ask this every week, it should become a workflow.
```

Prompt:

```text
Use skills/daily-priorities.md.

Run the daily priorities workflow using the current memory and messy week notes.
After the result, suggest one improvement to the workflow.
```

Checklist:

- Explain that a skill is just a reusable recipe.
- Show context to load, steps, output format, and quality gate.
- Emphasize that the workflow now lives outside your head.

## Act 6: Show The Compounding Loop

### 38-45 min: Memory Write-Back

Prompt:

```text
Based on this prioritization, extract what should be saved back into memory.

Return:
- new decision
- reusable pattern
- open question
- suggested destination file
```

Checklist:

- Show how a session improves the next session.
- Explain that most AI chats vanish when closed.
- Explain that Second Brain captures useful learning.

Key line:

```text
A normal AI session gives you an answer.
A Second Brain makes the next answer better.
```

## Act 7: Build Or Point To The Real Resource

### 45-55 min: Create The Follow-Up Asset

Say:

```text
Now I want to do something meta.

Instead of ending with theory, I am going to create or show the resource page where you can request this boilerplate.
```

Suggested resource page sections:

- Headline: AI Second Brain Boilerplate
- Promise: Start with one folder, one instruction file, one memory layer, one workflow.
- Benefits: stop re-explaining yourself, turn prompts into workflows, make AI remember what matters.
- Included: `CLAUDE.md`, `memory/`, `skills/`, `inbox/`, `tools/`.
- CTA: Request the boilerplate.

## Act 8: Seven-Day Build Plan

### 55-60 min: Close

Show:

```text
Day 1: Create one folder and one instruction file.
Day 2: Add profile, goals, projects, and constraints.
Day 3: Add examples of good and bad output.
Day 4: Turn one repeated prompt into a workflow.
Day 5: Add one real source of truth.
Day 6: Add one quality gate.
Day 7: Add one review loop that writes back to memory.
```

Closing line:

```text
The winning move is not to ask AI better questions.

The winning move is to build the system that makes better questions automatic.
```

## Backup Plan

If live coding or resource creation is too risky:

- Show this GitHub repo.
- Ask Claude to generate the landing page copy.
- Say: "I will ship this page right after the session and send it to everyone."
- Still show the artifact being created in real time.
