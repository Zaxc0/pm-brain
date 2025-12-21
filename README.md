# 🧠 PM Brain-as-Code

> **Your external product management brain. Single source of truth: latest commit.**

Product teams drown in blog posts and frameworks but still don't know **how to actually do the work**. A junior PM asks "how do we prioritize this?" — no clear answer. You need to run sprint planning in 30 minutes — no process doc. Leadership wants a product strategy by EOD — you start from scratch. You're onboarding someone — repeating yourself for the 47th time.

**Frameworks are everywhere. Operational execution guides are not.**

This repo bridges that gap with a living, git-versioned knowledge base that gives you battle-tested guides, templates, and playbooks — all wired into a coherent system:

- **🧭 Frameworks** – decision models and methods that actually help you choose what to do next  
- **📋 Step-by-step guides** – checklists and how-tos for running key rituals and processes  
- **📄 Copy-paste templates** – PRDs, one-pagers, roadmaps, comms, and more, ready to fill in  
- **🚨 Scenario playbooks** – what to do when things go sideways (incidents, tough conversations, tradeoffs)  
- **🏢 Company context** – vision, strategy, principles, portfolio, roadmap, and stakeholders that don't go stale  
- **🤖 Prompt libraries** – reusable prompts for structured thinking with AI tools (ChatGPT, Claude, Gemini, GitHub Copilot, Cursor, etc.)

**Single Source of Truth Principle:** The latest commit is always the current reality. No version confusion, no stale docs in Notion or Confluence that nobody updates.  

---

## 🚀 How to Get Started

### Option 1: Manual (Copy-Paste into AI Tools)

**Best for:** Quick use with ChatGPT, Claude, Gemini, Microsoft Copilot, or other chat-based AI tools.

1. **Browse** to the folder you need:
   - `01-Company-Context/` – for company strategy, vision, stakeholders
   - `02-Methods-and-Tools/` – for frameworks, guides, templates, playbooks
   - `03-Research-Artifacts/` – for research storage structure
   - `04-Initiatives/` – for opportunity assessments and initiative planning

2. **Copy** the relevant README + template files.

3. **Paste** into your AI chat session with a prompt like:
   ```
   Here's the structure I use for [product strategy / PRDs / OKRs / etc.].
   Help me fill it out / adapt it for [my context].
   ```
4. **Save for reuse** (optional but recommended):
   - Upload the template files to your AI tool's project/workspace feature (e.g., ChatGPT's "My GPTs", Claude's "Projects", or similar)
   - Or save the conversation/context so you can reference it in future sessions
   - This lets you reuse templates without copying/pasting each time

5. **Reuse** those templates across conversations.

### Option 2: Technical (Clone & Use with IDE AI Tools)

**Best for:** GitHub users with VS Code, Cursor, GitHub Copilot, Replit, or similar IDE AI tools.

1. **Clone** the repo:
   ```bash
   git clone https://github.com/andreaskelm/pm-brain.git
   cd pm-brain
   ```

2. **Plug in your company context**:
   - Replace placeholders in `01-Company-Context/` with your actual vision, strategy, principles, etc.
   - Customize templates in `02-Methods-and-Tools/` for your team's workflows.

3. **Start shipping** from this folder structure:
   - Use frameworks and guides in `02-Methods-and-Tools/` for daily work.
   - Store research in `03-Research-Artifacts/`.
   - Document initiatives in `04-Initiatives/`.

4. **Optional:** Point your IDE's AI tools (Cursor, GitHub Copilot, etc.) at this repo or specific subfolders as project context for AI-assisted work.

---

## 🏗️ System Structure Philosophy

This is a **PM brain-as-code**, not a random notes folder. The directories represent different **types of work** and **layers of your product system**, not a rigid sequential process.

### Four Core Layers

```text
pm-brain/
├── 01-Company-Context/        # 🏢 Strategic foundation (vision, strategy, metrics, stakeholders)
├── 02-Methods-and-Tools/      # 🧭 PM operating system (frameworks, guides, templates, prompts)
├── 03-Research-Artifacts/     # 🔍 Evidence layer (interview notes, synthesis, findings)
└── 04-Initiatives/            # 🚧 Active bets (early thinking, opportunity assessments, docs)
```

### Optional Layers

