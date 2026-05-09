---
description: Suggest a possible PR title and description for the current changes
---

# Workflow

1. Look for intent in session history (prior messages, commits, linked issues).
2. If intent can be inferred from session history, proceed.
3. If intent cannot be inferred, ask **one** specific question before drafting.
4. Draft the PR title and description. Display it and ask the user if they want to create the PR.

# Rules

**Title:**
- Imperative mood: "Add", "Fix", "Refactor", "Update", "Extract"
- Start with a capital letter, no trailing period, one line
- Descriptive but concise

**Description:**
- Summary: 1-2 sentences at the top stating the change and why. State the change, not the implementation.
- NEVER fabricate intent. If the user declines to provide one, say so in the PR — don't invent one.
- NEVER list files. GitHub shows this already.
- NEVER narrate code changes. The diff shows the implementation.
- NEVER speculate on risks. Only mention risks the user explicitly raised.
- No separate "Why" section — the why lives in the summary.
- No "Testing" or "Verification" section.
