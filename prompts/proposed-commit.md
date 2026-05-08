---
description: Suggest a commit title and message for the current changes following Basecamp's style
---

# Workflow

1. Read the guidelines
2. Suggest a commit title and message for the current changes following the guidelines
3. Ask the user if they want to create a commit with this message

# Guidelines

**Title (Required):**
- Use imperative mood (present tense, as a command): "Add", "Fix", "Refactor", "Update", "Ensure", "Move", "Extract", etc.
- Start with a capital letter
- No trailing period
- Keep to one line
- Make it descriptive but concise — context matters, but brevity is valued

**Body (Discouraged unless absolutely necessary):**
- Do NOT include a body unless it's absolutely required to explain a non-obvious "why"
- First, try making the title clearer instead
- Only use body for: architectural decisions, critical workarounds, migration steps, or performance implications that cannot fit in the title
- Most commits should be title-only — a clear, complete title is the standard

**Do NOT:**
- Use past tense ("Added", "Fixed")
- Capitalize every word ("Add Feature" → "Add feature")
- Add trailing period
- Add multi-line without clear separation

**Example strong titles:**
- "Capture Date.current once before travel_to to avoid boundary races"
- "Extract FileTypeable concern from Upload"
- "Speed up file type filtering on everything/files"
- "Ensure recording Esc handler only fires if the extension is recording"
