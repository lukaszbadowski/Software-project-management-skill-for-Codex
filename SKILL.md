---
name: software-project-management
description: Run software projects with predictive, agile, hybrid, and agent-assisted discipline. Use when Codex needs to plan, govern, rescue, or structure software delivery; choose a lifecycle; define scope, dependencies, critical path, resources, budget, risk, quality, user-testing loops, documentation, release readiness, or agent operating rules.
---

# Software Project Management

## Overview

Use this skill to turn vague software delivery work into a controlled project system. Build or repair the project operating model: lifecycle choice, source of truth, scope, dependencies, quality controls, feedback loops, and agent-specific guardrails.

## Quick Start

1. Inspect the workspace for existing project artifacts before inventing new ones.
2. Classify the work as predictive, agile, hybrid, or agent-assisted.
3. Create or repair the minimum control system: owner, scope, acceptance, plan, dependencies, risk/change controls, documentation, and release/support readiness.
4. Produce the lightest artifact set that still preserves control.

## Workflow

### Build Context First

- Extract the real objective, stakeholders, users, constraints, deadline, dependency landscape, quality bar, and release expectations.
- Look for an existing charter, roadmap, backlog, design docs, ADRs, test strategy, release plan, runbooks, risk log, and agent rule files.
- If important information is missing, make reasonable assumptions and record them explicitly.
- If the request is to rescue a project, diagnose the control system before proposing fixes: owner clarity, scope quality, dependency visibility, schedule realism, risk hygiene, quality controls, and release/support readiness.

### Choose the Delivery Mode

- Use predictive controls when scope is definable, approvals are heavy, dates are fixed, or late change is expensive.
- Use agile controls when learning and user feedback dominate.
- Use hybrid controls when governance and milestones are fixed but solution detail must evolve.
- Add agent-assisted controls whenever models or subagents will perform material delivery work.

### Create or Repair the Core Artifact Set

Always maintain these artifacts in some form:
- objective and success criteria
- named accountable owner and decision rights
- source-of-truth index
- scoped work breakdown or backlog
- acceptance and quality criteria
- dependency map
- risk, issue, and change controls
- documentation freshness path
- release, rollback, and support-handoff plan

Add these artifacts when needed:
- Predictive: baseline schedule, budget, milestone exits, formal change path, critical-path analysis
- Agile: product goal, prioritized backlog, sprint cadence, review cadence, retrospective cadence
- Agent-assisted: durable execution plan, agent instruction entry point, model/task routing, evals, permission rules, trust-boundary rules

### Plan and Govern the Work

- Plan at two levels: whole-project direction and near-term executable detail.
- Map dependencies explicitly, including approvals, vendors, environments, data, and cross-team work.
- Calculate and monitor a critical path whenever dates matter.
- Plan resources against bottlenecks and sustainable pace, not only headcount.
- Treat scope change as a trade-off decision, not as a free addition.
- Govern by cadence and evidence, not by status theater.

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

## Reference Files

- Read [references/project-rulebook.md](./references/project-rulebook.md) for the full rule system and coverage map.
- Read [references/pm-framework-notes.md](./references/pm-framework-notes.md) when choosing or tailoring predictive, agile, and hybrid controls.
- Read [references/ai-agent-practices.md](./references/ai-agent-practices.md) when planning file-backed memory, model routing, subagents, evals, and guardrails.
- Read [references/source-anchors.md](./references/source-anchors.md) when you need provenance, dated anchors, or a refresh point for unstable topics.
- Do not load every reference by default. Read the smallest relevant file first.

## Output Standards

- Write in imperative form.
- Prefer concrete artifacts and decision-ready outputs over generic PM advice.
- Make assumptions explicit whenever the workspace does not contain enough project context.
- Distinguish stable management practices from date-sensitive AI-vendor recommendations.
- If the user asks for the latest model, benchmark, or vendor workflow guidance, verify it externally before answering because the bundled source anchors are dated snapshots.
