# Conventional Human-Run Project Management Notes

This document synthesizes tried-and-tested software-project practices from predictive, agile, and hybrid delivery. It is a bundled background note for the `software-project-management` skill, not the default playbook for pure LLM-run projects. Source anchors refer to [source-anchors.md](./source-anchors.md).

## Table of Contents
- Purpose and Use
- A Normal Human-Run Software Project
- Predictive, Agile, and Hybrid
- Planning Mechanics
- Governance and Decision Rights
- Handoffs and Stage Transitions
- Progress Control
- Risk and Mitigation
- Quality Control
- User Testing and Feedback Loops
- Documentation
- Commonly Missed but Critical Topics
- Working Synthesis

## Purpose and Use
- Use this file only when the project includes meaningful human coordination, fixed calendars, external approvals, budgeting, or non-agent teams.
- For pure LLM-run projects, start with the master rulebook and the agent-practices reference, then pull from this file selectively.
- Treat predictive and agile as different control styles for the same job: delivering value under constraints with visible risk, quality, and accountability.
- Tailor the amount of upfront detail to uncertainty, but do not skip planning, governance, documentation, or quality control. Sources consistently support tailoring, not abandoning controls. [S03] [S04] [S05] [S06]

## A Normal Human-Run Software Project

### Typical Preconditions
- A real problem, opportunity, or mandate exists and has an identified owner. [S04] [S05]
- There is authority to spend money, time, and attention. [S05] [S11]
- Success criteria are explicit enough to decide whether to continue, stop, or change course. [S04] [S09]
- The team has access to required capabilities or a plan to procure them. [S03] [S11]
- Constraints are visible early: schedule drivers, compliance, architecture, support, procurement, dependencies, and operating context. [S04] [S10] [S11]

### Common Lifecycle Shape
- Discovery or initiation: clarify mandate, users, constraints, goals, and viability. [S05] [S12] [S13]
- Planning and mobilization: choose lifecycle, define scope, decompose work, estimate, map dependencies, plan risks, plan quality, prepare environments, assign roles. [S05] [S06] [S07] [S08]
- Delivery: execute work, coordinate dependencies, validate quality, adapt plans, and keep stakeholders informed. [S03] [S05] [S06]
- Validation and release: run acceptance, usability, operational, and compliance checks; cut over safely. [S03] [S04] [S12]
- Transition and closure: hand off to operations/support, capture lessons, measure benefits, and close open issues or residual risks. [S05] [S11] [S13]

## Predictive, Agile, and Hybrid

### Predictive
- Best fit when work is definable, dependencies are stable, external approvals are heavy, or the cost of late change is high. [S05] [S06]
- Control model: baselines for scope, schedule, and cost; formal change control; stage-gates; stronger critical-path discipline. [S05] [S08] [S11]

### Agile
- Best fit when the work is complex, user learning matters, and requirements will change as the team learns. [S02] [S03] [S06] [S13]
- Control model: prioritized backlog, short feedback cycles, empirical measures, regular inspection and adaptation, scope negotiated continuously within outcome guardrails. [S03] [S06]

### Hybrid
- Best fit when some parts are date-driven or regulated and other parts remain uncertain or discovery-heavy. [S06] [S13]
- Control model: fixed governance and macro-boundaries, flexible near-term execution, rolling-wave planning, and selective baselining. [S06] [S08]

## Planning Mechanics

### Scope and Decomposition
- Scope should be separated into:
  - outcome and value intent
  - solution scope
  - exclusions
  - constraints
  - acceptance and quality conditions
- A WBS or backlog is the practical mechanism for decomposing work. The point is not the artifact name but controlled decomposition. [S07] [S09]
- Decomposition should produce work items that are estimable, assignable, testable, and handoff-ready. [S07] [S08]

### Dependency Mapping
- Dependencies need four categories:
  - predecessor/successor logic within the team
  - cross-team dependencies
  - external approvals and procurement
  - environment or data dependencies
- Hidden dependencies are one of the most common causes of missed dates and chaotic handoffs. [S05] [S08] [S11]
- For agile work, dependencies still need explicit visibility; a backlog alone is not enough. [S03] [S06] [S13]

### Critical Path
- Critical path analysis is still useful for software whenever there is a committed date, scarce specialist capacity, regulatory sequencing, or deployment coordination. [S08]
- A workable critical-path method for software:
  1. define deliverables and stage exits
  2. decompose into activities
  3. estimate durations and resource assumptions
  4. map logical dependencies
  5. calculate the longest path
  6. identify float and buffers
  7. revisit after each major change
- Agile delivery does not remove critical paths; it often shifts them to integration, approvals, data migration, release windows, and external team dependencies. [S06] [S08]

### Resource Planning
- Plan by capability, not just headcount. The bottleneck is often architecture, test automation, security review, design, data, or release engineering rather than total team size. [S04] [S11]
- Account for non-build work: discovery, documentation, test data, operations prep, training, cutover, support, and rework. [S04] [S13]
- Sustainable pace matters. Scrum explicitly ties consistency and focus to working in sprints at a sustainable pace. [S03]

### Budgeting Time and Cost
- Time and cost budgets should include:
  - delivery work
  - management and coordination overhead
  - testing and hardening
  - release/cutover/rollback work
  - support handoff
  - contingency and management reserve
