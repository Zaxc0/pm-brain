# Product Management Mental Models

This document distills essential mental models for product managers and data platform teams at [Company]. These frameworks offer practical tools to navigate common challenges—whether you're exploring new opportunities, scaling proven solutions, or aligning teams around outcomes. Use these models to clarify thinking, guide discussions, and drive better decisions at every stage of the product lifecycle.

**Note:** These are complementary decision-making tools that work alongside the process frameworks (2.1-2.10). Use mental models for strategic thinking and team alignment; use process frameworks for structured workflows.

## Pre-mortems

| Element | Type | Description | Purpose |
|---------|------|-------------|---------|
| **Initial Prompt** | Process | "Imagine this project has failed six months from now - what went wrong?" | Creates psychological safety to discuss potential failures |
| **Tigers** | Risk Category | Threats that will actually kill the project | Identify critical risks that must be mitigated |
| **Paper Tigers** | Risk Category | Seeming threats that aren't actually dangerous | Distinguish real vs. perceived risks |
| **Elephants** | Risk Category | Uncomfortable truths no one is discussing | Surface unspoken concerns and assumptions |

### Process Flow
1. **Gather team** early in project lifecycle
2. **Present failure scenario** using the prompt
3. **Categorize risks** into Tigers, Paper Tigers, Elephants
4. **Prioritize threats** voted on by team
5. **Create action plan** to address highest priority risks

## 60-30-10 Framework

| Allocation | Focus Area | Description | Examples |
|------------|------------|-------------|----------|
| **60%** | **Incrementals** | High-ROI features that improve users' daily experience | Bug fixes, UI improvements, small feature enhancements, performance optimizations |
| **30%** | **Big New Initiatives** | Major opportunities that could significantly change trajectory (1-2 initiatives max) | New product lines, major feature launches, platform rewrites, strategic pivots |
| **10%** | **Stability & Infrastructure** | Technical debt and foundational work | Code refactoring, security updates, tooling improvements, monitoring systems |

