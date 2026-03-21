# Software Project Rules

This document is the master rulebook bundled with the `software-project-management` skill. It turns the research into explicit operating rules. Source anchors refer to [source-anchors.md](./source-anchors.md).

## Table of Contents
- Purpose and How to Use This Document
- Universal Rules
- Project Prerequisites and Readiness Checks
- Lifecycle Selection and Tailoring Rules
- Governance, Roles, and Decision Rights
- Scope, Requirements, and Acceptance Criteria
- Planning: WBS/Backlog, Estimates, Dependencies, Critical Path, Resources, Budget
- Execution, Handoffs, and Stage Transitions
- Monitoring and Control: Status, Metrics, Forecasting, Issue/Risk/Change Control
- Quality Engineering and Test Strategy
- User Research, Usability Testing, and Value Feedback Loops
- Documentation System and Living Documentation
- Release, Operational Readiness, Support Handoff, and Closure
- AI-Agent Operating Rules
- Recent 2025-2026 Developments and Unknown Unknowns
- Appendix A - Artifact Checklist
- Appendix B - Delivery-Mode Mapping
- Appendix C - Question Coverage Map

## Purpose and How to Use This Document
- Use this file as a rulebook for running software projects across predictive, agile, hybrid, and agent-assisted modes.
- Treat the rules as a control system, not as ceremony. The goal is reliable value delivery under real constraints.
- Tailor the amount of upfront detail to uncertainty, but do not remove the underlying controls for ownership, scope, quality, risk, change, documentation, and feedback. [S03] [S05] [S06]

## Universal Rules

### R01 - Define the value outcome before choosing the delivery method
- Applies to: predictive, agile, hybrid, agentic
- Required artifacts: problem statement, business or user outcome statement, success criteria
- Why it matters: method selection only makes sense after the team knows what value it is trying to create.
- Failure prevented: building activity around a vague mandate; optimizing process while missing the goal
- Source anchors: [S01] [S03] [S04] [S14]

### R02 - Assign one accountable owner for value decisions
- Applies to: predictive, agile, hybrid, agentic
- Required artifacts: named accountable owner, decision-rights map
- Why it matters: value decisions need a single throat to choke and a single point of prioritization.
- Failure prevented: committee paralysis, backlog churn, conflicting stakeholder instructions
- Source anchors: [S03] [S11]

### R03 - Keep one visible system of record for project truth
- Applies to: predictive, agile, hybrid, agentic
- Required artifacts: source-of-truth index, linked working artifacts, ownership list
- Why it matters: work breaks down when plans, decisions, and evidence are split across invisible locations.
- Failure prevented: rediscovery, conflicting assumptions, stale tribal knowledge
- Source anchors: [S05] [S13] [S18] [S19] [S24]

### R04 - Make every meaningful unit of work estimable, testable, and handoffable
- Applies to: predictive, agile, hybrid, agentic
- Required artifacts: decomposed work item, acceptance criteria, ready-for-handoff package
- Why it matters: if work cannot be estimated, tested, or handed off, it is not ready for controlled execution.
- Failure prevented: vague tasks, rework loops, broken stage transitions
- Source anchors: [S07] [S08] [S09] [S18]

## Project Prerequisites and Readiness Checks

### R05 - Do not start without a real mandate, budget authority, and success definition
- Applies to: predictive, agile, hybrid, agentic
- Required artifacts: charter or mandate, sponsor, budget/time authorization, success criteria
- Why it matters: projects need explicit authority and a stop-or-go basis.
- Failure prevented: shadow projects, orphan work, endless initiation
- Source anchors: [S04] [S05] [S11]

### R06 - Surface constraints early, especially the ones teams forget
- Applies to: predictive, agile, hybrid, agentic
- Required artifacts: constraint log covering compliance, NFRs, architecture, procurement, environments, support, release windows
- Why it matters: software slips are often caused by hidden constraints rather than code volume.
- Failure prevented: late surprises in security, infrastructure, legal, support, or performance
- Source anchors: [S04] [S10] [S11]

