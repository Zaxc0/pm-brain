---
title: Frameworks Decision Guide
---

# Purpose
Pick the right framework fast for your current discovery phase, entry trigger, and riskiest assumption.

## Introduction

This directory contains product management frameworks organized by purpose. Each framework is self-contained with principles, processes, and templates. Use the decision guide below to find the right framework for your current situation.

## How Frameworks Work Together

The frameworks follow a natural product development flow:

**Discovery → Define → Decide → Deliver → Launch & Learn**

1. **Discover** (2.5-Continuous-Discovery-Habits): Interview users, observe behavior, collect stories
2. **Define** (2.6-Jobs-To-Be-Done, 2.5.3-create-opportunities): Frame problems as jobs and opportunities
3. **Decide** (2.5.4-generate-solutions, 2.7-Idea-Validation): Generate solutions and validate assumptions
4. **Deliver** (2.8-PRD): Write requirements and build
5. **Launch & Learn** (2.2-OKR, 2.3-Roadmap): Measure outcomes and iterate

**Strategic Context:**
- **2.1-Product-Strategy**: Sets strategic direction (done first, informs everything)
- **2.2-OKR**: Operationalizes strategy into measurable outcomes
- **2.3-Roadmap**: Plans execution timeline
- **2.4-Newsletter**: Communicates progress

## How to Use This Directory

1. **Identify your entry point**: Use the decision map below to find the right starting framework
2. **Follow the flow**: Use framework outputs to determine next steps
3. **Maintain traceability**: Link documents together (JTBD → Opportunity → PRD → OKR)
4. **Iterate**: Frameworks are living processes, not one-time activities

## How to Maintain

- **Quarterly Review**: Review framework effectiveness and update based on learnings
- **After Major Changes**: Update frameworks when processes evolve
- **Version Control**: Track framework changes in git
- **Team Feedback**: Gather feedback on framework usability and effectiveness

## How to use
1) Identify your entry trigger and primary risk (desirability, usability, feasibility, viability).  
2) Start with the recommended framework below; capture outputs.  
3) Move to the next framework based on what the outputs unlock.

# PRD (Product Requirements Document) Framework

## Introduction

Use this framework and template to create product requirements documents that bridge discovery and execution, aligning cross-functional teams around what to build and how success will be measured.

## Files
- `2.8.1-prd-framework.md` — Complete PRD framework with principles, structure guidance, and quality checklist
- `2.8.2-prd-template.md` — Standard PRD template with sections for context, requirements, and success metrics
- `2.8.3-prd-jtbd-template.md` — Jobs-to-Be-Done focused PRD template for job-centered product work

## How to use
1) Review the framework in `2.8.1-prd-framework.md` to understand PRD principles and when to use them
2) Choose your template:
   - Use `2.8.2-prd-template.md` for standard product requirements
   - Use `2.8.3-prd-jtbd-template.md` when your work is centered around customer jobs
3) Start with section 3 (Goals & Success Metrics) then work outward
4) Use the quality checklist to ensure completeness before stakeholder review
5) Maintain as living document; track changes in version history

## When to Use
- After solution validation (passed RAT tests)
- For initiatives requiring >2 weeks engineering effort
- When cross-functional alignment is critical
- When clear success metrics can be defined

## How to Maintain

- **During Development**: Update open questions and decisions as they're resolved
- **Post-Launch**: Track success metrics and update post-launch plan section
- **Quarterly Reviews**: Archive completed PRDs and extract learnings

## Links
- Product Strategy: `../2.1.1-Product-Strategy/README.md`
- Jobs To Be Done: `../../2.3-Discovery/2.3.3-Jobs-To-Be-Done/README.md`
- Idea Validation: `../../2.3-Discovery/2.3.4-Idea-Validation/README.md`
- OKR Framework: `../2.1.2-OKR/README.md`

