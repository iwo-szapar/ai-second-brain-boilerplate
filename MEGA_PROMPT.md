# AI Second Brain Mega Prompt

Copy and paste this into Claude Code from inside this repo.

Before running it, replace the placeholders in `[square brackets]`.

```text
I want you to help me build my first AI Second Brain in this folder.

I am starting from a boilerplate, but I want you to personalize it for me.

My context:
- Name: [YOUR NAME]
- Role: [FOUNDER / EMPLOYEE / CONSULTANT / CREATOR / OTHER]
- Company or project: [COMPANY OR PROJECT]
- What I am building or responsible for: [SHORT DESCRIPTION]
- Current situation: I am juggling many things and want AI to stop giving me generic advice.
- Current goals: [LIST 1-3 GOALS]
- Current constraints: [TIME, ENERGY, TEAM, MONEY, FOCUS, ETC.]
- Recurring work I want help with: [PRIORITIZATION, DECISIONS, WRITING, RESEARCH, MEETINGS, SALES, PLANNING, ETC.]
- Public links about me or my work: [WEBSITE, LINKEDIN, GITHUB, NEWSLETTER, COMPANY PAGE, ETC.]

Your job:
Build a useful v0 of my AI Second Brain inside this repo.

Do not overbuild.
Do not create a giant knowledge base.
Create the smallest useful system that helps AI understand me, my work, my priorities, and my recurring workflows.

Use this principle:
If I would have to explain it to AI more than three times, it probably belongs in memory.

Step 1: Inspect the repo
- Read the current file tree.
- Read CLAUDE.md.
- Read files in memory/.
- Read files in skills/.
- Read inbox/messy-week-notes.md.
- Read tools/allowed-tools.md.
- Explain briefly what this boilerplate already gives me.

Step 2: Research me online
Use web search or available browser/research tools to inspect my public footprint from the links I provided.

Look for:
- how I describe myself
- what I am building or responsible for
- my audience, customers, team, or stakeholders
- recent projects, posts, products, talks, writing, or public proof
- recurring themes in my work
- signals about my priorities or positioning

Important research rules:
- Use only public information.
- Cite the sources you checked.
- Do not invent facts.
- If a fact is uncertain, mark it as uncertain.
- Do not include sensitive assumptions about me.

Step 3: Interview me before editing
Before changing files, ask me up to 7 focused questions.

Only ask questions that would materially improve the Second Brain.

Prioritize questions about:
- what matters most this month
- what I am currently avoiding or dropping
- what good AI output looks like for me
- what decisions I keep re-deciding
- what repeated workflows I want to turn into reusable recipes
- what AI should never do without asking me

Step 4: Build the v0 Second Brain
After I answer, update the repo files.

Edit these files:
- CLAUDE.md
- memory/profile.md
- memory/goals.md
- memory/projects.md
- memory/decisions.md
- memory/examples.md
- inbox/messy-week-notes.md
- tools/allowed-tools.md

Create or update up to 3 workflow files in skills/.

Recommended starting workflows:
- weekly-priorities.md
- decision-memo.md
- meeting-prep.md

For each workflow, include:
- when to use it
- context to load
- steps to follow
- output format
- quality gate
- memory write-back rule

Step 5: Give me my first useful answer
After building the v0, run the weekly priorities workflow.

Answer:
- What should I focus on this week?
- Why now?
- What should I not do?
- What should be remembered for next time?

Output format:

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

Step 6: Explain the system simply
After the files are updated and the first answer is generated, explain my new AI Second Brain in plain English.

Use this structure:
- What this brain knows now
- Which workflows I can run
- What I should add next
- How to keep it useful in 10 minutes per week

Working style:
- Be practical.
- Be specific.
- Keep the first version small.
- Prefer editing existing files over creating many new files.
- Do not use private tools or accounts unless I explicitly authorize them.
- If something should be researched but you cannot access it, ask me to paste it.
```

## What This Prompt Does

This prompt turns the boilerplate into a guided setup flow:

1. Claude reads the existing repo.
2. Claude researches your public context.
3. Claude asks a few clarifying questions.
4. Claude edits the memory and workflow files.
5. Claude gives you the first useful weekly priority answer.

## Why Start With A Mega Prompt

Most people understand one strong prompt before they understand a system.

The prompt is the bridge:

```text
Prompt -> context -> memory -> workflow -> write-back
```

Once the first run works, you turn the parts of the prompt you repeat into files and workflows.
