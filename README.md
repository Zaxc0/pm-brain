# 🧠 PM Brain-as-Code

> **Your external product management brain. Single source of truth: latest commit.**

A living knowledge base that bridges the gap between PM frameworks and actual operational execution. Git-versioned, shareable, ready to use.

Product teams drown in blog posts and frameworks but still don’t know how to run sprint planning on Tuesday morning or write a PRD by end-of-day. This repo gives you battle-tested guides, templates, and playbooks — all wired into a coherent system.

- A junior PM asks “how do we prioritize this?”
- You need to run a sprint planning session in 30 minutes
- Leadership wants a product strategy doc by EOD
- You’re onboarding someone and don’t want to repeat yourself for the 47th time

**Single Source of Truth Principle:** The latest commit is always the current reality. No version confusion, no stale docs in Notion/Confluence that nobody updates.

**How to use it (two common paths):**

- **If you’re technically savvy and use GitHub + IDEs** (e.g. VS Code, Cursor, Replit, Claude Code, etc.):  
  - 🚀 Get started: clone the repo → plug in your company context → start shipping from this folder structure.  
  - Optionally point your IDE’s AI tools at this repo (or selected subfolders) as project context.

- **If you mostly use chat-based AI tools** (e.g. ChatGPT, Claude, Gemini):  
  - Browse to the folder you care about (company context, methods & tools, research artifacts, initiatives).  
  - Copy the relevant README + template you want to work with.  
  - Paste it into your AI session as “here’s the structure I use; help me fill/adapt it,” and reuse those templates across conversations.

- **🧭 Frameworks** – decision models and methods that actually help you choose what to do next.  
- **📋 Step-by-step operational guides** – checklists and how-tos for running key rituals and processes.  
- **📄 Copy-paste ready templates** – PRDs, one-pagers, roadmaps, comms, and more, ready to fill in.  
- **🚨 Scenario-based playbooks** – what to do when things go sideways: incidents, tough conversations, tradeoffs.  
- **🏢 Company context** – vision, strategy, principles, portfolio, roadmap, and stakeholders that don’t go stale.  
- **🤖 Prompt libraries** – reusable prompts for structured thinking with your own context in AI tools.  

---

## 🏗️ System Structure Philosophy

This is a **PM brain-as-code**, not a random notes folder. The directories represent different **types of work** and **layers of your product system**, not a rigid sequential process.

At the top level, you work across four main layers:

- **01-Company-Context**: Your **product and company brain** — strategy, vision, metrics, stakeholders, processes.  
- **02-Methods-and-Tools**: Your **PM operating system** — decision frameworks, operational guides, templates, playbooks, and prompts, organized by topic.  
- **03-Research-Artifacts**: Your **evidence layer** — interview notes, synthesis, research findings.  
- **04-Initiatives**: Your **bets and decisions** — early thinking, opportunity assessments, and initiative docs.

Around that core, you can add **optional layers**:

- **08-Prototypes**: Experiments and prototype implementations.  
- **09-Personal-Context**: Personal notes and development (typically kept in a private fork).  .

You can use this repo directly in git, or **bring parts of it into your favorite AI tools** (e.g. Cursor, Replit, VS Code extensions, hosted LLMs) by creating projects/workspaces there and uploading selected templates or context docs as reference. The recommended approach is to treat this repo as the **source of truth**, and copy only the pieces you need into other tools’ “project context” or “instructions” areas.

**Daily Work Flow:**
1. Reference `01-Company-Context/` for strategic direction and company information
2. Use `02-Methods-and-Tools/` when you need a process, framework, template, or playbook
3. Store research outputs in `03-Research-Artifacts/` after completing discovery work
4. Do your active product work in `04-Initiatives/` (planning, documenting, iterating)

---

## 📂 Project Structure (High-Level)

```text
pm-brain/
├── 01-Company-Context/        # 🏢 Strategic and company context (your private reality)
├── 02-Methods-and-Tools/      # 🧭 PM operating system (frameworks, guides, templates, playbooks, prompts)
├── 03-Research-Artifacts/     # 🔍 Research outputs and evidence
├── 04-Initiatives/            # 🚧 Active product bets & opportunity assessments
├── 08-Prototypes/             # 🧪 Prototype implementations and experiments
├── 09-Personal-Context/       # 🧑 Optional personal layer (usually private)
└── README.md                  # This file
```

