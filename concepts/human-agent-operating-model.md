# Human-Agent Operating Model

The core question in AI project management is not “what can the model do?” It is “what should humans own, what should agents own, and what sits between them?”

## Principle

Humans should own:
- goal selection
- ambiguity resolution
- irreversible decisions
- accountability
- exception handling
- approval of high-stakes changes

Agents should own:
- synthesis of large context
- repetitive execution
- draft generation
- mechanical verification
- option generation
- background monitoring

If you reverse this split, you either get unsafe autonomy or expensive bureaucracy.

## The four ownership zones

### 1. Human-owned
Use for:
- strategy
- prioritization
- legal / financial / reputational decisions
- hiring / firing / compensation
- production actions with major blast radius

### 2. Agent-owned
Use for:
- code generation in bounded scopes
- research aggregation
- issue drafting
- migration checklists
- repetitive QA passes
- report generation

### 3. Joint-owned
Use for:
- architecture proposals
- product scoping
- incident triage
- roadmap shaping
- PR review and refinement

### 4. Escalation-only
Use for:
- strange failures
- contradictory evidence
- unclear requirements
- repeated retries
- evidence of policy mismatch

## Failure pattern

Most teams fail because they never formalize ownership. Then every bad output becomes a moral panic instead of an operating-model bug.

## Practical rule

If a task requires:
- hard judgment under ambiguity
- external accountability
- high downside if wrong

...default human-owned.

If a task is:
- bounded
- reviewable
- repeatable
- tool-grounded

...default agent-owned.
