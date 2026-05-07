# Dependencies and Critical Path

Most project plans fail because they describe work, not constraints. Dependencies and critical path are the constraint layer.

## Dependency

A dependency exists when one task cannot start, finish, or validate until another task or decision is complete.

Common types:
- technical dependency
- approval dependency
- information dependency
- environment/tooling dependency
- sequencing dependency

## Critical path

The critical path is the longest dependency chain that determines the earliest possible completion date. Speeding up work off the critical path may feel productive, but it does not actually move the end date.

## Why this matters more with AI

AI increases cheap parallel work. That creates a temptation to fan out everything at once. But most programs are still constrained by:
- a small number of key decisions
- shared integration points
- limited review capacity
- hidden tool or environment bottlenecks

So the real skill is not maximizing activity. It is identifying what truly gates completion.

## Practical uses
- find the 2–5 blockers that actually determine schedule risk
- distinguish parallelizable work from fake parallelism
- protect scarce reviewer/integrator time
- avoid local optimization on low-leverage tasks

## Failure modes
- dependency blindness
- optimistic sequencing
- hidden approvals treated as "small details"
- too many subagents or contributors generating merge debt before core decisions are settled
- managers celebrating throughput that does not shorten cycle time

## Good operating habit

Every non-trivial project should maintain:
- a dependency map
- current critical path guess
- explicit blocked state
- owner for each blocking dependency

The critical path is a living hypothesis, not a one-time planning artifact.