### How Methods & Tools Fit Inside This Structure

Inside `02-Methods-and-Tools/`, content is organized by **domain** and numbered frameworks:

```text
02-Methods-and-Tools/
├── 2.1-Strategy/        # Strategy, OKRs, roadmap, PRDs, personas
├── 2.2-Communication/   # Stakeholder comms, courses, formats
├── 2.3-Discovery/       # Continuous discovery, JTBD, validation
└── 2.9-Other/           # Supporting methods & mental models
```

Examples:

- Product strategy sprint: `02-Methods-and-Tools/2.1-Strategy/2.1.1-Product-Strategy/`  
- OKR framework and templates: `02-Methods-and-Tools/2.1-Strategy/2.1.2-OKR/`  
- Roadmap framework and templates: `02-Methods-and-Tools/2.1-Strategy/2.1.3-Roadmap/`  
- PRD framework and templates: `02-Methods-and-Tools/2.1-Strategy/2.1.4-PRD/`  
- Personas framework and template: `02-Methods-and-Tools/2.1-Strategy/2.1.5-Personas/`  
- Newsletter framework and template: `02-Methods-and-Tools/2.2-Communication/2.2.1-Newsletter/`  
- Research interview guide: `02-Methods-and-Tools/2.3-Discovery/2.3.1-Research-Interviews/1-interview-guide.md`  
- Continuous discovery habits: `02-Methods-and-Tools/2.3-Discovery/2.3.2-Continuous-Discovery-Habits/`  
- JTBD framework: `02-Methods-and-Tools/2.3-Discovery/2.3.3-Jobs-To-Be-Done/`  
- Idea validation framework: `02-Methods-and-Tools/2.3-Discovery/2.3.4-Idea-Validation/`  

- **01-Company-Context** maps to the **`context/` layer** from the PM Brain idea (team structure, tech stack, metrics, processes), but as templates and structures you fill in privately.  
- **03-Research-Artifacts** holds the **evidence** your brain runs on.  
- **04-Initiatives** is where you **apply** the brain to real product work (opportunity assessments, initiative docs) using frameworks and templates from `02-Methods-and-Tools`.

## 🎓 Who This Is For

### Junior PMs (APMs, Associate PMs)

- **Actionable steps**: Not just “run user research” — here you’ll find actual interview guides, templates, and checklists.  
- **Process reminders**: Step-by-step guides so you don’t miss critical steps during planning, discovery, or delivery.  
- **Clear escalation paths**: Guidance on when to involve senior PMs, leadership, or other teams.

### Mid-Level PMs

- **Framework reference**: Quick access to prioritization models, strategy frameworks, and discovery patterns when stakeholders disagree.  
- **Template library**: Proven PRDs, one-pagers, and comms templates so you don’t reinvent the wheel.  
- **Stakeholder patterns**: Playbooks for managing expectations, saying no, and aligning teams.

### Senior PMs & Leads

- **Onboarding accelerator**: Point new hires at this system instead of repeating yourself in Slack and meetings.  
- **Team alignment**: Shared language, artifacts, and playbooks that reduce friction across teams.  
- **Knowledge preservation**: Your team’s operating system doesn’t walk out the door when someone leaves.

---

## 🚀 How to Use This System

### As a New Team Member

1. Start with `01-Company-Context/` to understand vision, strategy, and how decisions are made.  
2. Browse `02-Methods-and-Tools/` to see how the team approaches discovery, prioritization, and delivery.  
3. Bookmark key templates under `02-Methods-and-Tools/templates/` (PRDs, one-pagers, meeting agendas).  
4. Use `03-Research-Artifacts/` to study past interviews and findings before talking to customers.  
5. Use `04-Initiatives/` to understand what’s currently in-flight and how bets are documented.

### As an Experienced PM

1. Jump straight to `02-Methods-and-Tools/` for the topic you’re working on (e.g. PRDs, discovery, OKRs).  
2. Grab the relevant **framework + guide + template + playbook** from the folders there.  
3. Update or extend the framework when reality diverges from the theory — commit your improvements.  
4. Keep `01-Company-Context/` updated so newcomers can self-serve context.

