# Project Estimation Under AI Uncertainty

AI changes estimation, but it does not eliminate it. It compresses some work, expands other work, and makes old intuition less reliable.

Traditional estimates assumed execution labor was the main constraint. In AI-heavy systems, raw production can get faster while review, integration, decision latency, and rework become the real schedule drivers.

## Core idea

Estimate the whole control loop, not just first-pass output generation.

That means accounting for:
- decomposition quality
- context prep
- agent execution time
- review time
- defect/rework rate
- integration cost
- approval latency
- hidden dependency risk

## What gets easier to estimate
- repetitive drafting
- boilerplate code or docs
- standard research collection
- transformation pipelines with clear validation rules

## What gets harder to estimate
- ambiguous requirements
- cross-functional coordination
- integration-heavy work
- safety-sensitive changes
- novel tasks with no stable workflow
- anything where verification is more expensive than generation

## Better estimation questions
Instead of asking only "how long will this take?", ask:
- how much of this is execution vs judgment?
- what percent can be parallelized safely?
- where are the likely review bottlenecks?
- what is the expected rework rate?
- what assumptions would break this estimate fastest?

## Good practice
Use range estimates with explicit drivers:
- optimistic: assumptions hold, low rework, reviews fast
- expected: normal review/integration friction
- pessimistic: hidden dependencies or high rescue load

Also separate:
- first-pass completion
- validated completion
- deployed / accepted completion

AI often shrinks the first number and leaves the last two mostly intact.

## Failure modes
- quoting agent runtime as project duration
- ignoring approval or review queues
- pretending parallel work is free
- underestimating context setup
- not updating estimates after the first 20 percent of execution reveals the real shape of the work

## Practical rule

Estimate in layers:
1. generation
2. verification
3. integration
4. acceptance

If those are collapsed into one number, the estimate is probably fiction.
