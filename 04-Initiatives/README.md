# Initiatives — Early Thinking & Opportunity Assessment

## Introduction

This directory is your starting point for capturing early initiative thinking before you have evidence. Use the opportunity assessment template to document hypotheses, assumptions, and initial ideas. Once you have enough clarity, move to the discovery frameworks in `../02-Methods-and-Tools/frameworks/discovery/` to validate your thinking with evidence.

**This is for:** Early ideas, hypotheses, and initial opportunity assessments  
**When ready:** Move to discovery methods in `../02-Methods-and-Tools/frameworks/discovery/` for evidence-based discovery

## How This Relates to Frameworks

**Early Thinking (This Directory):**
- Capture initial ideas and hypotheses
- Document what you know vs. what needs research
- Identify key questions to validate

**Discovery Frameworks (`../02-Methods-and-Tools/`):**
- Validate assumptions with user interviews (see `guides/research/`)
- Synthesize patterns from evidence (see `templates/research/`)
- Create evidence-based opportunities (see `frameworks/discovery/`)
- Generate and validate solutions (see `frameworks/prioritization/` and validation guides)
- Write PRDs (see `templates/prds/`)

**The Flow:**
1. Start here with opportunity assessment (early thinking)
2. Move to discovery frameworks when ready to validate
3. Return here to document your actual initiative as it evolves

## How to Use This Directory

1. Create a new initiative folder when you have an early idea
2. Use the opportunity assessment template to document your thinking
3. Identify what needs validation (move to discovery frameworks)
4. As you learn, update the opportunity assessment
5. When validated, create PRD and roadmap documents

## Quick start: self-quiz + AI collaboration

Use this to get unstuck fast, challenge assumptions, and move from thoughts → evidence → decisions.

- How it works:
  - You paste the prompt below into the model.
  - You paste your latest notes.
  - The model quizzes you section-by-section, fills gaps, and challenges assumptions.
  - You iterate until confident enough to move into a PRD/roadmap.

### Reusable prompt (copy-paste)

```markdown
Act as a product management coach for [you] at [company]. We’ll work iteratively and challenge assumptions. Keep mixed language 
if I write in Danish/English; translate critical highlights to English.

1) Quiz me section-by-section on:
- Objective
- Target customer
- Success metrics
- What we know
- What we should research
- Solution ideas
- Risks and questions to validate
- Next steps
- Links & artifacts

2) For each section:
- Ask 3–7 sharp questions.
- Propose initial draft answers based on my notes; clearly mark gaps as [to fill].
- Challenge assumptions and call out confidence (High/Med/Low).
- Suggest 1–3 fast experiments or research tasks with effort/impact.
- Keep answers concise and skimmable.

3) End each pass with:
- Updated section summaries
- Top 3 decision points
- Next 3 actions with owners/dates placeholders
- A minimal decision log entry if we made a call

I’ll paste my notes now. Start with “Objective”.
```

### How to use it
1) Paste the prompt. 2) Paste your current notes. 3) Answer questions; ask for revisions. 4) When stable, copy outputs into this README’s template or `prd.md`.

---

## What to include in each initiative folder

Use a lightweight but consistent structure. Add/remove to fit scope.

```text
pm-brain/04-Initiatives/
  [INIT-CODE]/
    opportunity-assessment.md  # Opportunity assessment (this template)
    summary.md                 # 1-pager exec summary
    prd.md                     # Full PRD (when ready)
    roadmap.md                 # Milestones/timeline
    decisions.md               # Decision log (date, context, decision, owner)
    risks.md                   # Key risks + mitigations
    research/
      interviews/              # Notes, transcripts, insights
      data/                    # Queries, datasets, charts
      experiments/             # Hypotheses, plans, results
    stakeholders/
      insights.md              # Who cares, needs, influence
      comms.md                 # Cadence, updates, audiences
    metrics/
      north-star.md            # Metrics tree, targets, guardrails
      dashboard-links.md       # BI links, definitions
    compliance/                # Regulatory, audit, approvals
    architecture/              # Diagrams, integration points
    retrospective.md           # Post-mortem after major phase
    lessons-learned.md         # Reusable learnings
    assets/                    # Visuals (SVG only)
```

- Recommended docs:
  - opportunity-assessment.md: living opportunity assessment.
  - summary.md: narrative and key numbers for execs.
  - prd.md: scope, requirements, acceptance criteria.
  - roadmap.md: milestones, dependencies, risks.
  - decisions.md: one-line entries; link to context.
  - research/*: interviews, analysis, experiment logs.
  - stakeholders/*: map, comms plan.
  - metrics/*: targets, dashboards, definitions.
  - compliance/, architecture/: use as needed.
  - retrospective.md, lessons-learned.md: after major delivery.

---

## How to Use This Template

1. **Start Early**: Create opportunity assessment when you have an initial idea or hypothesis
2. **Document What You Know**: Fill out sections with current knowledge; mark unknowns explicitly
3. **Identify Research Needs**: Use "What we should research" section to plan validation
4. **Move to Discovery**: When ready, use discovery methods in `../02-Methods-and-Tools/frameworks/discovery/` (and related guides/templates) to validate assumptions
5. **Update as You Learn**: Return to update opportunity assessment with new evidence
6. **Transition to Execution**: When validated, create PRD using templates in `../02-Methods-and-Tools/templates/prds/` and roadmap documents

## How to Maintain

- **Weekly Updates**: Update as you learn new information or make decisions
- **After Discovery**: Update with evidence from interviews and research
- **After Validation**: Update with validation results and next steps
- **Archive**: Move completed initiatives to archive or mark as complete

---

## Opportunity Assessment Template

# [Initiative Working Title]

## Objective
- What outcome are we trying to achieve and why now?
- Business value hypothesis (e.g., revenue, risk reduction, cost, speed).
- Time horizon and exit criteria (what “good” looks like).

## Target customer
- Primary customer/user segment and context (JTBD, key workflows).
- Stakeholders impacted (internal/external) and success definition for each.
- Where/how we’ll reach them (channels, touchpoints).

## Success metrics
- Leading indicators:
  - [Metric] — baseline: [x], target: [y] by [date]
- Lagging outcomes:
  - [Metric] — baseline: [x], target: [y] by [date]
- Guardrails (e.g., compliance, risk appetite, experience thresholds).

## What we know
- Facts and evidence (link sources: data, interviews, prior initiatives).
- Constraints (regulatory, technical, operational, capacity).
- Assumptions with confidence level (e.g., High/Med/Low).

## What we should research
- Key questions/hypotheses to validate.
- Methods (interviews, data analysis, discovery experiments, prototypes).
- Participants, sample size, and timeline.
- Decision criteria (what would change our mind; kill/pivot/commit thresholds).

## Solution ideas
- Concept 1: [one-liner] — first slice MVP scope.
- Concept 2: [one-liner] — alternative approach.
- Out of scope (for now) to protect focus.

## Risks and questions to validate
- Desirability (customer value, adoption risks).
- Viability (commercial model, business impact, go-to-market).
- Feasibility/Tech (integration, scalability, data availability).
- Usability (flow, UX, accessibility).
- Compliance/Legal (market rules, privacy, auditability).
- Dependencies (teams, vendors, data sources, timelines).
- Unknowns/Red flags and how we’ll de-risk.

## Next steps
- [Owner] → [action] by [date]
- [Owner] → [action] by [date]

## Links & artifacts
- Research notes: [...]
- Data/dashboard: [...]
- Stakeholders & comms rhythm: [...]
- Decision log: [...]