# Decision Logs

A decision log is a durable record of important choices: what was decided, why, by whom, when, and under what assumptions.

Teams forget fast. Agents forget instantly unless the context is re-supplied. Decision logs prevent rediscovery, re-litigation, and incoherent execution.

## What belongs in a decision log
- the decision itself
- alternatives considered
- rationale
- constraints or assumptions
- owner / decider
- date
- consequences / follow-up

## Why it matters in AI-heavy execution

Agents can execute quickly, but they are bad at reconstructing invisible organizational reasoning unless it is written down. If the why is missing, the system drifts:
- old decisions get reversed accidentally
- new contributors duplicate rejected paths
- prompts optimize for local output instead of the real intent

## When to log
Log decisions when they affect:
- architecture
- scope
- safety or approval boundaries
- prioritization
- workflow design
- user-facing commitments
- irreversible or expensive choices

## Benefits
- less churn
- faster onboarding
- better prompt/context quality
- cleaner retrospectives
- fewer circular debates

## Failure modes
- logging trivial choices and creating noise
- recording outcomes but not rationale
- not linking the log to the work artifacts it governs
- treating the decision log as archival paperwork instead of a living control surface

## Minimal template
- Decision:
- Date:
- Decider(s):
- Context:
- Options considered:
- Chosen path:
- Why:
- Risks / tradeoffs:
- Revisit trigger:

A good decision log is lightweight but searchable. If people cannot find it during execution, it does not exist.
