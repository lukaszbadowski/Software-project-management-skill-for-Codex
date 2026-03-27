# Source Log

Access date for all entries: `2026-03-27`

This log records the primary sources used to build the `software-project-management` skill. Source IDs are referenced from the bundled note files and the master rulebook.

## Table of Contents
- Solo Operator and Constraint Guidance
- AI-Agent Operating Practice
- Source Prioritization Rule

## Solo Operator and Constraint Guidance

### S01 - Agile Manifesto
- Type: Official framework source
- URL: <https://agilemanifesto.org/>
- Why trusted: Primary source from the original Agile Manifesto authors.
- Questions answered: Agile principles, mindset, value system, why iterative delivery and change-friendly practices matter.
- Notes on paywall or uncertainty: Public and stable. High-level values, not a full operating model.

### S02 - Principles Behind the Agile Manifesto
- Type: Official framework source
- URL: <https://agilemanifesto.org/principles.html>
- Why trusted: Primary source for the twelve agile principles.
- Questions answered: Feedback loops, changing scope, continuous delivery, sustainable pace, continuous improvement.
- Notes on paywall or uncertainty: Public and stable. Principles require interpretation for specific delivery systems.

### S03 - Scrum Guide 2020
- Type: Official framework guide
- URL: <https://scrumguides.org/docs/scrumguide/v2020/2020-Scrum-Guide-US.pdf>
- Why trusted: Official definition of Scrum by Ken Schwaber and Jeff Sutherland.
- Questions answered: Empiricism, backlog management, inspection, adaptation, and practical feedback-loop structure.
- Notes on paywall or uncertainty: Public PDF. Team-role content is not imported directly into the solo-operator skill.

### S04 - PMI PMBOK Guide
- Type: Official standard overview
- URL: <https://www.pmi.org/standards/pmbok>
- Why trusted: PMI’s current flagship standard overview.
- Questions answered: Value delivery, tailoring, scope, schedule, finance, procurement, risk, and release-related constraints.
- Notes on paywall or uncertainty: Overview is public; the full guide is member-gated or purchasable. Use as a canonical anchor, not a sole source of procedural detail.

### S05 - PMI Process Groups: A Practice Guide
- Type: Official practice guide overview
- URL: <https://www.pmi.org/standards/process-groups>
- Why trusted: Current PMI process-based guide for predictive delivery.
- Questions answered: Initiating, planning, executing, monitoring and controlling, closing; minimal predictive controls for real external commitments.
- Notes on paywall or uncertainty: Public overview, full guide gated.

### S06 - PMI Agile Practice Guide
- Type: Official practice guide overview
- URL: <https://www.pmi.org/standards/agile>
- Why trusted: PMI guide developed with Agile Alliance.
- Questions answered: Life-cycle selection, tailoring agile approaches, empirical measures, and hybrid framing.
- Notes on paywall or uncertainty: Public overview, full guide gated.

### S07 - PMI Work Breakdown Structures - Third Edition
- Type: Official standard overview
- URL: <https://www.pmi.org/standards/work-breakdown-structures-third-edition>
- Why trusted: PMI’s standard on decomposition and scope structuring.
- Questions answered: Scoping, decomposition, schedule/resource/risk linkage, cross-lifecycle applicability.
- Notes on paywall or uncertainty: Public overview, full guide gated.

### S08 - PMI Practice Standard for Scheduling - Third Edition
- Type: Official practice guide overview
- URL: <https://www.pmi.org/standards/scheduling-third-edition>
- Why trusted: PMI’s scheduling practice standard.
- Questions answered: Schedule models, critical path, rolling-wave planning, Monte Carlo, adaptive scheduling.
- Notes on paywall or uncertainty: Public overview, full guide gated.

### S09 - PMI Requirements Management: A Practice Guide
- Type: Official practice guide overview
- URL: <https://www.pmi.org/standards/requirements-management>
- Why trusted: PMI’s dedicated requirements guide.
- Questions answered: Requirements development, requirements management, acceptance framing, benefits and outcomes linkage.
- Notes on paywall or uncertainty: Public overview, full guide gated.

### S10 - PMI Risk Management in Portfolios, Programs, and Projects
- Type: Official practice guide overview
- URL: <https://www.pmi.org/standards/risk-management-in-portfolios>
- Why trusted: Current PMI practice guide focused on risk management principles and lifecycle.
- Questions answered: Risk identification, analysis, mitigation, opportunity capture, ongoing risk management.
- Notes on paywall or uncertainty: Public overview, full guide gated.

### S11 - GOV.UK Service Manual: User Research
- Type: Official government delivery guidance
- URL: <https://www.gov.uk/service-manual/user-research>
- Why trusted: Mature public-sector delivery guidance based on repeated service-delivery practice.
- Questions answered: Planning user research, research cadence by phase, usability testing, continuous discovery, sharing findings.
- Notes on paywall or uncertainty: Public. Written for digital services but broadly applicable to software delivery.

