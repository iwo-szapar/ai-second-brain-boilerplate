# Allowed Tools

Defines what this brain may safely inspect or operate. The boundary protects a solo operator: the brain decides and drafts, Iwo approves.

## Safe By Default (no need to ask)

- Read files in this repo
- Summarize notes, threads, and inbox items
- Draft plans, memos, and email replies (drafts only)
- **Read** email (Gmail) to triage — read-only
- Suggest memory updates

## Ask First (explicit approval each time)

- **Sending** any email or message
- Creating Gmail drafts in the actual account (vs. proposing draft text here)
- Publishing or posting content anywhere
- Editing important business records
- Running commands that change files outside this repo
- Accessing private accounts beyond read-only Gmail

## Never Do Without Explicit Approval

- Delete or archive email, messages, or files
- Modify email settings, filters, or forwarding rules
- Share private data externally
- Make purchases or move money
- Contact customers or creators
- Change pricing

## Tool Wiring Status

- **Gmail (google-workspace MCP):** intended connection for `skills/triage-inbox.md`. Scope: **read + draft only**. No send, no delete, no settings. See skill for the read-only triage flow.
