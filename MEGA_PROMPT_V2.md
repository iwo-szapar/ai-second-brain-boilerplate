# AI Second Brain Mega Prompt v2

Single-input, adaptive setup.

Copy and paste this into Claude Code from inside this repo.

This version is designed for people who are juggling many things: founders, operators, consultants, creators, and employees with too much context spread across their head, notes, docs, and browser tabs.

Before running it, replace the placeholders in `[square brackets]`.

```text
You are helping me build my first AI Second Brain.

An AI Second Brain is a small working system that helps AI remember how to help me:
- who I am
- what I am responsible for
- what I am trying to accomplish
- what projects and decisions matter
- what good output looks like
- which workflows I repeat
- what should be remembered after each useful session

The goal is not to build a giant knowledge base.
The goal is to stop re-explaining myself to AI from scratch.

I am starting from this boilerplate repo.
Your job is to turn it into a useful v0 of my personal AI Second Brain.

My starting context:
- Name: [YOUR NAME]
- Role: [FOUNDER / EMPLOYEE / CONSULTANT / CREATOR / OPERATOR / OTHER]
- Company, team, or project: [COMPANY / TEAM / PROJECT]
- What I am responsible for: [SHORT DESCRIPTION]
- Current situation: [WHAT FEELS MESSY OR OVERLOADED RIGHT NOW]
- Current goals: [1-3 GOALS]
- Current constraints: [TIME, ENERGY, TEAM, MONEY, FOCUS, ACCESS, ETC.]
- Recurring work I want AI to help with: [PRIORITIZATION, DECISIONS, MEETINGS, WRITING, RESEARCH, SALES, PLANNING, REPORTING, ETC.]
- Public links about me or my work: [LINKEDIN, WEBSITE, GITHUB, COMPANY PAGE, NEWSLETTER, PORTFOLIO, ETC.]
- Optional messy context dump: [PASTE NOTES, BIO, CURRENT PROJECTS, TODO LIST, ABOUT PAGE, JOB DESCRIPTION, RECENT POST, ETC.]

Run the phases below in order.
Do not skip ahead.
Do not edit files until I confirm the snapshot and workflow direction.
Do not invent facts.
If you are unsure, ask.

PHASE 1: Inspect the boilerplate

Read the repo first.

Inspect:
- CLAUDE.md
- README.md
- memory/profile.md
- memory/goals.md
- memory/projects.md
- memory/decisions.md
- memory/examples.md
- skills/daily-priorities.md
- skills/decision-memo.md
- inbox/messy-week-notes.md
- tools/allowed-tools.md

Then explain in 5 bullets what this boilerplate already gives me.

PHASE 2: Play back what you understand

Read my starting context and messy context dump.

Summarize me back in one paragraph, 5-7 sentences max.

Include:
- who I am
- what I seem responsible for
- what I am trying to accomplish
- what feels overloaded or messy
- what recurring work AI could help with

Quote at least two phrases from my own text.

End with exactly:
"Did I get this right? Anything I missed or got wrong?"

Wait for my correction before continuing.

PHASE 3: Research my public context

After I confirm the playback, research my public footprint using the links I provided.

Use web search, web fetch, browser tools, or other available research tools.

If you cannot access the web in this session, say so explicitly and switch to inference mode. Mark every external claim as "inferred, not verified."

Look for:
- how I describe myself publicly
- what I am building or responsible for
- my audience, customers, team, or stakeholders
- recent projects, posts, products, talks, writing, or public proof
- recurring themes in my work
- signals about my positioning or priorities

Research rules:
- Use only public information.
- Cite the sources you checked.
- Separate verified facts from interpretations.
- Do not include sensitive assumptions.
- Do not over-research. Spend enough time to improve the setup, not to write a biography.

Output:

# Public Context Found

## Verified
- [fact] — [source]

## Inferred
- [interpretation] — why you infer it

## Still Unknown
- [important missing fact]

PHASE 4: Create my operating snapshot

Before editing files, create a compact snapshot that will guide the whole Second Brain.

Output exactly:

PERSONAL OPERATING SNAPSHOT
Role:
Current situation:
Main goal:
Current constraints:
Active projects:
Open loops:
Recurring work:
Decision style:
What good AI help looks like:
What AI should not do:
Public context that matters:
Uncertainties:

If any field is weak or unclear, ask up to 5 focused questions.

Only ask questions that materially improve the brain.

Good questions are specific:
- "Which goal matters most this month if everything else slips?"
- "What decision do you keep re-deciding?"
- "What recurring task would save you the most time if AI handled 70% of it?"
- "What does bad AI advice usually look like for you?"
- "What should AI never do without asking?"

Wait for my answers before continuing.

PHASE 5: Propose three workflow candidates

Do not build workflows yet.

First propose three candidates:

1. Safest workflow — closest to work I already do and easiest to trust.
2. Highest-leverage workflow — removes the most repeated pain or decision fatigue.
3. Fastest-to-value workflow — useful in under 10 minutes this week.

For each candidate, output:

WORKFLOW CANDIDATE [1/2/3]
Name:
When I would use it:
Context it needs:
Output it produces:
Why it matters now:
Risk or limitation:

Then recommend one workflow to build first.

Be decisive.
Do not say all three are equally good.

Ask:
"Does this first workflow match how you actually work, or should I change it before building?"

Wait for my confirmation.

PHASE 6: Build v0 of the Second Brain

After I confirm, update the repo.

Edit existing files first:
- CLAUDE.md
- memory/profile.md
- memory/goals.md
- memory/projects.md
- memory/decisions.md
- memory/examples.md
- inbox/messy-week-notes.md
- tools/allowed-tools.md

Create or update up to 3 files in skills/.

For each workflow file, include:
- when to use it
- context to load
- steps to follow
- output format
- quality gate
- memory write-back rule

Keep the first version small.
Prefer useful over complete.

Do not add more files unless there is a clear reason.

PHASE 7: Run the first useful workflow

After editing the files, run the recommended first workflow.

The first answer should make the value obvious.

If the workflow is prioritization, use this format:

# This Week's Focus

## Top 3 Priorities

### 1. [Priority]
Why now:
Next action:
Time box:

### 2. [Priority]
Why now:
Next action:
Time box:

### 3. [Priority]
Why now:
Next action:
Time box:

## What Not To Do This Week

## Memory Write-Back

## What I Still Need To Know

If the workflow is not prioritization, use the output format from that workflow file.

PHASE 8: Explain what you built

After the first workflow run, explain the new Second Brain in plain English.

Use this structure:

# Your AI Second Brain v0

## What It Knows Now

## What Workflows You Can Run

## What To Add Next

## How To Keep It Useful In 10 Minutes Per Week

## Files Changed

PHASE 9: Memory write-back

End by extracting what should be remembered from this setup session.

Output:

# Memory Write-Back

## New Decisions

## Reusable Patterns

## Open Questions

## Suggested File Updates

Working style for the whole setup:
- Be practical.
- Be specific.
- Keep the first version small.
- Ask before editing.
- Prefer editing existing files over creating new ones.
- Do not use private tools or accounts unless I explicitly authorize them.
- Do not contact anyone, publish anything, or send anything.
- If online research is unavailable, ask me to paste more context.
- If I provide sensitive context, keep it local to this repo and do not include it in public-facing examples.
```

## Why This Version Works

This version starts with a single prompt, then adapts.

It does not assume the user understands folders, skills, agents, or workflows upfront.

It follows this path:

```text
Messy input -> playback -> public research -> operating snapshot -> workflow candidates -> confirmation -> files -> first useful answer -> memory write-back
```

## Best For

- Founders juggling sales, product, content, hiring, and delivery.
- Employees managing multiple stakeholders, meetings, projects, and decisions.
- Consultants who want AI to understand their clients, offers, and recurring deliverables.
- Creators who want to turn their expertise into repeatable workflows.
