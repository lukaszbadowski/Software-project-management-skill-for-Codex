---
name: software-project-management
description: Run LLM-first and hybrid software projects with clear scope, dependencies, tests, durable files, and guardrails. Use when Codex needs to plan, govern, rescue, or structure software delivery driven by models or subagents; choose which human-project controls are actually necessary; define scope, acceptance, dependencies, documentation, release readiness, evals, and agent operating rules.
---

# Software Project Management

## Overview

Use this skill to turn vague AI-assisted delivery work into a controlled execution system. Default to scope, acceptance, dependency sequencing, durable files, tests or evals, and permissions; add calendars, budgets, staffing, and stakeholder rituals only when external human constraints require them.

## Quick Start

1. Inspect the workspace for existing project artifacts before inventing new ones.
2. Classify the work as agentic-first, hybrid, or human-coordinated.
3. Create or repair the minimum control system: owner, scope, acceptance, work plan, dependencies, risk/change controls, documentation, and guardrails.
4. Produce the lightest artifact set that still preserves control.

## Workflow

### Build Context First

- Extract the real objective, users, constraints, dependency landscape, acceptance bar, and release expectations. Only treat deadlines, budgets, staffing, or stakeholder rituals as first-class inputs if the project actually has them.
- Look for an existing task brief, roadmap or execution plan, backlog, design docs, ADRs, test strategy, release plan, runbooks, risk log, and agent rule files.
- If important information is missing, make reasonable assumptions and record them explicitly.
- If the request is to rescue a project, diagnose the control system before proposing fixes: owner clarity, scope quality, dependency visibility, acceptance quality, risk hygiene, context legibility, tool permissions, and release or support readiness where relevant.

### Choose the Delivery Mode

- Default to agent-assisted controls when models or subagents perform most of the execution.
- Use predictive controls only when external approvals, release windows, budgets, or fixed commitments are real constraints.
- Use agile controls when learning and user feedback dominate and there is still meaningful human coordination around the work.
- Use hybrid controls when external interfaces are fixed but the solution detail must evolve.

### Create or Repair the Core Artifact Set

Always maintain these artifacts in some form:
- objective and success criteria
- named accountable owner or explicit decision path
- source-of-truth index
- scoped work breakdown or backlog
- acceptance and quality criteria
- dependency map
- durable execution plan or current-state note
- risk, issue, and change controls
- permission and trust-boundary rules
- documentation freshness path

Add these artifacts when needed:
- Predictive: baseline schedule, budget, milestone exits, formal change path, critical-path analysis
- Human-coordinated agile: product goal, prioritized backlog, inspect/adapt cadence, review cadence, retrospective cadence
- Agent-assisted: agent instruction entry point, model or task routing, evals, and explicit escalation rules
- Production delivery: release, rollback, and support-handoff plan

### Plan and Govern the Work

- Plan at two levels: whole-project direction and near-term executable detail. Only add long-range calendar plans when external commitments require them.
- Map dependencies explicitly, including approvals, vendors, environments, data, and cross-team work.
- Calculate and monitor a critical path only when external deadlines, approvals, or scarce shared bottlenecks make it useful.
- Plan scarce resources only when they constrain throughput: review bandwidth, CI capacity, API quotas, model budget, or human bottlenecks.
- Treat scope change as a trade-off decision, not as a free addition.
- Govern by evidence and explicit triggers, using cadence only where it improves control.

### Control Quality, Value, and Learning

- Separate user testing for product quality from user research for product value.
- Treat non-functional requirements as release criteria, not deferred polish.
- Keep documentation living: versioned, owned, refreshed, and retired when stale.
- Turn repeated failures into process, tooling, documentation, or policy improvements.

### Extend the System for Agent-Assisted Delivery

- Keep durable task state in files, not only in chat.
- Keep entry-point instructions short and navigational.
- Use vendor-neutral handoff artifacts so different models can continue work safely.
- Use subagents only for bounded parallel work or high-volume output.
- Enforce least privilege, secret-handling rules, trust boundaries, and explicit approvals for risky actions.
- Revalidate prompts, models, and workflows with evals when behavior or tooling changes.

## Common Deliverables

- project operating plan
- project rescue assessment
- artifact checklist tailored to lifecycle
- dependency and critical-path analysis
- risk, quality, and release-control plan
- agentic execution and guardrail plan
- human-coordination extension, only when external teams or approvals matter

## Reference Files

- Read [references/project-rulebook.md](./references/project-rulebook.md) for the full rule system and coverage map.
- Read [references/pm-framework-notes.md](./references/pm-framework-notes.md) only when human coordination, external approvals, fixed calendars, or organizational budgeting matter.
- Read [references/ai-agent-practices.md](./references/ai-agent-practices.md) when planning file-backed memory, model routing, subagents, evals, and guardrails.
- Read [references/source-anchors.md](./references/source-anchors.md) when you need provenance, volatile vendor anchors, or a refresh point for unstable topics.
- Do not load every reference by default. Read the smallest relevant file first.

## Output Standards

- Write in imperative form.
- Prefer concrete artifacts and decision-ready outputs over generic PM advice.
- Make assumptions explicit whenever the workspace does not contain enough project context.
- Distinguish stable control practices from volatile vendor recommendations.
- Do not introduce schedules, budgets, staffing plans, stakeholder cadences, or stage gates unless the project genuinely depends on them.
- If the user asks for the latest model, benchmark, or vendor workflow guidance, verify it externally before answering because the bundled source anchors are point-in-time snapshots.
