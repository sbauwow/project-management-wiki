# Context Management

In AI-era project management, context is infrastructure.

The question is not whether to provide context. It is how to provide enough of the right context without burying the model or the reviewer.

## Three context layers

### 1. Durable context
Stable facts that rarely change:
- architecture
- conventions
- environment assumptions
- safety rules
- product vocabulary

### 2. Task context
What this task specifically needs:
- objective
- scope
- relevant files / systems
- exact acceptance criteria
- recent errors / evidence

### 3. Live state
Ephemeral facts:
- current branch
- failing tests
- open PRs
- production metrics
- currently staged diffs

Most failures happen when teams confuse these layers.

## Failure modes
- Too little context → hallucination, wrong assumptions
- Too much context → dilution, irrelevant wandering
- Stale context → confidently wrong execution
- Hidden context → reviewer cannot understand why work happened

## Good practice
- keep durable context in docs, memory, repo structure, or skills
- keep task context explicit in the assignment
- verify live state before acting
- strip irrelevant context aggressively

## Rule
A task should include the minimum context required for accurate execution, plus the evidence needed for verification.

Not more. Not less.
