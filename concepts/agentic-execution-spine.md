# Agentic Execution Spine

This is the practical operating loop for AI-era project management.

## Spine

1. Clarify objective
2. Define constraints
3. Decompose work
4. Route slices to humans or agents
5. Execute
6. Review / approve
7. Measure what happened
8. Distill the learning back into the system

Without step 8, the organization stays stupid.

## Step 1 — clarify objective
Good objective:
- outcome-shaped
- measurable
- bounded in time
- clear owner

Bad objective:
- “improve product”
- “use AI more”
- “move faster”

## Step 2 — define constraints
Every execution loop needs:
- scope boundaries
- acceptable tools
- quality bar
- time budget
- approval requirements
- rollback path

## Step 3 — decompose work
The key move is turning a fuzzy initiative into executable slices.

A good slice is:
- independently testable
- low-coupling
- reviewable
- small enough for an agent to execute cleanly

## Step 4 — route ownership
Ask:
- does this require judgment?
- is the blast radius high?
- can output be verified cheaply?
- is the task mostly mechanical?

That determines human-owned vs agent-owned.

## Step 5 — execute
Execution should happen in parallel when slices are independent.

Do not parallelize:
- decisions that depend on the same unresolved ambiguity
- work that collides in one file/module without coordination
- high-stakes production actions without review gates

## Step 6 — review / approve
Review is where quality is created.

A review system needs:
- clear acceptance criteria
- known approver
- review SLA
- explicit pass / fail / revise outcomes

## Step 7 — telemetry
Track:
- cycle time
- number of retries
- human review minutes
- pass rate
- rollback rate
- cost per completed slice

## Step 8 — distill
Turn repeated patterns into:
- templates
- playbooks
- prompts
- skills
- tooling improvements

This is how you convert one-off execution into durable leverage.