### R07 - Staff by required capabilities, not by generic headcount
- Applies to: predictive, agile, hybrid, agentic
- Required artifacts: capability map, staffing plan, acquisition plan for missing skills
- Why it matters: the schedule is constrained by bottleneck skills and decisions, not by total people.
- Failure prevented: false confidence from oversized but unbalanced teams
- Source anchors: [S03] [S04] [S11]

### R08 - Prepare environments, data, and access as first-class project work
- Applies to: predictive, agile, hybrid, agentic
- Required artifacts: environment plan, test-data plan, access and dependency checklist
- Why it matters: delivery stalls when execution environments are treated as incidental.
- Failure prevented: blocked teams, fake progress, failed testing and release readiness
- Source anchors: [S04] [S13] [S19]

## Lifecycle Selection and Tailoring Rules

### R09 - Use predictive controls when the work is definable and change is expensive
- Applies to: predictive, hybrid
- Required artifacts: baseline scope, baseline schedule, baseline budget, formal change path
- Why it matters: date-driven and approval-heavy work needs firmer upfront control.
- Failure prevented: pretending uncertainty is low while managing loosely
- Source anchors: [S05] [S08] [S11]

### R10 - Use agile controls when uncertainty and learning dominate
- Applies to: agile, hybrid
- Required artifacts: product goal, prioritized backlog, sprint or iteration cadence, review and retrospective cadence
- Why it matters: complex work benefits from frequent inspection and adaptation.
- Failure prevented: locking detail too early, learning too slowly, delayed user feedback
- Source anchors: [S02] [S03] [S06] [S13]

### R11 - Use hybrid delivery when governance must be stable but solution detail cannot be
- Applies to: hybrid, agentic
- Required artifacts: fixed macro-boundaries, rolling-wave plan, control points, local adaptation rules
- Why it matters: many real software efforts contain both predictable and discovery-heavy components.
- Failure prevented: false binary choice between waterfall and scrum purity
- Source anchors: [S06] [S08] [S13]

## Governance, Roles, and Decision Rights

### R12 - Define decision rights explicitly before delivery scales
- Applies to: predictive, agile, hybrid, agentic
- Required artifacts: RACI or equivalent, escalation map, authority boundaries
- Why it matters: high-speed work magnifies decision ambiguity.
- Failure prevented: duplicated approvals, political deadlock, invisible vetoes
- Source anchors: [S03] [S11]

### R13 - Govern by cadence and evidence, not by status theater
- Applies to: predictive, agile, hybrid, agentic
- Required artifacts: governance cadence, standard evidence pack, decision log
- Why it matters: governance should improve decisions, not tax the team.
- Failure prevented: reporting overhead with no control benefit
- Source anchors: [S05] [S13]

### R14 - Define stage or milestone exit criteria before the work reaches them
- Applies to: predictive, agile, hybrid, agentic
- Required artifacts: exit criteria, approvers, evidence requirements
- Why it matters: stage transitions are where ambiguity and wishful thinking tend to concentrate.
- Failure prevented: late gate failures, rushed approvals, handoff chaos
- Source anchors: [S05] [S11]

## Scope, Requirements, and Acceptance Criteria

### R15 - Separate outcome scope from solution scope
- Applies to: predictive, agile, hybrid, agentic
- Required artifacts: outcome statement, in-scope work, out-of-scope work, assumptions
- Why it matters: teams need to know what must be achieved and what is merely one proposed way to achieve it.
- Failure prevented: premature solution lock-in and hidden scope growth
- Source anchors: [S04] [S09]

### R16 - Maintain a controlled decomposition of the total work
- Applies to: predictive, agile, hybrid, agentic
- Required artifacts: WBS or backlog, dependency markers, ownership markers
- Why it matters: controlled decomposition is the foundation for estimates, dependencies, reporting, and handoffs.
- Failure prevented: missing work, duplicate work, untraceable delivery
- Source anchors: [S07] [S09]

### R17 - Attach acceptance and quality conditions to every substantial scope item
- Applies to: predictive, agile, hybrid, agentic
- Required artifacts: acceptance criteria, NFRs, definition of done or equivalent
- Why it matters: without explicit acceptance, teams drift toward shipping outputs instead of verified outcomes.
- Failure prevented: endless interpretation disputes, rework after "completion"
- Source anchors: [S03] [S04] [S09]

