# Work Decomposition for Agents

Agent quality is mostly a decomposition problem.

If the work unit is too large, too ambiguous, or too coupled, the model looks dumb. The real failure is upstream.

## A good agent-ready work unit
It should be:
- bounded
- specific
- grounded in known context
- independently verifiable
- low in hidden dependencies

## A bad work unit
Examples:
- “fix the codebase”
- “make this enterprise-ready”
- “figure out product strategy and implement it”

These are management failures disguised as assignments.

## Decomposition ladder

### Level 1 — initiative
Example:
- launch bilingual product surface for Chinese users

### Level 2 — workstreams
Example:
- locale architecture
- UI translation
- QA / regression coverage
- analytics / rollout measurement

### Level 3 — slices
Example:
- add locale cookie handling
- translate nav copy
- add tests for locale route
- verify production redirects

### Level 4 — execution units
Example:
- patch route
- run focused test
- validate redirect header
- commit cleanly

Agents should mostly receive level 3 or level 4 work.

## Heuristics

Split when:
- one task touches too many systems
- review requires different expertise
- failure is hard to localize
- output cannot be verified in one place

Do not oversplit into pure overhead. The unit should still be meaningful.

## Smell test
If the assignee would need to ask three clarifying questions before starting, the work is not decomposed enough.