### During Crisis or Time Pressure

1. Go to the relevant **playbooks** in `02-Methods-and-Tools/playbooks/` (e.g. incidents, rollbacks, major bugs).  
2. Use the connected **templates** (e.g. incident comms, stakeholder updates) to respond quickly.  
3. Log any new learnings in `03-Research-Artifacts/` or the relevant framework’s guides so the system improves.

---

## 📋 Quick Links

> These are example anchor points. In a fresh clone, some may be stubs you customize for your context.

### Most-Used Documents

- **Sprint Planning Guide**: `02-Methods-and-Tools/guides/planning/sprint-planning.md`  
- **PRD Template**: `02-Methods-and-Tools/templates/prds/standard-prd.md`  
- **Prioritization Framework (Value vs Effort)**: `02-Methods-and-Tools/frameworks/prioritization/value-vs-effort.md`  
- **Stakeholder Update Template**: `02-Methods-and-Tools/templates/comms/weekly-update.md`

### Emergency Playbooks

- **Product Incident Response**: `02-Methods-and-Tools/playbooks/crisis-management/incident-response.md`  
- **Feature Rollback Process**: `02-Methods-and-Tools/playbooks/crisis-management/rollback-process.md`  
- **Handling Major Bugs**: `02-Methods-and-Tools/playbooks/crisis-management/bug-triage.md`

### Onboarding Essentials

- **Team Structure & Roles Template**: `01-Company-Context/6-company-stakeholders.md`  
- **Decision-Making Framework & Decision Rights**: `01-Company-Context/README.md` (and related strategy docs)  
- **Key Metrics Glossary**: `01-Company-Context/5-company-roadmap.md` (or a dedicated metrics file you add)

---

## Key Features

### Structured Frameworks
- **11 Product Management Frameworks**: From strategy to execution, covering the complete product lifecycle
- **Decision Guide**: Quick reference to find the right framework for your situation
- **Templates & Examples**: Ready-to-use templates for common product management tasks
- **Mental Models**: Decision-making tools for strategic thinking and team alignment

### Company Context
- **Strategic Foundation**: Vision, strategy, principles, and roadmap documents
- **Product Portfolio**: Current products, services, and customer segments
- **Stakeholder Directory**: Key stakeholders and organizational structure
- **Placeholder Templates**: Generic templates ready to be customized

### Research & Discovery
- **Research Artifacts Storage**: Organized storage for interview notes, synthesis, and findings
- **Discovery Frameworks**: Systematic customer discovery and validation processes
- **Opportunity Assessment**: Template for early initiative thinking

### Personal Development
- **Personal Context**: Personal notes, learnings, and development goals
- **Career Planning**: Job search, assessments, and growth tracking

## Getting Started

### 1. Company Context
Start by reviewing and customizing documents in `01-Company-Context/`:
- Replace placeholder content with your company's actual vision, strategy, and principles
- Update product portfolio and stakeholder information
- See `01-Company-Context/README.md` for detailed guidance

### 2. Frameworks, Methods & Tools
Explore frameworks and methods in `02-Methods-and-Tools/`:
- Use the guide in `02-Methods-and-Tools/README.md` to find the right framework or tool
- Follow the flow: Early Thinking → Discovery → Define → Decide → Deliver → Launch & Learn
- Each framework includes usage guides and templates

### 3. Early Thinking
Document early ideas in `04-Initiatives/`:
- Use the opportunity assessment template for new initiatives
- Move to discovery frameworks when ready to validate
- See `04-Initiatives/README.md` for the complete process

### 4. Research
Store research outputs in `03-Research-Artifacts/`:
- See `02-Methods-and-Tools/2.3-Discovery/2.3.1-Research-Interviews/1-interview-guide.md` for guidelines on how to conduct interviews and principles
- Save interview notes, synthesis outputs, and research findings
- Link research artifacts to initiatives and PRDs
- See `03-Research-Artifacts/README.md` for organization guidelines

## How Frameworks Work Together

The frameworks follow a natural product development flow:

**0. Early Thinking** (`04-Initiatives/`) → Capture initial ideas and hypotheses