## Planning: WBS/Backlog, Estimates, Dependencies, Critical Path, Resources, Budget

### R18 - Plan at two levels: whole-project direction and near-term executable detail
- Applies to: predictive, agile, hybrid, agentic
- Required artifacts: roadmap or master schedule, near-term delivery plan, refresh cadence
- Why it matters: teams need both strategic direction and tactical clarity.
- Failure prevented: either detail paralysis or vague optimism
- Source anchors: [S05] [S06] [S08] [S13]

### R19 - Map dependencies explicitly, including non-code dependencies
- Applies to: predictive, agile, hybrid, agentic
- Required artifacts: dependency map, dependency owners, due dates, escalation path
- Why it matters: cross-team, vendor, environment, and approval dependencies often dominate delivery risk.
- Failure prevented: blocked work and false confidence from local task completion
- Source anchors: [S05] [S08] [S11]

### R20 - Calculate and monitor a critical path whenever dates matter
- Applies to: predictive, hybrid, agentic
- Required artifacts: schedule model, activity logic, duration assumptions, critical-path review cadence
- Why it matters: date commitments are managed through dependency logic, not hope.
- Failure prevented: missing the true schedule drivers and misusing slack
- Source anchors: [S08]

### R21 - Estimate with explicit assumptions and confidence, not single-number certainty
- Applies to: predictive, agile, hybrid, agentic
- Required artifacts: estimate basis, assumptions, ranges or confidence note, refresh date
- Why it matters: most software estimates fail because assumptions remain implicit.
- Failure prevented: pseudo-precision and untracked estimate drift
- Source anchors: [S04] [S08]

### R22 - Plan resources against bottlenecks and sustainable pace
- Applies to: predictive, agile, hybrid, agentic
- Required artifacts: capacity plan, bottleneck analysis, pacing assumption
- Why it matters: throughput collapses when scarce capabilities or exhausted teams become the real constraint.
- Failure prevented: heroic plans that fail in execution
- Source anchors: [S03] [S04]

### R23 - Budget for overhead, risk, and transition, not only build effort
- Applies to: predictive, agile, hybrid, agentic
- Required artifacts: budget model, contingency, reserve policy, transition cost line items
- Why it matters: real project cost includes planning, testing, documentation, release, training, and support handoff.
- Failure prevented: budget blowouts caused by undercounted non-build work
- Source anchors: [S04] [S05] [S10]

### R24 - Reforecast continuously when reality changes
- Applies to: predictive, agile, hybrid, agentic
- Required artifacts: forecast refresh cadence, variance log, recovery options
- Why it matters: a stale plan is worse than no plan because it creates false confidence.
- Failure prevented: late surprise slippage and unmanaged cost drift
- Source anchors: [S05] [S13]

## Execution, Handoffs, and Stage Transitions

### R25 - Start work only when the receiving team has what it needs to succeed
- Applies to: predictive, agile, hybrid, agentic
- Required artifacts: definition of ready, dependency clearance, input package
- Why it matters: work started without ready inputs becomes churn disguised as progress.
- Failure prevented: blocked sprints, context loss, repeated clarification loops
- Source anchors: [S03] [S09] [S18]

### R26 - Hand off artifacts, evidence, and unresolved risks together
- Applies to: predictive, agile, hybrid, agentic
- Required artifacts: handoff note, outputs, tests/evidence, open issues and risks
- Why it matters: a handoff is only complete when the next owner can continue without rediscovery.
- Failure prevented: dropped context, broken acceptance, repeated defects
- Source anchors: [S05] [S09] [S18]

### R27 - Track cross-team and stage-transition work as deliverables, not side conversations
- Applies to: predictive, agile, hybrid, agentic
- Required artifacts: transition checklist, dependency actions, owner list
- Why it matters: integration and transition work is real project work with real schedule cost.
- Failure prevented: "almost done" projects that fail at release or handoff
- Source anchors: [S11] [S13]