```text
├── 08-Prototypes/             # 🧪 Experiments and prototype implementations
└── 09-Personal-Context/       # 🧑 Personal notes (keep sensitive content in private fork)
```

### Daily Workflow

1. **Reference** `01-Company-Context/` for strategic direction and company information.
2. **Use** `02-Methods-and-Tools/` when you need a process, framework, template, or playbook.
3. **Store** research outputs in `03-Research-Artifacts/` after completing discovery work.
4. **Do** your active product work in `04-Initiatives/` (planning, documenting, iterating).

---

## 📂 What's Inside `02-Methods-and-Tools/`

Content is organized by **domain** and **numbered frameworks**:

```text
02-Methods-and-Tools/
├── 2.1-Strategy/            # Strategy, OKRs, roadmaps, PRDs, personas
│   ├── 2.1.1-Product-Strategy/
│   ├── 2.1.2-OKR/
│   ├── 2.1.3-Roadmap/
│   ├── 2.1.4-PRD/
│   ├── 2.1.5-Personas/
│   ├── 2.1.6-North-Star/        (placeholder)
│   └── 2.1.7-Prioritization/    (placeholder)
├── 2.2-Communication/       # Newsletters, stakeholder comms, courses
│   ├── 2.2.1-Newsletter/
│   ├── 2.2.2-Meeting-Agendas/   (placeholder)
│   ├── 2.2.3-One-Pagers/        (placeholder)
│   ├── 2.2.4-Crisis-Management/ (placeholder)
│   └── 2.2.9-Courses/
├── 2.3-Discovery/           # Continuous discovery, JTBD, validation
│   ├── 2.3.1-Research-Interviews/
│   ├── 2.3.2-Continuous-Discovery-Habits/
│   ├── 2.3.3-Jobs-To-Be-Done/
│   └── 2.3.4-Idea-Validation/
└── 2.9-Other/               # Mental models and supporting methods
    └── 2.9.1-Mental-Models/
```

**Key examples:**
- Product strategy sprint: `02-Methods-and-Tools/2.1-Strategy/2.1.1-Product-Strategy/`
- OKR framework & templates: `02-Methods-and-Tools/2.1-Strategy/2.1.2-OKR/`
- PRD framework & templates: `02-Methods-and-Tools/2.1-Strategy/2.1.4-PRD/`
- Research interview guide: `02-Methods-and-Tools/2.3-Discovery/2.3.1-Research-Interviews/1-interview-guide.md`
- Continuous discovery habits: `02-Methods-and-Tools/2.3-Discovery/2.3.2-Continuous-Discovery-Habits/`
- Jobs-to-be-Done: `02-Methods-and-Tools/2.3-Discovery/2.3.3-Jobs-To-Be-Done/`
- Idea validation: `02-Methods-and-Tools/2.3-Discovery/2.3.4-Idea-Validation/`

See `02-Methods-and-Tools/README.md` for a complete guide on choosing the right method for your situation.

---

## 🎓 Who This Is For

### Junior PMs (APMs, Associate PMs)

- **Actionable steps**: Not just "run user research" — actual interview guides, templates, and checklists.
- **Process reminders**: Step-by-step guides so you don't miss critical steps during planning, discovery, or delivery.
- **Clear escalation paths**: Guidance on when to involve senior PMs, leadership, or other teams.

### Mid-Level PMs

- **Framework reference**: Quick access to prioritization models, strategy frameworks, and discovery patterns when stakeholders disagree.
- **Template library**: Proven PRDs, one-pagers, and communication templates so you don't reinvent the wheel.
- **Stakeholder patterns**: Guides for managing expectations, saying no, and aligning teams.

### Senior PMs & Leads

- **Onboarding accelerator**: Point new hires at this system instead of repeating yourself in Slack and meetings.
- **Team alignment**: Shared language, artifacts, and guides that reduce friction across teams.
- **Knowledge preservation**: Your team's operating system doesn't walk out the door when someone leaves.

---

## 🔄 How Frameworks Work Together

The frameworks follow a natural product development flow:

**0. Early Thinking** (`04-Initiatives/`) → Capture initial ideas and hypotheses

**1. Discover** (`02-Methods-and-Tools/2.3-Discovery/`) → Interview users, observe behavior, collect stories

