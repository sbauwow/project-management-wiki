# Telemetry and Review Loops

If you cannot see the system, you cannot manage it.

AI project management needs observability not just for infrastructure, but for execution quality.

## What to measure

### Throughput
- slices completed
- cycle time
- queue age
- time from assignment to review

### Quality
- pass rate
- rework rate
- review rejection rate
- escaped defects

### Human load
- review minutes
- interruptions
- escalations
- approvals per operator

### Agent behavior
- retries
- tool failures
- context misses
- token / cost usage

## Review loop
Weekly, ask:
- what got done?
- where did work stall?
- what failure modes repeated?
- what should become a template, skill, or tool?
- what work should stop being delegated?

## Rule
Do not just instrument output volume. Cheap output can hide expensive correction.

The right question is: how much trustworthy progress did the system create per unit of human attention?