## Monitoring and Control: Status, Metrics, Forecasting, Issue/Risk/Change Control

### R28 - Measure progress through completed evidence, not reported effort
- Applies to: predictive, agile, hybrid, agentic
- Required artifacts: milestone evidence, increment evidence, status dashboard
- Why it matters: progress should reflect outputs that are inspectable and usable.
- Failure prevented: percent-complete illusions and optimistic reporting
- Source anchors: [S03] [S05] [S13]

### R29 - Keep separate logs for risks, issues, and changes
- Applies to: predictive, agile, hybrid, agentic
- Required artifacts: risk register, issue log, change log
- Why it matters: a risk is not an issue, and a change request is not either of them.
- Failure prevented: confused accountability and weak mitigation
- Source anchors: [S10] [S11]

### R29A - Estimate risks with owners, triggers, and response types
- Applies to: predictive, agile, hybrid, agentic
- Required artifacts: risk register with likelihood, impact, owner, trigger, mitigation, contingency
- Why it matters: teams cannot mitigate what they have not sized, prioritized, and operationalized.
- Failure prevented: vague risk lists with no usable response path
- Source anchors: [S10] [S11]

### R30 - Inspect and adapt on a fixed cadence
- Applies to: predictive, agile, hybrid, agentic
- Required artifacts: review cadence, retrospective cadence, action list
- Why it matters: problems worsen when learning is ad hoc rather than scheduled.
- Failure prevented: late detection of drift, repeated process mistakes
- Source anchors: [S02] [S03] [S05]

### R31 - Treat scope changes as trade-off decisions, not as free additions
- Applies to: predictive, agile, hybrid, agentic
- Required artifacts: change record, impact analysis, approval outcome, updated forecast
- Why it matters: every scope change consumes time, money, quality margin, or attention.
- Failure prevented: silent scope creep and broken commitments
- Source anchors: [S05] [S06] [S11]

## Quality Engineering and Test Strategy

### R32 - Design quality in before building, then verify and validate continuously
- Applies to: predictive, agile, hybrid, agentic
- Required artifacts: quality criteria, standards, review and test strategy
- Why it matters: quality cannot be inspected into a system after the fact.
- Failure prevented: late defect discovery and quality debt
- Source anchors: [S03] [S04]

### R33 - Use layered testing that matches software risk
- Applies to: predictive, agile, hybrid, agentic
- Required artifacts: test pyramid or equivalent, environment matrix, test-data plan
- Why it matters: different risks need different forms of evidence.
- Failure prevented: overreliance on one test layer and missed regressions
- Source anchors: [S04] [S13] [S22]

### R34 - Treat non-functional requirements as release criteria, not as deferred polish
- Applies to: predictive, agile, hybrid, agentic
- Required artifacts: NFR list, thresholds, validation method
- Why it matters: security, performance, accessibility, reliability, privacy, and operability often decide whether software is truly shippable.
- Failure prevented: technically complete but operationally unacceptable releases
- Source anchors: [S04] [S11] [S12]

### R34A - Treat architecture and technical debt as managed scope, not as invisible residue
- Applies to: predictive, agile, hybrid, agentic
- Required artifacts: architecture decision records, debt backlog or risk log, trade-off notes
- Why it matters: architecture quality and accumulated debt directly affect delivery speed, operability, and change cost.
- Failure prevented: schedule and quality degradation caused by untracked structural compromise
- Source anchors: [S04] [S10] [S11]

## User Research, Usability Testing, and Value Feedback Loops

### R35 - Run user testing to improve product quality
- Applies to: agile, hybrid, predictive, agentic
- Required artifacts: usability research plan, participant criteria, findings log
- Why it matters: software quality includes usability, accessibility, and task success in real hands.
- Failure prevented: shipping software that passes tests but fails users
- Source anchors: [S12]

### R36 - Run user research to improve delivered value
- Applies to: agile, hybrid, predictive, agentic
- Required artifacts: discovery research plan, research questions, decision log tied to findings
- Why it matters: building the right product is a separate problem from building the product right.
- Failure prevented: feature factories and low-value output
- Source anchors: [S02] [S12] [S14] [S15]

