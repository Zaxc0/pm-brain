# Creating Interview Snapshots (Continuous Discovery Habits)

## Goal
Guide an AI assistant in extracting meaningful insights from qualitative interviews or user research sessions, creating structured snapshots that capture specific customer stories, behaviors, and needs following the Continuous Discovery Habits methodology.

## Output
- **Format:** Markdown (`.md`)
- **Location:** `03-Research-Artifacts/3.1-User-Interviews/snapshots/`
- **Filename:** `snapshot-[participant-identifier]-[YYYY-MM-DD].md`

## Process
0. **Follow the rules:** Start by telling me your plan for approaching this task in a way that is optimized to uphold these guidelines above all, and eliminates any chance of violating them. Make sure it includes a final phase of verifying every single quote, and fixing any violations, repeating this until there are no violations. 
1. **Parse Interview Data:** Process transcript, notes, or session recordings
2. **Identify Session Type:** Categorize as discovery interview, usability test, feedback session, etc.
3. **Extract Customer Stories:** Focus on specific behavioral instances, not generalizations
4. **Map Customer Journey:** Document the participant's experience flow
5. **Identify Needs & Pain Points:** Extract underlying customer needs from stories
6. **Capture Behavioral Insights:** Note interesting patterns or unexpected behaviors
7. **Create Structured Snapshot:** Compile findings using standard template
8. **Tag for Retrieval:** Add relevant tags for future synthesis

## Story Extraction Principles
**DO capture:**
- **Specific instances:** "The last time I..." or "Yesterday when I..."
- **Actual behavior:** What they did step-by-step, in sequence
- **Contextual details:** Environment, timing, tools used, people involved
- **Emotional reactions:** Moments of frustration, delight, confusion, surprise
- **Current workarounds:** How they solve problems today with existing tools
- **Failed attempts:** What they've tried that didn't work and why

**AVOID capturing:**
- **Generalizations:** "I always..." "I never..." without specific examples
- **Hypothetical scenarios:** "I would probably..." or "If I could..."
- **Feature requests:** Unless you probe for the underlying need/problem
- **Opinions about competitors:** Focus on their actual experience, not comparisons
- **Wishful thinking:** What they think they want vs. what they actually do

## Interview Snapshot Template
```markdown
# Interview Snapshot: [Participant Role/ID] - [Date]

## Participant Context
- **Role/Position:** [Their job function or user type]
- **Experience Level:** [Novice/Intermediate/Expert in relevant domain]
- **Usage Context:** [How/when they use the product/service]
- **Interview Type:** [Discovery/Usability/Feedback/etc.]

## Key Stories Captured

### Story 1: [Brief descriptive title]
**Situation:** [Context and trigger]
**Actions:** [Step-by-step what they did]
**Outcome:** [What happened as a result]
**Emotion:** [How they felt about the experience]

### Story 2: [Brief descriptive title]
**Situation:** [Context and trigger]
**Actions:** [Step-by-step what they did]
**Outcome:** [What happened as a result]
**Emotion:** [How they felt about the experience]

## Customer Journey Moments
- **Trigger:** What initiated their process
- **Key Steps:** Major phases of their workflow
- **Decision Points:** Where they had to make choices
- **Pain Points:** Friction or frustration moments
- **Success Moments:** When things worked well

## Needs Identified
- **Explicit Needs:** What they directly said they needed
- **Implicit Needs:** Underlying needs inferred from their stories
- **Unmet Needs:** Problems they're solving with workarounds

## Behavioral Insights
- **Surprising Behaviors:** Actions that differed from expectations
- **Workaround Patterns:** How they adapt when primary solution fails
- **Mental Models:** How they think about the problem space
- **Success Patterns:** What conditions lead to positive outcomes

## Quotes & Evidence
> "[Exact quote that illustrates key insight]"
> 
> "[Another relevant quote with context]"

## Opportunities Suggested
- [Potential opportunity based on unmet needs]
- [Another opportunity from behavioral patterns]

## Follow-up Questions
- [Questions to explore in future interviews]
- [Assumptions to test based on this conversation]

## Tags
#[customer-segment] #[use-case] #[product-area] #[priority-level]
```

## Quality Checklist
Before saving, verify:
- [ ] At least 2-3 specific stories captured with full context
- [ ] Clear distinction between what they said vs. what they did
- [ ] Underlying needs identified, not just surface complaints
- [ ] Direct quotes captured to support insights
- [ ] Behavioral patterns noted, not just preferences
- [ ] Tagged appropriately for future synthesis
```