# Parallelism and Orchestration

AI makes parallel execution cheap. That does not mean parallelism is free.

Cheap execution often creates expensive coordination.

## Use parallelism when
- tasks are independent
- interfaces are stable
- merge points are known
- outputs can be compared or recombined cleanly

## Avoid parallelism when
- requirements are still moving
- multiple workers will fight over one artifact
- there is unresolved ambiguity at the top
- reviewers cannot absorb the output load

## The orchestration job
Orchestration means:
- assigning slices to the right workers
- passing enough context
- ensuring outputs are comparable
- reconciling conflicts
- deciding what becomes canonical

Without orchestration, “multi-agent” just means many disconnected drafts.

## Good orchestration primitives
- explicit goal per worker
- clear interface boundary
- one canonical integration owner
- shared acceptance criteria
- verification step between batches

## Common anti-pattern
Delegating three agents to overlapping code with vague instructions and then acting surprised at conflict. That is not scale. That is entropy.