### R37 - Feed research and review findings back into scope and process
- Applies to: agile, hybrid, predictive, agentic
- Required artifacts: backlog or scope updates, retrospective actions, changed assumptions
- Why it matters: feedback matters only when it changes what the team builds or how it works.
- Failure prevented: performative research and inert retrospectives
- Source anchors: [S02] [S03] [S05] [S12]

## Documentation System and Living Documentation

### R38 - Maintain a minimal entry-point map and deeper linked references
- Applies to: predictive, agile, hybrid, agentic
- Required artifacts: top-level index, linked topical docs, ownership metadata
- Why it matters: people and models need a navigable map before they need detail.
- Failure prevented: giant unreadable manuals and documentation sprawl
- Source anchors: [S18] [S19] [S24]

### R39 - Review, refresh, and retire documentation continuously
- Applies to: predictive, agile, hybrid, agentic
- Required artifacts: freshness cadence, doc owners, stale-doc retirement path
- Why it matters: stale documentation is active operational risk.
- Failure prevented: incorrect decisions based on obsolete instructions
- Source anchors: [S05] [S13] [S19] [S24]

## Release, Operational Readiness, Support Handoff, and Closure

### R40 - Plan cutover, rollback, and support readiness as project work
- Applies to: predictive, agile, hybrid, agentic
- Required artifacts: release plan, rollback plan, support plan, runbooks
- Why it matters: the release is part of delivery, not an afterthought after coding.
- Failure prevented: failed launches, unsupported live systems, emergency improvisation
- Source anchors: [S04] [S11] [S13]

### R41 - Hand off to operations and support with explicit ownership and evidence
- Applies to: predictive, agile, hybrid, agentic
- Required artifacts: runbooks, support contacts, known issues, monitoring thresholds, training materials
- Why it matters: operational success requires more than shipping code.
- Failure prevented: post-release confusion and slow incident response
- Source anchors: [S05] [S11] [S13]

### R42 - Close the project by capturing lessons and residual obligations
- Applies to: predictive, agile, hybrid, agentic
- Required artifacts: retrospective or lessons learned, debt list, residual risk log, benefits follow-up plan
- Why it matters: closure is where teams turn one project’s cost into future capability.
- Failure prevented: repeated mistakes and abandoned obligations
- Source anchors: [S02] [S05] [S15]

## AI-Agent Operating Rules

### R43 - Store durable task state in files, not only in chat
- Applies to: agentic, hybrid
- Required artifacts: execution plan, progress log, decision log, evidence log
- Why it matters: chat context is transient; files survive sessions, model changes, and handoffs.
- Failure prevented: context-window dependence and task amnesia
- Source anchors: [S18] [S19] [S24]

### R44 - Keep agent entry-point instructions short, stable, and navigational
- Applies to: agentic, hybrid
- Required artifacts: short root instructions, linked deeper references
- Why it matters: concise entry points preserve context budget and improve adherence.
- Failure prevented: bloated instruction files that crowd out the task itself
- Source anchors: [S16] [S19] [S24]

### R45 - Make the codebase legible to the agent before expecting autonomy
- Applies to: agentic, hybrid
- Required artifacts: architecture map, commands, boundary rules, searchable references
- Why it matters: an agent can only act reliably on what it can discover and verify.
- Failure prevented: hallucinated structure, poor navigation, repeated rediscovery
- Source anchors: [S18] [S19]

### R46 - Make every autonomous task acceptance-driven
- Applies to: agentic, hybrid
- Required artifacts: acceptance criteria, exact commands, success condition, escalation rule
- Why it matters: agents need clear checks before they act.
- Failure prevented: plausible-looking but unverifiable work
- Source anchors: [S17] [S18]

### R47 - Route work to the smallest model that can do it reliably
- Applies to: agentic, hybrid
- Required artifacts: task-shape routing rule, model selection note for heavier work
- Why it matters: cost control is a workflow design problem, not only a finance problem.
- Failure prevented: token waste and unnecessary latency
- Source anchors: [S16] [S20] [S21]