### Key Benefits
- Prevents roadmap from being filled entirely with quick wins
- Ensures dedicated time for high-impact opportunities
- Balances immediate needs with long-term strategic goals
- Forces prioritization of big initiatives (can't do 5 with only 30% allocation)

## The 3 Levels of Product Work

| Level | Focus | Typical Roles | Common Activities | Potential Issues |
|-------|-------|---------------|-------------------|------------------|
| **Impact** | Outcomes, customer experience, business results | Executives, CEOs, founders | Strategy discussions, customer impact analysis, business metrics | May miss execution realities |
| **Execution** | Delivery, milestones, getting things done | PMs, engineers, designers | Sprint planning, task management, bug fixes, feature delivery | May lose sight of bigger picture |
| **Optics** | Creating awareness and visibility | All roles (necessary function) | Status updates, presentations, documentation, communication | Can become the goal instead of means |

### Conflict Patterns
- **Impact vs Execution**: CEO asks "Why is customer service poor?" PM explains resource constraints
- **Execution vs Optics**: Team focused on delivery vs. stakeholders wanting visibility
- **Impact vs Optics**: Results-focused leaders vs. perception-focused team members

### Resolution Strategy
Use shared vocabulary to identify which level each person is operating at, then align on what's most important for the current context.

## Product 0-1 vs 1-100

| Stage      | Focus                | Key Activities                        | Success Metrics                | Common Pitfalls                |
|------------|----------------------|---------------------------------------|-------------------------------|-------------------------------|
| **0-1**    | Discovery & Fit      | User research, rapid prototyping, MVPs, hypothesis testing | User engagement, speed of learning, qualitative feedback | Over-engineering, skipping user validation, building for scale too early |
| **1-100**  | Scaling & Optimization | Performance, automation, process standardization, team specialization | Usage growth, system reliability, operational efficiency | Premature optimization, losing user focus, excessive complexity |

- **0-1:** "What should we build?" — Emphasize learning, user problems, and rapid iteration. Small, flexible teams validate assumptions before scaling.
- **1-100:** "How do we scale what works?" — Focus on execution, reliability, and efficiency. Specialized teams optimize and standardize proven solutions.
- **Key Insight:** Success depends on recognizing your stage and adapting team structure, metrics, and mindset accordingly.

## One-Way vs Two-Way Door Decisions

A mental model for matching decision-making speed and rigor to the reversibility of the decision.

| Type         | Description                        | Decision Process                | Examples (Data Platform)                |
|--------------|------------------------------------|----------------------------------|-----------------------------------------|
| **Two-Way**  | Reversible, low-cost to undo       | Decide quickly, experiment, empower teams | Tool selection, batch timing, alert thresholds |
| **One-Way**  | Hard/impossible to reverse, high impact | Slow down, analyze, consult widely | Cloud provider, core architecture, compliance standards |

- **Two-Way Doors:** Favor speed and experimentation. If it fails, you can easily reverse course.
- **One-Way Doors:** Require thorough analysis and broad alignment. Mistakes are costly or permanent.
- **Key Practice:** Always ask, "Is this a one-way or two-way door?"—then match your process to the risk.

## The Alignment Check

A simple diagnostic to surface hidden misalignment before it derails execution.

| Element | Description | Purpose |
|---------|-------------|---------|
| **Core Question** | "What are our top 3 priorities and how do we measure success?" | Reveals gaps between what people think they're working toward |
| **Expected Result** | Different definitions of success and timeframes | Exposes the real problem: everyone working hard in different directions |

### Warning Signs of Misalignment
- Multiple functional plans stapled together as "the plan"
- High effort, low meaningful output
- Team frustration despite individual hard work

### Process
1. **Ask each team member** the core question independently
2. **Compare responses** for consistency in priorities and success metrics
3. **Surface differences** openly in team discussion
4. **Align on shared definition** before proceeding with execution

**Key Insight:** Teams often assume they're aligned when they're not. This simple check prevents wasted effort on competing priorities.

## The Assumptions Framework

A diagnostic for understanding the root cause of product disagreements and building shared conviction.

| Element | Description | Purpose |
|---------|-------------|---------|
| **Core Principle** | "When two people disagree about product strategy, they have different assumptions" | Shifts focus from arguing solutions to aligning on underlying beliefs |
| **Assumption Mapping** | Identify what each person believes to be true about users, market, or constraints | Surface hidden differences in worldview |
| **Shared Foundation** | Align on key assumptions before debating solutions | Create basis for genuine agreement and conviction |

### Process Flow
1. **When disagreement occurs**, pause solution discussion
2. **Ask "What assumptions"** lead each person to their preferred approach
3. **Map differences** in beliefs about users, market, technical constraints
4. **Align or validate** assumptions through data, research, or testing
5. **Revisit solutions** once assumptions are shared

### Application Patterns

| Scenario | Assumption Check | Resolution Path |
|----------|------------------|-----------------|
| **Top-Down Strategy** | "What assumptions led leadership to this direction?" | Understand reasoning before building roadmap |
| **Bottom-Up Proposals** | "What do I assume that others might not?" | Ensure stakeholders share your foundational beliefs |
| **Team Misalignment** | "What different assumptions explain our different views?" | Surface and reconcile conflicting worldviews |

### Key Benefits
- Transforms arguments into productive assumption discussions
- Builds genuine conviction rather than compliance
- Reveals when disagreement is actually about facts vs. opinions
- Creates pathway to passionate execution through shared beliefs

**Key Insight:** Passionate execution flows naturally from shared assumptions. Focus on aligning beliefs, not just agreeing on tasks.

## Cross-Framework Navigation

- **Strategic Planning**: Use with `../../2.1-Strategy/2.1.1-Product-Strategy/` for strategy development
- **Team Alignment**: Use with `../../2.1-Strategy/2.1.2-OKR/` when setting objectives
- **Decision Making**: Use with `../../2.3-Discovery/2.3.4-Idea-Validation/` for validation decisions
- **Roadmap Planning**: Use with `../../2.1-Strategy/2.1.3-Roadmap/` for prioritization