- Use bottom-up estimates for near-term known work and top-down caps for portfolio constraints. [S05] [S08]
- Reforecast continuously. A baseline without reforecasting becomes theater. [S05] [S13]

## Governance and Decision Rights
- Software projects need explicit decision rights for:
  - scope and backlog ordering
  - architecture and standards
  - release approval
  - budget and staffing changes
  - risk acceptance
  - change control
- Governance should define cadence and escalation paths, not only approval checkpoints. [S11]
- Scrum is explicit that the Product Owner is accountable for maximizing value and backlog transparency; this is a practical anti-pattern check against committee ownership. [S03]

## Handoffs and Stage Transitions
- Handoffs need an artifact contract. A task is not ready for handoff if the receiver must rediscover context. [S05] [S09]
- A useful handoff package includes:
  - objective and current state
  - assumptions
  - required inputs and dependencies
  - output artifacts
  - tests or acceptance evidence
  - unresolved risks/issues
  - owner of next decision
- Stage transitions should have exit criteria, not just dates. [S05] [S11]

## Progress Control
- Predictive work often reports earned progress against a plan; agile work reports progress through working increments, backlog movement, and empirical delivery signals. Both still need forecasting. [S05] [S06] [S13]
- Useful progress control combines:
  - milestone status
  - completion evidence
  - risk and issue status
  - burn or throughput trends where appropriate
  - forecast vs target
  - decision log for major scope/timeline changes
- GOV.UK guidance is strong on reporting only what helps decision-makers and avoiding reporting theater that drains delivery capacity. [S13]

## Risk and Mitigation
- Risk management is continuous, not a kickoff ritual. [S10]
- Risk practice should cover:
  - identification
  - probability and impact estimation
  - exposure or priority ranking
  - qualitative or quantitative analysis
  - response planning
  - ownership
  - trigger conditions
  - residual risk tracking
- A workable software-project risk entry should name:
  - risk statement
  - cause
  - consequence
  - likelihood
  - impact
  - mitigation or contingency
  - owner
  - trigger for escalation
- Mitigation is stronger when tied to early warning signals and decision thresholds rather than vague "watch closely" language. [S10] [S11]
- Software-specific high-frequency risks:
  - architecture mismatch
  - unmanaged technical debt
  - hidden dependencies
  - environment instability
  - poor test data
  - external vendor delays
  - weak product ownership
  - under-scoped NFRs
  - change overload
  - release/rollback weakness

## Quality Control
- Quality must be defined before work starts through acceptance criteria, NFRs, standards, and a definition of done or equivalent. [S03] [S04]
- Quality control is layered:
  - prevention through standards and review
  - verification through tests and inspections
  - validation through user-facing evaluation and acceptance
  - operational checks through monitoring, rollback, and support readiness
- Scrum explicitly ties developers to adhering to a Definition of Done and adapting daily toward the sprint goal. [S03]

## User Testing and Feedback Loops

### User Testing for Quality
- Use usability testing and direct observation to detect whether the software is understandable, accessible, and error-resistant. [S12]
- This is a quality question: "Can real users use it successfully and safely?"

### User Testing for Value
- Use discovery research, interviews, prototype tests, and review sessions to determine whether the team is solving the right problem. [S12] [S13]
- This is a value question: "Are we building the right thing?"

### Process Learning Loops
- Retrospectives and lessons learned should change behavior, not just record observations. [S02] [S03] [S05]
- Agile guidance emphasizes frequent reflection and adjustment; predictive guidance emphasizes closure learning and process improvement. A mature hybrid system should do both. [S02] [S05]

## Documentation

### Documentation Types Needed by Most Software Projects
- Business case or mandate
- Product vision and success criteria
- Scope definition and exclusions
- Roadmap, release plan, schedule model, or sprint plan
- Dependency map
- Risk, issue, and change logs
- Requirements or backlog
- Architecture and key design records
- Test strategy and evidence
- Environment and data setup instructions
- Release, cutover, and rollback plans
- Operations/support runbooks
- Decision log and lessons learned

### Living Documentation
- Documentation must be versioned, owned, reviewable, and tied to work. [S03] [S05] [S13]
- A good living-documentation system uses:
  - a small entry-point index
  - named owners
  - review cadence
  - freshness checks during delivery and release
  - retirement of stale content

## Commonly Missed but Critical Topics
- Architecture and technical debt management
- Non-functional requirements and compliance constraints
- Test environments and data readiness
- Release, cutover, and rollback planning
- Operational readiness and support handoff
- Procurement and vendor dependencies
- Adoption, training, and change management
- Cross-team dependency governance
- Benefits realization after delivery

## Working Synthesis
- The best unifying principle is: lock what must be stable early, leave uncertain details flexible, and keep evidence-based control loops running throughout. [S03] [S05] [S06]
- Predictive, agile, and hybrid methods differ mainly in when detail is fixed, how often plans are refreshed, and how change is governed.
- Architecture and technical debt should be treated as managed scope with explicit trade-offs, not as invisible residue. If it matters enough to threaten schedule, quality, or operability, it belongs in the plan, backlog, risk log, or roadmap. [S04] [S10] [S11]
- None of the credible sources support "no planning", "no documentation", or "ship first and clean up governance later" as a serious project-management model.