### R48 - Use subagents for bounded parallel work and high-volume output
- Applies to: agentic, hybrid
- Required artifacts: scoped subtask brief, expected output, tool limits, ownership boundary
- Why it matters: subagents preserve main-context quality and increase throughput when work is decomposed cleanly.
- Failure prevented: context pollution and duplicated analysis
- Source anchors: [S26]

### R49 - Enforce least privilege and explicit permission paths
- Applies to: agentic, hybrid
- Required artifacts: sandbox mode, permission rules, destructive-action policy, escalation rules
- Why it matters: autonomous tooling without permission boundaries is unsafe.
- Failure prevented: accidental destructive behavior and overbroad access
- Source anchors: [S25]

### R50 - Convert repeated failures into documentation, tooling, or policy improvements
- Applies to: agentic, hybrid
- Required artifacts: failure log, updated docs/rules/tools, validation of the improvement
- Why it matters: repeated human intervention means the system has not learned yet.
- Failure prevented: paying the same coordination tax every run
- Source anchors: [S14] [S15] [S19]

### R51 - Treat evaluations as required infrastructure for prompt, model, and workflow changes
- Applies to: agentic, hybrid
- Required artifacts: eval set, regression checks, change note
- Why it matters: agent systems drift whenever prompts, models, tools, or policies change.
- Failure prevented: silent degradation masked by anecdotal wins
- Source anchors: [S17]

### R52 - Prefer agent-readable structure and mechanical invariants over taste-by-conversation
- Applies to: agentic, hybrid
- Required artifacts: structural checks, lint rules, boundary tests, repo conventions
- Why it matters: high-throughput agent systems stay coherent when the rules are encoded, not re-explained.
- Failure prevented: style drift, architecture erosion, and inconsistent outputs
- Source anchors: [S19]

### R52A - Use vendor-neutral handoff artifacts for cross-model interoperability
- Applies to: agentic, hybrid
- Required artifacts: task brief, current-state summary, exact file list, commands run, expected next action
- Why it matters: model changes and multi-model workflows only work when state is explicit and portable.
- Failure prevented: hidden-context handoffs and model-specific dead ends
- Source anchors: [S18] [S19] [S24]

### R52B - Define trust boundaries for agent inputs, secrets, and side effects
- Applies to: agentic, hybrid
- Required artifacts: trust-boundary policy, secret-handling rules, external-input policy, signoff rules for privileged actions
- Why it matters: fetched content, generated code, and third-party text are not safe to treat as privileged instructions.
- Failure prevented: prompt-injection-driven actions, secret exposure, and unsafe automated execution
- Source anchors: [S19] [S25]

## Recent 2025-2026 Developments and Unknown Unknowns

### R53 - Assume benchmark claims are provisional until reproduced on your own tasks
- Applies to: agentic, hybrid
- Required artifacts: local eval suite, benchmark interpretation note
- Why it matters: public coding benchmarks can be contaminated or misaligned with real work.
- Failure prevented: overtrusting leaderboard gains that do not transfer to production tasks
- Source anchors: [S22] [S23]

### R54 - Assume models, costs, and capabilities will drift; revalidate routing and prompts regularly
- Applies to: agentic, hybrid
- Required artifacts: review cadence for model routing, prompt/eval refresh
- Why it matters: model aliases, snapshots, and reasoning tradeoffs change over time.
- Failure prevented: stale optimization choices and degraded reliability
- Source anchors: [S20] [S21]

### R55 - Expect AI to amplify the organization you already have
- Applies to: agentic, hybrid
- Required artifacts: organizational capability review, improvement backlog
- Why it matters: AI multiplies both strengths and dysfunctions.
- Failure prevented: blaming the tool for systemic planning, governance, or quality failures
- Source anchors: [S14] [S15]

### R56 - Treat human attention as a scarce resource and design the delivery system around it
- Applies to: predictive, agile, hybrid, agentic
- Required artifacts: review strategy, automation strategy, escalation policy
- Why it matters: in modern delivery, the true critical path is often decision and review capacity.
- Failure prevented: human bottlenecks disguised as technical bottlenecks
- Source anchors: [S13] [S19]