### S12 - GOV.UK Service Manual: Agile Delivery
- Type: Official government delivery guidance
- URL: <https://www.gov.uk/service-manual/agile-delivery>
- Why trusted: Mature public-sector agile delivery guidance with governance, progress reporting, and phased delivery detail.
- Questions answered: Agile planning, progress reporting, roadmap use, phased delivery, and practical adaptation.
- Notes on paywall or uncertainty: Public. Strong on service delivery and progress control, lighter on engineering detail.

### S13 - DORA State of AI-assisted Software Development 2025
- Type: Official research report overview
- URL: <https://dora.dev/research/2025/dora-report/>
- Why trusted: Research program run by Google Cloud’s DORA team.
- Questions answered: How AI affects delivery systems, organizational amplifiers, why tooling alone is insufficient, latest good practices in AI-assisted delivery.
- Notes on paywall or uncertainty: Report download is public. Findings are research-backed but still require local validation.

### S14 - DORA AI Capabilities Model 2025
- Type: Official research companion guide
- URL: <https://dora.dev/ai/capabilities-model/report/>
- Why trusted: Companion guide to DORA’s 2025 report with implementation-oriented capability framing.
- Questions answered: Continuous improvement capabilities, monitoring progress, and delivery-system prerequisites for AI-assisted delivery.
- Notes on paywall or uncertainty: Public overview and report download.

## AI-Agent Operating Practice

### S15 - OpenAI Prompt Caching Guide
- Type: Official API guide
- URL: <https://platform.openai.com/docs/guides/prompt-caching>
- Why trusted: Official OpenAI guidance on cache behavior and prompt structure for cost and latency control.
- Questions answered: Token saving, prompt structure, static-prefix design, cost-aware model usage.
- Notes on paywall or uncertainty: Public docs. Applies to API behavior, not every vendor.

### S16 - OpenAI Working with Evals
- Type: Official API guide
- URL: <https://developers.openai.com/api/docs/guides/evals>
- Why trusted: Official OpenAI evaluation workflow guidance.
- Questions answered: How to test workflows, why evals matter when prompts/models change, regression control for agent systems.
- Notes on paywall or uncertainty: Public docs. Evals still need local task design.

### S17 - OpenAI Cookbook: Using PLANS.md for Multi-hour Problem Solving
- Type: Official cookbook article
- URL: <https://developers.openai.com/cookbook/articles/codex_exec_plans>
- Why trusted: Official OpenAI cookbook guidance for long-horizon agent work.
- Questions answered: How to store tasks outside the context window, what execution plans should contain, progress logs, decision logs, evidence capture.
- Notes on paywall or uncertainty: Public. Cookbook guidance is practical rather than normative.

### S18 - OpenAI Harness Engineering: Leveraging Codex in an Agent-first World
- Type: Official engineering blog post
- URL: <https://openai.com/index/harness-engineering/>
- Why trusted: First-party operational write-up from OpenAI’s own agent-first engineering experiment.
- Questions answered: File-based memory, repository-as-system-of-record, doc gardening, guardrails, observability, autonomous work preparation, recurring cleanup loops.
- Notes on paywall or uncertainty: Public. Describes OpenAI’s internal setup, so adapt the principles rather than copying the exact implementation.

### S19 - OpenAI GPT-5.1 Model Guide Page
- Type: Official model page
- URL: <https://developers.openai.com/api/docs/models/gpt-5.1>
- Why trusted: Current official model reference.
- Questions answered: Reasoning-effort controls, task-model fit, cost/latency tradeoffs, snapshot drift awareness.
- Notes on paywall or uncertainty: Public. Specific model rankings change over time.

### S20 - OpenAI codex-mini-latest Model Page
- Type: Official model page
- URL: <https://developers.openai.com/api/docs/models/codex-mini-latest>
- Why trusted: Official page for a lower-cost coding-oriented model.
- Questions answered: When to use a cheaper/faster model for localized work and lower-stakes tasks.
- Notes on paywall or uncertainty: Public. Alias behavior can change as the model updates.

### S21 - OpenAI SWE-Lancer Benchmark
- Type: Official research benchmark
- URL: <https://openai.com/index/swe-lancer/>
- Why trusted: First-party benchmark focused on real-world freelance engineering tasks.
- Questions answered: Real-task evaluation framing, end-to-end tests, economic framing, why practical task design matters.
- Notes on paywall or uncertainty: Public overview and linked paper/repo. Benchmark results should still be treated as directional.

### S22 - OpenAI: Why SWE-bench Verified No Longer Measures Frontier Coding Capabilities
- Type: Official research analysis
- URL: <https://openai.com/index/why-we-no-longer-evaluate-swe-bench-verified/>
- Why trusted: First-party analysis of a widely used public benchmark.
- Questions answered: Benchmark contamination, flawed tests, evaluation limits, why benchmark wins can mislead.
- Notes on paywall or uncertainty: Public. Discusses benchmark health as of 2026-02-23.