**1. Discover** (see discovery methods in `02-Methods-and-Tools/2.3-Discovery/` and related guides) → Interview users, observe behavior, collect stories

**2. Define** (e.g. JTBD in `02-Methods-and-Tools/2.3-Discovery/2.3.3-Jobs-To-Be-Done/`) → Frame problems as jobs and opportunities

**3. Decide** (e.g. idea validation in `02-Methods-and-Tools/2.3-Discovery/2.3.4-Idea-Validation/`) → Generate solutions and validate assumptions

**4. Deliver** (e.g. PRD templates in `02-Methods-and-Tools/2.1-Strategy/2.1.4-PRD/`) → Write requirements and build

**5. Launch & Learn** (e.g. OKR/roadmap methods in `02-Methods-and-Tools/2.1-Strategy/2.1.2-OKR/` and `2.1.3-Roadmap/`) → Measure outcomes and iterate

## Usage Guidelines

### Daily Work
1. **Morning Review**: Check current initiatives and priorities
2. **Framework Selection**: Use decision guide to find the right framework
3. **AI Assistance**: Leverage AI copilot for context-aware support
4. **Documentation**: Update relevant documents with new insights

### Product Development
1. **Start with Context**: Review company vision, strategy, and principles
2. **Early Thinking**: Document ideas in `04-Initiatives/`
3. **Discovery**: Use discovery frameworks to validate assumptions
4. **Define & Decide**: Frame problems and validate solutions
5. **Deliver**: Write PRDs and execute
6. **Learn**: Measure outcomes and iterate

### Continuous Improvement
1. **Regular Reviews**: Update company context and personal learnings
2. **Framework Refinement**: Improve processes based on experience
3. **Knowledge Sharing**: Share insights and best practices
4. **Template Updates**: Refine templates based on usage

## Directory Overview

### 01-Company-Context
Foundational documents that provide strategic direction. These should be the outcome of actual strategic work. See `01-Company-Context/README.md` for the complete structure and numbering logic.

### 02-Methods-and-Tools
Product management frameworks, guides, templates, playbooks, and prompts. See `02-Methods-and-Tools/README.md` for how to navigate and choose the right method for your situation.

### 03-Research-Artifacts
Storage for research outputs and artifacts from discovery activities. This is storage, not a process framework. See `03-Research-Artifacts/README.md` for organization guidelines.

### 04-Initiatives
Early thinking and opportunity assessment before you have evidence. Use the opportunity assessment template to document hypotheses. See `04-Initiatives/README.md` for the complete template and process.

***Optional***
### 08-Prototypes
Prototype implementations and experimental projects.

### 09-Personal-Context
Personal development notes, learnings, assessments, and career planning. In a public or shared repo, keep sensitive content in a private fork or private repo.



## Maintenance

### Living Document Principle

- **Update when you use it**: If you spot gaps or outdated steps while working, fix them in the repo.  
- **Let git be the changelog**: Use clear commit messages instead of separate change logs.  
- **Prefer improvements over TODOs**: Avoid permanent “TODO” sections — make the change or capture it in an issue/backlog file.

### Suggested Review Cadence

- **Weekly**: Update current initiatives and progress in `04-Initiatives/`.  
- **Monthly**: Review and update key frameworks, guides, and templates you touched.  
- **Quarterly**: Revisit `01-Company-Context/` (strategy, roadmap, OKRs).  
- **Annually**: Do a higher-level cleanup of folder structure and archive stale experiments.

---

## Contributing

This repository is designed as a **template PM operating system**. There are two main ways to use it:

1. **Fork and customize privately** (recommended for real company context).  
2. **Contribute improvements back** to the public template (for generic frameworks, guides, and patterns).

When contributing to this public repo:

1. **Maintain structure**: Follow the established folder and naming conventions.  
2. **Keep examples generic**: Don’t add proprietary or sensitive company information.  
3. **Document changes**: Use clear commit messages (what changed, why it changed, who it’s for).  
4. **Share learnings**: When you add a new guide or playbook, mention the scenarios it’s meant to handle.  
5. **Respect placeholders**: Use placeholders and comments where teams need to plug in their own context.

---

## License

This project is licensed under the **MIT License**. See `LICENSE` for details.