## Appendix A - Artifact Checklist

| Artifact | Purpose |
| --- | --- |
| Mandate or charter | Defines authority, sponsor, and purpose |
| Success criteria | States what counts as done and valuable |
| Decision-rights map | Clarifies who decides what |
| Scope and exclusion statement | Prevents silent scope creep |
| WBS or backlog | Decomposes total work |
| Dependency map | Makes critical blockers visible |
| Schedule or roadmap | Connects work to time |
| Capacity and staffing plan | Aligns work to real capability |
| Budget model and reserve | Connects work to cost |
| Risk register | Tracks threats and opportunities |
| Issue log | Tracks active problems |
| Change log | Governs scope and plan changes |
| Acceptance criteria / DoD | Defines completion quality |
| Test strategy and evidence | Verifies and validates quality |
| User research plan and findings | Improves quality and value |
| Architecture and design records | Preserves technical intent |
| Environment and data setup docs | Enables reproducible execution |
| Release / rollback plan | Enables safe deployment |
| Runbooks and support handoff | Enables stable operation |
| Retrospective / lessons learned | Captures improvement actions |
| Execution plan (agentic) | Stores durable long-horizon task state |
| Rules / entry-point doc (agentic) | Guides agents into the right context |
| Eval suite (agentic) | Regresses behavior when models or prompts change |

## Appendix B - Delivery-Mode Mapping

| Mode | What stays fixed | What stays flexible | Typical control mechanism |
| --- | --- | --- | --- |
| Predictive | Scope, schedule, budget baselines | Local execution details | Formal planning and change control |
| Agile | Outcome intent and quality bar | Scope detail and sequencing | Backlog management plus inspect/adapt cadence |
| Hybrid | Governance, major milestones, key constraints | Near-term implementation detail | Rolling-wave planning and mixed controls |
| Agentic | Outcome, guardrails, acceptance, permissions | Internal execution path | File-backed plans, tool constraints, tests, evals |

## Appendix C - Question Coverage Map

| Original question | Primary rule coverage |
| --- | --- |
| Prerequisites for a software project | R05-R08 |
| Stages of a software project | R14, R25-R27, R40-R42 |
| How to plan the work | R16-R24 |
| How to map dependencies | R19 |
| How to hand off work and artifacts | R26-R27, R41 |
| How to map a critical path | R20 |
| How to plan resources | R07, R22 |
| How to budget time and cost | R23-R24 |
| How to scope work | R15-R17 |
| How to prepare the documentation | R03, R38-R39 |
| What documentation the project needs | Appendix A, R38-R39 |
| How to control progress | R28-R31 |
| How to estimate risks | R06, R29, R29A |
| How to mitigate risks | R29-R31, R29A |
| How to control quality | R32-R34, R34A |
| How to address scope changes | R31 |
| What processes ensure project success | R01-R04, R12-R14, R28-R31 |
| How to include learning loops for process improvement | R30, R37, R42, R50 |
| How to include feedback loops to refine scope | R30-R31, R36-R37 |
| How to include user testing to improve quality | R35 |
| How to include user testing to improve value | R36 |
| How and when to include agile practices | R09-R11 |
| How to run living project documentation | R38-R39 |
| How to use files to improve success probability | R03, R43-R45 |
| How to store tasks outside context windows | R43-R44 |
| How to ensure interoperability between models | R03, R43-R46, R52A |
| How to choose models to save tokens | R47, R54 |
| How to include tests in tasks | R17, R32-R33, R46, R51 |
| How to include learning loops in agent work | R50-R51, R55 |
| How to help models understand codebases | R45, R52 |
| How to manage context windows | R03, R38, R43-R45, R48 |
| How and when to use subagents | R48 |
| How to prepare work for autonomous agents | R43-R46, R49 |
| How to optimize processes | R30, R50, R52, R56, R34A |
| How to set guardrails | R49, R52, R52B |
| What else was missed | R06, R34, R34A, R40-R42, R53-R56, R52B |
| Latest AI coding-space good practices | R47-R56, R52A, R52B |
