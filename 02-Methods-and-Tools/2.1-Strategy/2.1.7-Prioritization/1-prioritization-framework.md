# Product Prioritization Framework

## Overview

This framework helps product teams make systematic decisions about what to build next. Prioritization is NOT about pleasing everyone—it’s about maximizing value delivery with limited resources.

## Core Philosophy

### Prioritization is NOT Guesswork

Effective prioritization should:

- **Drive strategic focus over tactical firefighting** - Align work to goals, not just urgency
- **Reduce bias over gut feelings** - Use data and frameworks, not HiPPO (Highest Paid Person’s Opinion)
- **Increase transparency over politics** - Make decisions defensible and repeatable
- **Enable team autonomy over micromanagement** - Teams understand the “why” behind priorities

### Understanding Prioritization Dimensions

Every initiative can be evaluated across multiple dimensions:

- **VALUE ←→ EFFORT** - What you gain vs. what it costs
- **CERTAINTY ←→ RISK** - Confidence in estimates and outcomes
- **STRATEGIC ←→ TACTICAL** - Long-term positioning vs. short-term needs
- **BROAD ←→ NARROW** - How many users/customers affected

## Framework Structure

### 1. Header Section

Always include:

- **Disclaimer** - “Priorities reflect current strategy and will shift as we learn”
- **Prioritization method** - Which framework(s) are you using?
- **Last prioritization date**
- **Next review date**
- **Decision owner**

### 2. Prioritization Methods

**RICE Scoring (Comprehensive)**

- Best for: Feature development, product roadmaps
- Factors: Reach, Impact, Confidence, Effort
- Time investment: Medium to high
- Bias reduction: High

**ICE Scoring (Quick & Simple)**

- Best for: Growth experiments, rapid testing
- Factors: Impact, Confidence, Ease
- Time investment: Low
- Bias reduction: Medium

**Effort-Impact Matrix (Visual)**

- Best for: Workshops, stakeholder alignment
- Factors: Impact (value) vs. Effort (cost)
- Time investment: Low
- Bias reduction: Low to medium

**Value vs. Complexity (Strategic)**

- Best for: Long-term planning, portfolio decisions
- Factors: Business value vs. Technical complexity
- Time investment: Medium
- Bias reduction: Medium

### 3. Responsibility Assignment (RACI)

**Use when:**

- Multiple stakeholders involved
- Unclear ownership causing delays
- Cross-functional dependencies
- Need decision clarity

**Structure:**

- R = Responsible (does the work)
- A = Accountable (owns the outcome)
- C = Consulted (provides input)
- I = Informed (kept in the loop)

### 4. Decision Criteria

Define what matters most:

- Strategic alignment (does this support our strategy?)
- Customer value (does this solve a real problem?)
- Business impact (does this move key metrics?)
- Technical feasibility (can we actually build this?)
- Resource availability (do we have capacity?)

## Writing Guidelines

### Initiative Names

- ✅ “Add multi-factor authentication for enterprise users”
- ✅ “Redesign checkout flow to reduce abandonment”
- ✅ “Build API integration with Salesforce”
- ❌ “Security improvements”
- ❌ “Better UX”
- ❌ “Technical debt”

### Scoring Rationale

- ✅ “Reach: 5,000 enterprise users × 90% adoption = 4,500/quarter”
- ✅ “Impact: 3x (massive) - Directly addresses #1 churn reason”
- ✅ “Effort: 4 person-months based on engineering estimate”
- ❌ “This seems important”
- ❌ “High impact”
- ❌ “Won’t take long”

### Priority Decisions

- ✅ “Prioritized due to RICE score of 625 and strategic alignment with enterprise expansion”
- ✅ “Deprioritized despite stakeholder interest due to low reach (50 users) and high effort (8 person-months)”
- ❌ “Leadership wants this”
- ❌ “Competitors have it”

## Review Schedule

### Weekly Check-ins (Active Work)

- Progress on prioritized initiatives
- Blockers and impediments
- Quick wins or deprioritization needs

### Bi-weekly Backlog Grooming

- Score new ideas
- Re-evaluate scores based on learnings
- Remove obsolete items

### Monthly Strategic Review

- Portfolio balance check
- Resource allocation
- Stakeholder alignment

### Quarterly Planning

- Full re-prioritization
- Strategy alignment check
- Capacity planning
- Major initiative sequencing

## Stakeholder Communication

### For Leadership

- Focus on strategic initiatives and business impact
- Show portfolio balance (quick wins vs. big bets)
- Highlight trade-offs and opportunity costs
- Use scores to defend decisions

### For Product Teams

- Emphasize customer value and impact
- Connect work to metrics and outcomes
- Show how initiatives ladder up to strategy
- Make scoring transparent and participatory

### For Engineering Teams

- Provide technical context and effort estimates
- Show why high-effort items are worth it
- Balance innovation with maintenance
- Make dependencies visible

### For Customer-Facing Teams

- Connect priorities to customer pain points
- Share timeline expectations
- Explain what’s NOT being built and why
- Gather input for future prioritization

## Common Challenges and Solutions

### “Everything is a priority”

