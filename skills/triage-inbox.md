# Triage Inbox Skill

Use this when I say "triage my inbox", "what's in my email", or "deal with my emails".

The job: turn a noisy inbox into a ranked, decided list — and drafted replies in my voice — without me reading every message cold. **Never send. Draft only. I approve.**

## Context To Load

- `CLAUDE.md`
- `memory/profile.md` (who I am, constraints)
- `memory/goals.md` (north star + projects — what "matters" means)
- `memory/projects.md` (SB2.0, Factory, ISG — sender relevance)
- `memory/examples.md` (my voice for drafts)
- `tools/allowed-tools.md` (Gmail = read + draft only)

## Steps

1. Read unread / recent inbound email (read-only via Gmail MCP). If Gmail isn't connected, ask me to paste threads into `inbox/` and process those instead.
2. For each message, classify into exactly one bucket:
   - **ACT** — needs a decision or task from me (not just a reply).
   - **REPLY** — needs a response; draftable now.
   - **READ** — worth my eyes, no action (FYI, newsletters I chose).
   - **IGNORE** — noise, promo, no-reply. Don't surface individually; just count.
3. Rank ACT + REPLY by: relevance to active projects (SB2.0 / Factory / ISG) → time-sensitivity (named deadline) → relationship value. Note **why now** for each.
4. For every REPLY, draft a response in my voice (see `memory/examples.md`). Keep it short, direct, one clear next step.
5. Flag anything that touches the hard boundaries (money, pricing, sending on my behalf, settings) — surface, never act.
6. Suggest what to save to `memory/` (a new recurring sender, a decision, a pattern).

## Quality Gate (must pass before showing me)

- [ ] Every ACT/REPLY item has a one-line "why now".
- [ ] Drafts sound like me, not like an assistant. No filler, no hype.
- [ ] Nothing was sent, archived, or deleted.
- [ ] IGNORE is a count, not a wall of text.
- [ ] Ranked top-down — I can act on #1 immediately.

## Output Format

# Inbox Triage — [date] — [N unread]

## Act now ([count])
1. **[Sender] — [subject]** · why now: [...] · suggested action: [...]

## Replies drafted ([count]) — approve to send
1. **[Sender] — [subject]** · why it matters: [...]
   > [draft in Iwo's voice]

## Read later ([count])
- [Sender] — [subject] (one line)

## Ignored: [count] (promo/noise)

# Needs your call
- [anything touching a hard boundary]

# Memory Write-Back
- [new senders, decisions, or patterns worth saving]