**2. Define** (`02-Methods-and-Tools/2.3-Discovery/2.3.3-Jobs-To-Be-Done/`) → Frame problems as jobs and opportunities

**3. Decide** (`02-Methods-and-Tools/2.3-Discovery/2.3.4-Idea-Validation/`) → Generate solutions and validate assumptions

**4. Deliver** (`02-Methods-and-Tools/2.1-Strategy/2.1.4-PRD/`) → Write requirements and build

**5. Launch & Learn** (`02-Methods-and-Tools/2.1-Strategy/2.1.2-OKR/` and `2.1.3-Roadmap/`) → Measure outcomes and iterate

---

## 📋 Quick Start Guides

### As a New Team Member

1. Start with `01-Company-Context/` to understand vision, strategy, and how decisions are made.
2. Browse `02-Methods-and-Tools/` to see how the team approaches discovery, prioritization, and delivery.
3. Study past research in `03-Research-Artifacts/` before talking to customers.
4. Review `04-Initiatives/` to understand what's currently in-flight and how bets are documented.

### As an Experienced PM

1. Jump straight to `02-Methods-and-Tools/` for the topic you're working on (e.g., PRDs, discovery, OKRs).
2. Grab the relevant **framework + guide + template** from the folders there.
3. Update or extend the framework when reality diverges from theory — commit your improvements.
4. Keep `01-Company-Context/` updated so newcomers can self-serve context.

### During Crisis or Time Pressure

1. Go to the relevant framework in `02-Methods-and-Tools/` (e.g., `2.2-Communication/2.2.4-Crisis-Management/` for incidents).
2. Use the connected guides and templates to respond quickly.
3. Log any new learnings in the relevant framework's guides so the system improves.

---

## 📁 Directory Overview

### 01-Company-Context
Foundational documents that provide strategic direction. These should be the outcome of actual strategic work. See `01-Company-Context/README.md` for the complete structure and numbering logic.

### 02-Methods-and-Tools
Product management frameworks, guides, templates, playbooks, and prompts. See `02-Methods-and-Tools/README.md` for how to navigate and choose the right method for your situation.

### 03-Research-Artifacts
Storage for research outputs and artifacts from discovery activities. This is storage, not a process framework. See `03-Research-Artifacts/README.md` for organization guidelines.

### 04-Initiatives
Early thinking and opportunity assessment before you have evidence. Use the opportunity assessment template to document hypotheses. See `04-Initiatives/README.md` for the complete template and process.

### 08-Prototypes *(optional)*
Prototype implementations and experimental projects.

### 09-Personal-Context *(optional)*
Personal development notes, learnings, assessments, and career planning. In a public or shared repo, keep sensitive content in a private fork or private repo.

---

## 🔧 Maintenance

### Living Document Principle

- **Update when you use it**: If you spot gaps or outdated steps while working, fix them in the repo.
- **Let git be the changelog**: Use clear commit messages instead of separate change logs.
- **Prefer improvements over TODOs**: Avoid permanent "TODO" sections — make the change or capture it in an issue/backlog file.

### Suggested Review Cadence

- **Weekly**: Update current initiatives and progress in `04-Initiatives/`.
- **Monthly**: Review and update key frameworks, guides, and templates you touched.
- **Quarterly**: Revisit `01-Company-Context/` (strategy, roadmap, OKRs).
- **Annually**: Do a higher-level cleanup of folder structure and archive stale experiments.

---

## 🤝 Contributing

This repository is designed as a **template PM operating system**. There are two main ways to use it:

1. **Fork and customize privately** (recommended for real company context).
2. **Contribute improvements back** to the public template (for generic frameworks, guides, and patterns).

When contributing to this public repo:

1. **Maintain structure**: Follow the established folder and naming conventions.
2. **Keep examples generic**: Don't add proprietary or sensitive company information.
3. **Document changes**: Use clear commit messages (what changed, why it changed, who it's for).
4. **Share learnings**: When you add a new guide or playbook, mention the scenarios it's meant to handle.
5. **Respect placeholders**: Use placeholders and comments where teams need to plug in their own context.

---

*⭐ Star this repo if you find it useful • 🔀 Fork it to customize for your team*

---

## 📄 License

This project is licensed under the **MIT License**. See `LICENSE` for details.
