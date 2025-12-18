## `.cursor/rules` – Workspace Rules Overview

This directory contains **rule files** that tell the AI how to behave in this workspace. They are **local to this repo** and can be tailored to your work style and projects.

### What these files are

- `thinking.mdc` – General “how to think with me” instructions for the AI (e.g. coaching style, language handling, focus areas).  
- `thinking.personal.mdc` – **Template** for your personal context: name (or alias), working style, preferences. You should fill this with your own information (or keep it blank) and avoid committing sensitive details to public repos.  
- `AGENTS.md` – Template for defining custom AI “agents” (roles) for this workspace.  

> **Important:** These files are meant to describe *how* you want the AI to work with you – not to store confidential business data. Keep actual private/company information in regular project files that are not shared publicly.

### When and how rules are applied

- Rules in `thinking.mdc` can be referenced whenever you ask for:
  - Strategic thinking, coaching, or decision support
  - Help structuring work (roadmaps, OKRs, discovery, PRDs, etc.)
  - Help synthesizing notes, research, or stakeholder input
- `thinking.personal.mdc` is used **only** to adapt tone, pacing, and structure to your preferences (e.g. more bullets, slower pacing, more probing questions).
- `AGENTS.md` can define multiple “personas” or roles (e.g. Product Coach, Architect, Research Partner) that you can invoke explicitly in prompts.

### Quick start: set up your rules

You can use the prompt below to have the AI help you configure these rule files:

```markdown
Act as a workspace setup coach. I want to configure `.cursor/rules` for this repo.

1) Ask me:
- What kind of work I mostly do here (e.g. product, engineering, research, writing, coding).
- How I like to work (e.g. lots of structure vs. loose exploration, written vs. spoken style).
- Any accessibility or neurodiversity considerations I want you to adapt to.

2) Help me fill out or adjust:
- `thinking.mdc`: high-level description of how I want the AI to think and support me.
- `thinking.personal.mdc`: my working preferences and communication style (keeping sensitive details minimal or private).
- `AGENTS.md`: 1–3 agents/roles that would be genuinely useful for this repo.

3) Propose:
- A short checklist for keeping these rules up to date.
- Any safeguards I should consider so private/company information doesn’t leak into public repos.

I'll start by telling you what I use this repo for and how I like to work.
```

### Using these rules across tools

- In **Cursor**, this `.cursor/rules` folder is read automatically; update these files and commit them to keep behavior consistent across collaborators.  
- In other tools (e.g. **Replit**, **VS Code + AI extensions**), you can **reuse the same content** by:
  - Copying relevant sections from `thinking.mdc`, `thinking.personal.mdc`, and `AGENTS.md` into those tools’ “system prompt” / “instructions” / “workspace settings” areas.  
  - Keeping this folder as the **single source of truth**, and pasting updated snippets into other IDEs when needed.
- If you adopt multiple IDEs, consider adding a short “Where I use these rules” note here with links or notes for each environment (Cursor, Replit, VS Code, etc.).
