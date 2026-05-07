# Project Management Wiki

A first-principles reference for modern project management in the age of AI. Dense, hyperlinked, opinionated. This is a cousin to the product-discovery-wiki: that repo is about deciding what to build; this one is about turning chosen work into reliable execution.

> Discovery asks: what should we build and why? Project management asks: how do we turn goals into finished outcomes with acceptable cost, risk, speed, and coordination load? In the age of AI, that means managing humans, agents, workflows, approvals, context, and feedback loops — not just tasks and timelines.

---

## Mental model

```
                    Strategy / Objective        ← what winning means
                           │
                    Portfolio / Bets            ← what deserves attention
                           │
                    Program / Workstream        ← grouped outcomes
                           │
                  Backlog / Decision Queue      ← candidate work
                           │
               ┌───────────┴───────────┐
         Human-owned                Agent-owned
         ambiguity, stakes          throughput, execution
               │                         │
         decomposition           delegation / automation
               └───────────┬───────────┘
                           │
                  review / approval gates       ← safety + quality
                           │
                   telemetry / evidence         ← what actually happened
                           │
                    synthesis / learning        ← update plans, systems, prompts
```

Top-down: strategy → portfolio → workstreams → execution. Bottom-up: evidence and learning reshape plans weekly.

---

## Core idea

Project management in the age of AI is about six things:

1. Choosing and sequencing the right work
2. Decomposing it into slices humans and agents can actually execute
3. Managing dependencies, approvals, and context so quality holds
4. Exploiting parallelism without creating merge hell or review collapse
5. Measuring what happened instead of trusting status theater
6. Turning execution cycles into reusable systems, not one-off heroics

If you only bolt AI onto a Gantt chart, you get faster confusion.

---

## Core concepts

### Operating model
- [Human-Agent Operating Model](concepts/human-agent-operating-model.md) — who owns what, where agents help, and where human judgment remains decisive
- [Agentic Execution Spine](concepts/agentic-execution-spine.md) — the end-to-end loop from objective → decomposition → execution → review → learning
- [Portfolio in the Age of AI](concepts/portfolio-in-the-age-of-ai.md) — how portfolios change when execution gets cheaper but attention stays scarce
- [Operating Cadence](concepts/operating-cadence.md) — daily, weekly, and milestone rhythms for staying aligned without drowning in meetings

### Work design
- [Work Decomposition for Agents](concepts/work-decomposition-for-agents.md) — how to slice work into tickets, modules, prompts, and review points that agents can execute reliably
- [Parallelism and Orchestration](concepts/parallelism-and-orchestration.md) — when to run many agents or teams in parallel, and how to recombine outputs safely
- [Dependencies and Critical Path](concepts/dependencies-and-critical-path.md) — the real constraint layer underneath optimistic planning
- [Resource Allocation in the Age of AI](concepts/resource-allocation-in-the-age-of-ai.md) — what changes when execution labor is abundant but oversight, taste, and decision bandwidth are not
- [Issue Design and Task Schema Quality](concepts/issue-design-and-task-schema-quality.md) — how to write executable work units instead of vague tickets
- [Project Estimation Under AI Uncertainty](concepts/project-estimation-under-ai-uncertainty.md) — how to estimate generation, review, integration, and rework instead of pretending one number is enough

### Information architecture
- [Context Management](concepts/context-management.md) — how to feed the right information to humans and agents without drowning either
- [Decision Logs](concepts/decision-logs.md) — preserving why choices were made so execution does not re-litigate everything
- [Knowledge Capture and Distillation](concepts/knowledge-capture-and-distillation.md) — how completed work becomes durable memory, templates, and playbooks instead of disappearing into chat logs
- [Prompt and Policy Versioning](concepts/prompt-and-policy-versioning.md) — prompts, rubrics, and approval rules as versioned execution infrastructure

### Control systems
- [Approval and Safety Gates](concepts/approval-and-safety-gates.md) — where human approval belongs and how to avoid both reckless autonomy and pointless friction
- [Telemetry and Review Loops](concepts/telemetry-and-review-loops.md) — observability for project execution: throughput, quality, latency, review load, rework, failure modes
- [Risk Management in Agentic Systems](concepts/risk-management-in-agentic-systems.md) — managing operational, legal, security, and quality risks when execution is partially autonomous
- [Review Capacity as a Bottleneck](concepts/review-capacity-as-a-bottleneck.md) — why verification, not generation, often sets real throughput
- [Status Theater vs Truth Reporting](concepts/status-theater-vs-truth-reporting.md) — how to report the state of work honestly instead of cosmetically
- [Project Management Anti-Patterns in Agentic Orgs](concepts/project-management-anti-patterns-in-agentic-orgs.md) — recurring execution failures amplified by AI

---

