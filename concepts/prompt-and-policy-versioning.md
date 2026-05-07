# Prompt and Policy Versioning

When agents perform real project work, prompts and policies become execution infrastructure. If they change invisibly, the system becomes unstable.

## Prompt versioning

Prompt versioning means treating operational prompts like code:
- named
- stored
- diffable
- reviewable
- rollbackable

This matters because small prompt changes can alter:
- output quality
- safety behavior
- task interpretation
- escalation thresholds
- formatting and integration compatibility

## Policy versioning

Policies define behavioral rules: what agents may do, what requires approval, what counts as done, what data is restricted, what actions are prohibited.

Without clear policy versions, teams cannot explain why behavior changed or whether a failure came from:
- bad task design
- bad prompt
- bad policy
- model drift
- tool failure

## What to version
- system prompts
- task templates
- review rubrics
- approval policies
- escalation rules
- tool permission sets
- definitions of done

## Good practice
- give every operational prompt a stable name and revision history
- tie prompt/policy versions to runs, outputs, or tickets in telemetry
- change one meaningful variable at a time when possible
- keep rollback paths for high-impact workflows

## Failure modes
- silently editing prompts in place
- not recording which policy governed a run
- changing prompts and then blaming the model for behavior shifts
- no separation between experimentation prompts and production prompts

## Practical rule

If a prompt or policy can materially change project execution, it should be versioned like any other production control surface.