### S23 - Anthropic Claude Code Memory Docs
- Type: Official product docs
- URL: <https://docs.anthropic.com/en/docs/claude-code/memory>
- Why trusted: Official guidance on project memory and rule loading.
- Questions answered: Persistent file-backed memory, keeping index files short, path-scoped rules, managing durable context.
- Notes on paywall or uncertainty: Public docs for Claude Code specifically, but the file-backed-memory pattern generalizes.

### S24 - Anthropic Claude Code Hooks Docs
- Type: Official product docs
- URL: <https://docs.anthropic.com/en/docs/claude-code/hooks>
- Why trusted: Official docs on guardrails and permission mediation.
- Questions answered: Permission interception, policy hooks, allow/ask/deny flows, tool restrictions, runtime guardrails.
- Notes on paywall or uncertainty: Public docs. Implementation is product-specific; the least-privilege principle is general.

### S25 - Anthropic Claude Code Subagents Docs
- Type: Official product docs
- URL: <https://docs.anthropic.com/en/docs/claude-code/sub-agents>
- Why trusted: Official docs on scoped delegation and context isolation.
- Questions answered: When to use subagents, isolating high-volume output, fresh context, tool scoping.
- Notes on paywall or uncertainty: Public docs. Feature names are vendor-specific, but the operating pattern generalizes.

### S26 - OpenAI Codex Best Practices
- Type: Official product docs
- URL: <https://developers.openai.com/codex/learn/best-practices>
- Why trusted: Official Codex guidance for effective agentic software development workflows.
- Questions answered: Plan-first workflows, reusable instructions, testing and review loops, configuration pitfalls, and practical reliability patterns.
- Notes on paywall or uncertainty: Public docs. Recommendations evolve as Codex features change.

### S27 - OpenAI Custom Instructions with AGENTS.md
- Type: Official product docs
- URL: <https://developers.openai.com/codex/guides/agents-md>
- Why trusted: Official documentation for Codex instruction-file discovery and layering.
- Questions answered: How to structure reusable instructions, layer repo and directory overrides, and keep instruction files practical.
- Notes on paywall or uncertainty: Public docs. Filename and config details may evolve.

### S28 - OpenAI Codex Hooks
- Type: Official product docs
- URL: <https://developers.openai.com/codex/hooks>
- Why trusted: Official documentation for deterministic hook-based automation in Codex.
- Questions answered: How to run validators automatically, enforce standards, and attach policy scripts to Codex lifecycle events.
- Notes on paywall or uncertainty: Public docs. Hooks are marked experimental and behavior may change.

### S29 - OpenAI Codex Workflows
- Type: Official product docs
- URL: <https://developers.openai.com/codex/workflows>
- Why trusted: Official workflow guidance for common Codex software-development tasks.
- Questions answered: Reproduction-and-verification loops, local review patterns, milestone-based refactors, and staged cloud delegation.
- Notes on paywall or uncertainty: Public docs. Workflow examples are illustrative and should be adapted locally.

### S30 - OpenAI Codex Subagents
- Type: Official product docs
- URL: <https://developers.openai.com/codex/subagents>
- Why trusted: Official documentation for Codex subagent orchestration.
- Questions answered: When to use subagents, explicit spawning, parallel review passes, and sandbox inheritance.
- Notes on paywall or uncertainty: Public docs. Operational tradeoffs such as token cost still need local judgment.

### S31 - OpenAI GPT-5.2-Codex Model Page
- Type: Official model reference
- URL: <https://developers.openai.com/api/docs/models/gpt-5.2-codex>
- Why trusted: Current official model page for OpenAI's long-horizon coding model.
- Questions answered: Model fit for long-horizon coding, reasoning-effort controls, and context-window characteristics.
- Notes on paywall or uncertainty: Public docs. Model aliases, prices, and comparative positioning can change over time.

### S32 - Anthropic Best Practices for Claude Code
- Type: Official product docs
- URL: <https://code.claude.com/docs/en/best-practices>
- Why trusted: Official Anthropic guidance on effective Claude Code workflows.
- Questions answered: Verification-first prompting, explore-plan-code sequencing, concise instruction files, fresh-context review patterns, and scale-out practices.
- Notes on paywall or uncertainty: Public docs. Product workflows and command names can change.

### S33 - Anthropic Claude Code Security
- Type: Official product docs
- URL: <https://code.claude.com/docs/en/security>
- Why trusted: Official Anthropic security guidance for Claude Code usage.
- Questions answered: Prompt-injection protections, permission boundaries, external-content risks, and safe handling of sensitive code.
- Notes on paywall or uncertainty: Public docs. Security features and defaults may change as the product evolves.

## Source Prioritization Rule
- Official framework owners and official vendor docs were used first.
- Primary research and benchmark owners were used second.
- Secondary sources were used only to find primary material, not as the basis for claims in the research pack.