**Response pattern:**
“If everything is a priority, nothing is. Let’s use RICE scoring to objectively rank these. Which initiatives have the highest reach × impact relative to effort? What are we willing to say ‘not now’ to?”

### “But [executive/customer] really wants this”

**Response pattern:**
“Let’s score it objectively. What’s the reach, impact, confidence, and effort? How does it compare to our current priorities? If it scores higher, we can re-prioritize. If not, we can explain why with data.”

### “We need to balance quick wins with strategic bets”

**Response pattern:**
“Agreed. Let’s aim for 70-20-10: 70% high-confidence improvements, 20% medium-confidence bets, 10% experimental long-shots. Does our current portfolio match this?”

### “The scoring feels subjective and gameable”

**Response pattern:**
“You’re right to be concerned. Let’s: (1) Use consistent scoring scales, (2) Score collaboratively as a team, (3) Base estimates on data when possible, (4) Review scores against actual results to calibrate.”

## Best Practices

### Do’s

- Score collaboratively with cross-functional teams
- Use data to support estimates when available
- Re-score based on learnings and new information
- Make scoring scales consistent across initiatives
- Document assumptions behind scores
- Review actual outcomes vs. predicted scores
- Balance portfolio across effort/impact quadrants

### Don’ts

- Let HiPPO (Highest Paid Person’s Opinion) override scores
- Score in isolation without team input
- Set scores once and never revisit
- Game the system to get pet projects approved
- Ignore effort estimates from engineering
- Forget to communicate deprioritization decisions
- Prioritize solely based on ease (avoid “easy button” trap)

## Prioritization Success Metrics

Track these to know if your framework is working:

- **Delivery predictability** - Are we completing prioritized work on time?
- **Value realization** - Do completed initiatives move target metrics?
- **Team alignment** - Can everyone explain current priorities?
- **Decision speed** - How fast can we make priority calls?
- **Stakeholder satisfaction** - Do stakeholders understand trade-offs?
- **Score accuracy** - How close are actual results to predictions?

## RICE Scoring Deep Dive

### Reach: How many people will this impact?

**Definition:** Number of people/events affected per time period (usually per quarter)

**How to estimate:**

- Use product analytics for existing flows
- Base on current user segments
- Account for adoption rate (not everyone will use it)
- Be specific: “customers/quarter” or “sessions/month”

**Scoring guidance:**

- Use actual numbers, not T-shirt sizes
- 1,000+ users per quarter = significant reach
- 100-1,000 = moderate reach
- <100 = low reach (may still be valuable for strategic reasons)

**Example:**

- Feature used by 2,000 customers/month = 6,000 reach per quarter
- New signup flow with 500 signups/month × 80% see change = 1,200 reach per quarter

### Impact: How much will this improve the metric we care about?

**Definition:** How much each person/event is affected

**Scoring scale:**

- **3.0** = Massive impact - Game-changing, primary differentiator
- **2.0** = High impact - Significant improvement to key metric
- **1.0** = Medium impact - Noticeable improvement
- **0.5** = Low impact - Minor improvement
- **0.25** = Minimal impact - Barely noticeable

**How to estimate:**

- Connect to North Star or input metrics
- Look at similar features’ historical impact
- Use A/B test results when available
- Consider competitive differentiation

**Example:**

- Solves #1 churn reason = 3.0 (massive)
- Improves conversion by 15-20% = 2.0 (high)
- Nice-to-have quality improvement = 0.5 (low)

### Confidence: How sure are you about reach, impact, and effort?

**Definition:** Certainty in your estimates

**Scoring scale:**

- **100%** = High confidence - Strong data, proven approach
- **80%** = Medium confidence - Some data, reasonable assumptions
- **50%** = Low confidence - Mostly assumptions, high uncertainty

**What increases confidence:**

- User research validating the problem
- Historical data on similar features
- Customer requests and feedback
- Technical prototype or proof of concept
- Engineering estimates with specifications

**What decreases confidence:**

- Whiteboard sketches only
- Gut feelings without data
- Untested assumptions
- New technical territory
- External dependencies

**Example:**

- 100%: We have A/B test data showing 25% improvement
- 80%: We have user research but no hard metrics yet
- 50%: This is a hypothesis we want to test

### Effort: How much work will this take?

**Definition:** Total person-months across all functions (product, design, engineering)

**How to estimate:**

- Break down by discipline (PM, design, engineering, QA)
- Use person-months (work one person can do in a month)
- Keep estimates rough: whole numbers or 0.5
- Include all phases: design, development, testing, launch

**Scoring guidance:**

- 0.5 = Less than 2 weeks total effort
- 1 = About 1 month
- 2-3 = Moderate project (quarter)
- 5+ = Major initiative
- 10+ = Multi-quarter epic

**Example:**

- Small UI change: 1 designer (0.5) + 1 engineer (1 week) = 0.5 person-months
- New feature: 2 engineers (6 weeks) + 1 designer (3 weeks) = 3.5 person-months
- Platform rebuild: 4 engineers (3 months) = 12 person-months

### RICE Formula

**RICE Score = (Reach × Impact × Confidence) / Effort**

**Example Calculation:**

