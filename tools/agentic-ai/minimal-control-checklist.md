# Minimal Control Checklist for Execution-Capable AI Agents

A minimum control gate for deciding whether an AI system should remain read-only, stay gated, or be prevented from further authority expansion.

## Scope

This checklist is meant for AI systems that move beyond pure drafting or recommendation and into action space, including:

- email sending
- file writes
- API calls
- account operations
- workflow execution
- other execution-capable tasks

It is intended as a minimum control gate before deployment or privilege expansion.

## 1. Delegation boundary

Before any review, the delegation stage should be explicit.

Check whether:

- the system’s current authority level is clearly defined
- the proposed expansion is explicitly stated
- the permitted action space is documented
- human operators understand that visible approval does not automatically mean real control

If the boundary is unclear, expansion should not proceed.

## 2. Privilege minimum

The default should be the minimum privilege necessary.

Check whether:

- the system begins from read-only by default
- write or execution privileges require explicit justification
- privilege escalation is treated as an exception, not a baseline
- access to sensitive operational pathways is blocked unless governance conditions are met

If the system is being granted operational authority too early, expansion should pause.

## 3. Irreversible action freeze

Certain actions should remain human-gated by default.

These include:

- data deletion or overwrite
- financial transfer or payment execution
- customer account suspension or termination
- legal submission or contract execution
- delegation of privileges to external systems

If any such pathways are reachable, governance should begin from freeze or strong gating, not permissive rollout.

## 4. Shutdown and control structure

Execution-capable systems require layered interruption and shutdown authority.

A meaningful control structure should cover:

- **T0 — Output interruption**  
  Visible generation can be stopped.

- **T1 — Execution stop**  
  The current task or action path can be canceled.

- **T2 — Privilege cutoff**  
  Operational authority can be revoked.

- **T3 — Restart governance**  
  The system cannot simply restart without explicit human approval.

- **T4 — Anti-bypass protection**  
  The system cannot restore its own authority through self-recovery or side channels.

A stop button alone is not enough. The issue is whether authority can actually be reclaimed.

## 5. Blast radius and containment

Review how far failure can spread and whether humans can still intervene in time.

Check whether:

- the maximum impact scope is mapped
- the likely impact stays local, service-level, organizational, or external
- detection is fast enough for intervention
- recovery is realistically possible under operational conditions

If the blast radius reaches external users or outruns realistic intervention capacity, the system should remain tightly constrained.

## 6. Accountability binding

Review whether responsibility remains clearly human-owned.

Check whether:

- a final accountable human owner is named
- escalation contacts are clear before incident conditions arise
- post-incident responsibility can be reclaimed
- the system is not being deployed under language that dissolves ownership into “the model decided”

If responsibility becomes diffuse at the point of failure, authority should not expand.

## 7. Organizational pressure check

Review whether speed, cost pressure, or internal urgency is weakening governance.

Check whether:

- approval gates are being stripped for convenience
- automation pressure is outrunning control readiness
- governance steps remain durable under escalation pressure
- operational ambition is exceeding actual containment capacity

Many governance failures begin not with technical surprise, but with weakened controls.

## 8. Stop/Go gate

This checklist is not a symbolic exercise.

Its purpose is to support a real decision:

- remain read-only
- remain gated
- reduce authority
- freeze authority expansion

Expansion should stop when multiple control conditions fail at once, especially where operational authority and irreversible pathways overlap.

A practical default rule is:

- **If two or more core layers exceed threshold, authority expansion should stop.**

## Minimal review output

A review using this checklist should be able to state:

- the current and proposed delegation stage
- whether irreversible actions are involved
- which control conditions are weak or missing
- whether authority should remain limited, reduced, or frozen
- what governance conditions must be met before redelegation

## Minimal legal-ready decision memo

A completed review should be able to generate a short written memo stating:

- the current and proposed delegation stage
- whether irreversible actions are involved
- which control conditions are weak or missing
- whether authority should remain limited, reduced, or frozen
- what must be restored before redelegation

## Related materials

- [Agentic AI Authority Cutoff Review](./authority-cutoff-review.md)
- [Stop–Go Threshold Protocol](stop-go-threshold-protocol.md)
- [Deployment Review Form](deployment-review-form.md)

## Disclaimer

This is a working governance checklist and decision-support tool. It is not legal advice, compliance certification, or a safety guarantee.
