## Methods & Tools – The PM Operating System

This directory is the **core of the PM brain**: it contains the decision models, guides, templates, playbooks, and prompts you use every day.

Content here is organized primarily by **domain** (Strategy, Communication, Discovery, Other), and within each domain by **numbered frameworks**.

---

## Structure

```text
02-Methods-and-Tools/
├── 2.1-Strategy/            # Strategy, OKRs, roadmap, PRDs, personas
│   ├── 2.1.1-Product-Strategy/
│   ├── 2.1.2-OKR/
│   ├── 2.1.3-Roadmap/
│   ├── 2.1.4-PRD/
│   ├── 2.1.5-Personas/
│   ├── 2.1.6-North-Star/        # (placeholder)
│   └── 2.1.7-Prioritization/    # (placeholder)
├── 2.2-Communication/       # Stakeholder comms, courses, formats
│   ├── 2.2.1-Newsletter/
│   ├── 2.2.2-Meeting-Agendas/   # (placeholder)
│   ├── 2.2.3-One-Pagers/        # (placeholder)
│   ├── 2.2.4-Crisis-Management/ # (placeholder)
│   └── 2.2.9-Courses/
├── 2.3-Discovery/           # Continuous discovery, JTBD, validation
│   ├── 2.3.1-Research-Interviews/
│   ├── 2.3.2-Continuous-Discovery-Habits/
│   ├── 2.3.3-Jobs-To-Be-Done/
│   └── 2.3.4-Idea-Validation/
└── 2.9-Other/               # Supporting methods & mental models
    └── 2.9.1-Mental-Models/
```

Inside each numbered framework folder (e.g. `2.3.2-Continuous-Discovery-Habits/`), files are usually numbered:

- `1-...` for the main framework or guide  
- `2-...`, `3-...`, etc. for templates, steps, or evaluations  

---

## When to use what

- **2.1-Strategy/** – When you need to **set direction or plan**:  
  - Vision & strategy, OKRs, roadmap, PRDs, personas, north star, prioritization.
- **2.2-Communication/** – When you need to **communicate or train**:  
  - Stakeholder newsletters, courses, (future) crisis comms, one-pagers, formats.
- **2.3-Discovery/** – When you need to **learn from customers or validate ideas**:  
  - Research interviews, continuous discovery habits, JTBD, idea validation.
- **2.9-Other/** – When you need **supporting tools and mental models**:  
  - Decision-making models and other cross-cutting methods.

---

## Typical navigation examples

- **Prioritizing a backlog**
  - Start in `2.1-Strategy/2.1.7-Prioritization/` (when populated) or `2.3-Discovery/2.3.4-Idea-Validation/`.  
  - Use a decision log in your initiative folder under `04-Initiatives/`.

- **Running discovery**
  - Read `2.3-Discovery/2.3.1-Research-Interviews/1-interview-guide.md`.  
  - Use `2.3-Discovery/2.3.2-Continuous-Discovery-Habits/1-4-*.md` to snapshot, synthesize, create opportunities, and generate solutions.  
  - Save raw notes and synthesis outputs in `03-Research-Artifacts/`.

- **Writing a PRD**
  - Skim `2.1-Strategy/2.1.4-PRD/1-prd-framework.md`.  
  - Copy `2.1-Strategy/2.1.4-PRD/2-prd-template.md` or `3-prd-jtbd-template.md` and fill it in.  
  - Link back to discovery artifacts in `03-Research-Artifacts/` and initiatives in `04-Initiatives/`.

As you adapt these to your team, keep this structure but tune the content to match your reality.

---

## Quick start: self-quiz + AI collaboration for methods

Use this prompt to figure out **where to start in `02-Methods-and-Tools/`** when you’re not sure which framework to use:

```markdown
Act as a product management coach. We'll work iteratively and challenge assumptions.

1) First, help me locate the right area in this repo:
- Ask what I'm trying to do right now (e.g. shape strategy, plan roadmap, write PRD, run discovery, validate an idea, communicate to stakeholders).
- Based on my answer, propose 1–3 starting points under `02-Methods-and-Tools/` using this structure:
  - 2.1-Strategy (2.1.1-Product-Strategy, 2.1.2-OKR, 2.1.3-Roadmap, 2.1.4-PRD, 2.1.5-Personas, 2.1.6-North-Star, 2.1.7-Prioritization)
  - 2.2-Communication (2.2.1-Newsletter, 2.2.2-Meeting-Agendas, 2.2.3-One-Pagers, 2.2.4-Crisis-Management, 2.2.9-Courses)
  - 2.3-Discovery (2.3.1-Research-Interviews, 2.3.2-Continuous-Discovery-Habits, 2.3.3-Jobs-To-Be-Done, 2.3.4-Idea-Validation)
  - 2.9-Other (2.9.1-Mental-Models)

2) For the chosen starting framework:
- Ask me to paste any relevant notes or context (initiative, customer segment, current docs).
- Summarize which parts of the framework I’ve already covered vs what’s missing.
- Suggest the next 1–3 concrete steps (e.g. "fill out this template", "run these interviews", "write this PRD section") with file paths in this repo.

3) At the end of each pass:
- List: (a) the framework files I should touch next, (b) which repo directory to update in `04-Initiatives/` or `03-Research-Artifacts/`, and (c) any risks or open questions to track.

I'll start by telling you what I'm working on right now.
```