Initiative: Add dark mode

- Reach: 80,000 users per quarter
- Impact: 1.0 (medium - quality of life improvement)
- Confidence: 80% (0.8) - we have survey data
- Effort: 2 person-months

RICE Score = (80,000 × 1.0 × 0.8) / 2 = **32,000**

Initiative: AI-powered recommendations

- Reach: 150,000 users per quarter
- Impact: 2.0 (high - drives engagement)
- Confidence: 50% (0.5) - untested hypothesis
- Effort: 6 person-months

RICE Score = (150,000 × 2.0 × 0.5) / 6 = **25,000**

→ Prioritize dark mode (32,000) over AI recommendations (25,000)

## ICE Scoring Alternative

### When to Use ICE Instead of RICE

ICE is faster and simpler, best for:

- Growth experiments and A/B tests
- Early-stage ideas without clear reach data
- Rapid prioritization (minutes, not hours)
- Marketing campaigns and tactics

### ICE Components

**Impact (1-10 scale):**

- 10 = Transformative
- 7-9 = Very high
- 4-6 = Medium
- 1-3 = Low

**Confidence (1-10 scale):**

- 10 = Proven (data-backed)
- 7-9 = High confidence
- 4-6 = Medium confidence
- 1-3 = Low confidence

**Ease (1-10 scale):**

- 10 = Trivial (hours to days)
- 7-9 = Easy (days to week)
- 4-6 = Moderate (1-2 weeks)
- 1-3 = Hard (weeks to months)

**ICE Score = (Impact + Confidence + Ease) / 3**

Or simpler: **Impact × Confidence × Ease**

## RACI Matrix Deep Dive

### When to Use RACI

RACI is essential when:

- Multiple teams/stakeholders involved
- Unclear who makes final decisions
- Frequent “who owns this?” questions
- Cross-functional dependencies
- New initiatives without established ownership

### RACI Roles Explained

**R = Responsible (Doer)**

- Does the actual work
- Completes the task or deliverable
- Can have multiple people
- Cannot delegate their responsibility

**Examples:**

- Engineer writes the code
- Designer creates the mockups
- PM writes the specification

**A = Accountable (Owner)**

- Owns the outcome
- Makes final decisions
- Approves the work
- **ONLY ONE per task**
- Cannot be delegated

**Examples:**

- Product Manager accountable for feature delivery
- Engineering Lead accountable for technical quality
- VP Product accountable for roadmap

**C = Consulted (Advisor)**

- Provides input and expertise
- Two-way communication
- Subject matter experts
- Input happens BEFORE work is done

**Examples:**

- Legal consulted on privacy features
- Security consulted on authentication changes
- Customer success consulted on UX changes

**I = Informed (Stakeholder)**

- Kept updated on progress
- One-way communication
- No input required
- Notified of completion or major milestones

**Examples:**

- Executive team informed of launch
- Marketing informed of feature release
- Support team informed of changes

### RACI Best Practices

**One Accountable Rule:**

- Each task must have exactly ONE accountable person
- This is your decision-maker and ultimate owner
- Two accountables = no accountability

**Not Everyone Needs a Letter:**

- It’s okay to have blank cells
- Not every role needs involvement in every task
- Too many C’s = decision paralysis
- Too many I’s = email overload

**Balance Responsible Assignments:**

- Don’t overload individuals with too many R’s
- Distribute work across the team
- Check for capacity and bandwidth

**RACI is Living Document:**

- Update as project evolves
- Review when responsibilities shift
- Remove completed tasks regularly

## Effort-Impact Matrix

### Four Quadrants

**Quick Wins (High Impact, Low Effort)**

- **Do First**
- Easy wins that move the needle
- Build momentum and team confidence
- Target: 40% of capacity

**Major Projects (High Impact, High Effort)**

- **Do Next**
- Strategic bets worth the investment
- Require cross-functional commitment
- Target: 40% of capacity

**Fill-Ins (Low Impact, Low Effort)**

- **Do Later**
- Nice-to-haves when capacity allows
- Good for new team members
- Target: 10% of capacity

**Money Pits (Low Impact, High Effort)**

- **Avoid**
- High cost, low return
- Question why these exist
- Target: 0% of capacity (unless strategic requirement)

### Using the Matrix

1. Plot all initiatives on the matrix
1. Identify where most items cluster
1. Aim for portfolio balance:
- 40% Quick Wins
- 40% Major Projects
- 10% Fill-Ins
- 10% Innovation/Exploration
1. Ruthlessly cut or defer Money Pits

-----

## References

- Prioritization Template: `2-prioritization-template.md`
- Product Strategy: `../2.1.1-Product-Strategy/README.md`
- OKR Framework: `../2.1.2-OKR/README.md`
- Roadmap: `../2.1.3-Roadmap/README.md`
- North Star: `../2.1.6-North-Star/README.md`
- Opportunity Assessment: `../../2.3-Discovery/2.3.4-Opportunity-Assessment/README.md`
- Bias Framework: `../../2.9-Other/2.9.4-Bias/README.md`
- Self-Reflection: `../../2.9-Other/2.9.2-Self-Reflection/README.md`

