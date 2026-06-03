# Decisions

Use this file to prevent re-deciding the same things.

## Decision Template

### YYYY-MM-DD: Decision title

Decision:

Reason:

Tradeoff:

Review date:

---

### 2026-06-03: First automation target is email triage

Decision: The Second Brain's first job-to-be-done is email triage, not content or outreach.

Reason: Inbound email is Iwo's #1 time/energy drain right now. Highest-leverage thing to remove first.

Tradeoff: Content and creator-outreach automation wait until triage is working.

Review date: 2026-07-03

### 2026-06-03: Brain operates solo — decide and draft, never send

Decision: The brain decides and drafts; Iwo approves. No autonomous sending, deleting, archiving, or publishing.

Reason: Iwo works solo; outputs are for him, not a team. Trust is built before autonomy.

Tradeoff: Slightly more approval steps in exchange for zero risk of a bad message going out.

Review date: ongoing

### 2026-06-03: Pattern — "said yes" session invites fall through the inbox

Pattern (learned from first live triage): People reply YES to live-session invites, but the calendar hold doesn't always go out. Two warm yeses (Gabe Marusca, Jan; Caroline Mol, Apr) sat unanswered until the brain surfaced them — both sessions had already passed.

Why it matters: these are dropped relationships, not noise. The inbox hides them because a 3-month-old "YES!" looks like an old read email.

How to apply: triage should always flag positive replies to outbound invites as open loops, even when old. Consider a standing "said-yes-to-a-session" tracker so a yes can't get lost between reply and calendar.

Open question: build that tracker as a second skill, or keep it inside triage-inbox?

### 2026-06-03: Personalize the boilerplate, keep the distributable shell

Decision: Fill `memory/` and add a triage skill + inbox agent; leave README, mega prompts, and `demo/` intact because they serve the Factory/Bootcamp.

Reason: This repo is both Iwo's brain and the boilerplate he ships to others.

Tradeoff: Some generic boilerplate framing stays in the distributable files.

Review date: 2026-07-03
