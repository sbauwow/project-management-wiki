# Approval and Safety Gates

The goal is not maximum autonomy. The goal is maximum safe throughput.

Approval systems should exist where they reduce downside more than they add drag.

## Put approval gates around
- production writes
- money movement
- legal / policy sensitive actions
- credential use
- customer-facing changes with major blast radius
- destructive repo or infra actions

## Do not put approval gates around
- every low-risk read
- every formatting change
- every internal draft
- every test run
- every trivial lookup

Over-approval is a tax. Under-approval is a liability.

## Gate design
A good gate specifies:
- what action is gated
- why it is gated
- who approves
- what evidence the approver sees
- what happens after rejection

## Review outcomes
Every gated action should end in one of:
- approve
- reject
- revise
- escalate

If the system has no explicit reject or revise path, it is not a real control system.

## Key metric
Track review load, not just approval count.

A team drowning in approvals is not safe. It is overloaded.