## Practical workflows
- [Agentic Execution Spine](concepts/agentic-execution-spine.md) — the practical operating backbone
- [Operating Cadence](concepts/operating-cadence.md) — the rhythm that keeps plans real
- [Work Decomposition for Agents](concepts/work-decomposition-for-agents.md) — turn ambiguous goals into executable slices
- [Issue Design and Task Schema Quality](concepts/issue-design-and-task-schema-quality.md) — define better units of execution
- [Dependencies and Critical Path](concepts/dependencies-and-critical-path.md) — identify what really blocks progress
- [Project Estimation Under AI Uncertainty](concepts/project-estimation-under-ai-uncertainty.md) — estimate the full loop, not just first-pass generation
- [Context Management](concepts/context-management.md) — make execution grounded instead of hallucinated
- [Approval and Safety Gates](concepts/approval-and-safety-gates.md) — install the right brakes
- [Telemetry and Review Loops](concepts/telemetry-and-review-loops.md) — measure what happened
- [Review Capacity as a Bottleneck](concepts/review-capacity-as-a-bottleneck.md) — monitor the hidden queue that governs throughput
- [Decision Logs](concepts/decision-logs.md) — reduce rediscovery and re-debate
- [Prompt and Policy Versioning](concepts/prompt-and-policy-versioning.md) — keep operational rules stable and auditable
- [Knowledge Capture and Distillation](concepts/knowledge-capture-and-distillation.md) — convert work into organizational memory

---

## Start here if you're building an AI-native execution system

Read in this order:
1. [Human-Agent Operating Model](concepts/human-agent-operating-model.md)
2. [Agentic Execution Spine](concepts/agentic-execution-spine.md)
3. [Work Decomposition for Agents](concepts/work-decomposition-for-agents.md)
4. [Issue Design and Task Schema Quality](concepts/issue-design-and-task-schema-quality.md)
5. [Dependencies and Critical Path](concepts/dependencies-and-critical-path.md)
6. [Context Management](concepts/context-management.md)
7. [Approval and Safety Gates](concepts/approval-and-safety-gates.md)
8. [Review Capacity as a Bottleneck](concepts/review-capacity-as-a-bottleneck.md)
9. [Telemetry and Review Loops](concepts/telemetry-and-review-loops.md)
10. [Decision Logs](concepts/decision-logs.md)
11. [Knowledge Capture and Distillation](concepts/knowledge-capture-and-distillation.md)

---

## Reading order (if new)
1. [Human-Agent Operating Model](concepts/human-agent-operating-model.md) — the philosophical prerequisite
2. [Agentic Execution Spine](concepts/agentic-execution-spine.md) — the workflow skeleton
3. [Work Decomposition for Agents](concepts/work-decomposition-for-agents.md) — how to structure execution
4. [Issue Design and Task Schema Quality](concepts/issue-design-and-task-schema-quality.md) — how to create executable work units
5. [Dependencies and Critical Path](concepts/dependencies-and-critical-path.md) — what actually constrains delivery
6. [Context Management](concepts/context-management.md) — how to make execution reliable
7. [Approval and Safety Gates](concepts/approval-and-safety-gates.md) — how to prevent damage
8. [Review Capacity as a Bottleneck](concepts/review-capacity-as-a-bottleneck.md) — why throughput often dies at verification
9. [Parallelism and Orchestration](concepts/parallelism-and-orchestration.md) — how to scale throughput
10. [Telemetry and Review Loops](concepts/telemetry-and-review-loops.md) — how to know what is real
11. [Decision Logs](concepts/decision-logs.md) — how not to forget why the plan exists
12. [Knowledge Capture and Distillation](concepts/knowledge-capture-and-distillation.md) — how the system gets smarter over time

---

## Reading order (if practitioner)
- **Operating system first** → [Human-Agent Operating Model](concepts/human-agent-operating-model.md) → [Agentic Execution Spine](concepts/agentic-execution-spine.md) → [Operating Cadence](concepts/operating-cadence.md)
- **Execution quality** → [Work Decomposition for Agents](concepts/work-decomposition-for-agents.md) → [Issue Design and Task Schema Quality](concepts/issue-design-and-task-schema-quality.md) → [Context Management](concepts/context-management.md) → [Approval and Safety Gates](concepts/approval-and-safety-gates.md)
- **Flow control** → [Dependencies and Critical Path](concepts/dependencies-and-critical-path.md) → [Project Estimation Under AI Uncertainty](concepts/project-estimation-under-ai-uncertainty.md) → [Parallelism and Orchestration](concepts/parallelism-and-orchestration.md)
- **Management layer** → [Decision Logs](concepts/decision-logs.md) → [Status Theater vs Truth Reporting](concepts/status-theater-vs-truth-reporting.md) → [Risk Management in Agentic Systems](concepts/risk-management-in-agentic-systems.md) → [Telemetry and Review Loops](concepts/telemetry-and-review-loops.md)
- **Scale failure modes** → [Review Capacity as a Bottleneck](concepts/review-capacity-as-a-bottleneck.md) → [Project Management Anti-Patterns in Agentic Orgs](concepts/project-management-anti-patterns-in-agentic-orgs.md)
- **Long-term leverage** → [Prompt and Policy Versioning](concepts/prompt-and-policy-versioning.md) → [Knowledge Capture and Distillation](concepts/knowledge-capture-and-distillation.md) → [Portfolio in the Age of AI](concepts/portfolio-in-the-age-of-ai.md) → [Resource Allocation in the Age of AI](concepts/resource-allocation-in-the-age-of-ai.md)

---

## Glossary
See [glossary.md](glossary.md) for one-line definitions of the core terms used across the wiki.
