# Issue Design and Task Schema Quality

A bad task creates bad execution, regardless of who does it. Humans work around vague tickets with conversation and intuition. Agents fail harder and more literally.

## Core idea

Issue quality is execution quality.

A strong issue or task schema gives enough structure that the assignee can act without guessing the fundamentals.

## Good task fields
- objective
- scope boundaries
- inputs / references
- constraints
- expected output
- verification method
- owner
- dependencies
- approval requirements
- definition of done

## Why this matters more with agents

Agents are highly sensitive to:
- missing context
- ambiguous success conditions
- implicit assumptions
- hidden dependencies
- unclear file/system boundaries

Poorly designed tasks produce:
- hallucinated requirements
- overbroad edits
- repeated clarification loops
- brittle outputs that fail review

## What good PMs do
- design issues as executable contracts
- separate problem statement from implementation suggestion
- define what must be preserved, not just what should change
- include exact artifacts and verification commands where possible
- keep one issue focused on one coherent outcome

## Failure modes
- tickets that are really just titles
- stuffing multiple decisions into one issue
- no acceptance criteria
- no indication of risk or approval needs
- no distinction between exploratory work and committed execution

## Practical rule

If two competent operators would interpret a task in meaningfully different ways, the issue is not ready.
