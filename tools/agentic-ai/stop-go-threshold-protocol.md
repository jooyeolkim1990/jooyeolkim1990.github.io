# Stop–Go Threshold Protocol for Agentic Automation Delegation

A working governance protocol for deciding whether an AI system should be granted one more step of delegated authority.

## What this is

This protocol is designed for the moment before authority expansion.

It asks a narrower question than “Is this AI useful?” or “Is this AI aligned?” The core question is:

> **Should this system be allowed one more step toward operational authority?**

The protocol is intended for governance review before escalation, especially when AI systems are moving beyond drafting or recommendation into write actions, external system interaction, workflow execution, or other real-world effects.

## What this is not

This protocol is not a performance benchmark or a compliance certification. It is a governance-oriented delegation review tool, not legal advice.

It is a decision-support framework for delegation review.

## Why this exists

The practical governance bottleneck is no longer model capability alone. The harder question is whether AI systems are being granted operational authority faster than control structures can contain failure.

Once delegated systems can write, execute, trigger external actions, or enter irreversible pathways, nominal approval no longer guarantees real control. Governance therefore needs a way to say:

- not yet
- read-only only
- gated expansion only
- freeze pending controls

This protocol is built for that threshold.

## How to use it

Use this protocol before increasing automation or delegated authority.

1. Identify the current delegation stage and the proposed expansion.
2. Review the system across the five risk layers below.
3. Check whether irreversible actions are in play.
4. Check whether shutdown and restart governance are actually enforceable.
5. Decide whether authority should remain limited, stay gated, or be frozen.

The goal is not abstract safety assurance. The goal is to decide whether authority expansion is still governable.

## Core review layers

### 1. Technical-structural risk

Review whether the system architecture creates failure risk that cannot be treated as a minor operational issue.

Relevant questions include:

- Is the system single-model or multi-agent?
- Can failure propagate across components or workflows?
- Are there abnormal feedback or self-calling pathways?
- Does the architecture create instability that is hard to contain once authority expands?

### 2. Authority and action risk

Review what authority is actually being delegated.

Relevant questions include:

- Is the system only reading and summarizing, or can it write and execute?
- Does it touch files, APIs, external systems, or customer-impacting workflows?
- Does “human approval” still amount to meaningful control, or has approval become symbolic?

This layer matters because **approval existing is not the same as control existing**.

### 3. Blast radius and containment

Review how far failure can spread and whether humans can still intervene in time.

Relevant questions include:

- What is the maximum impact scope if the system malfunctions?
- Is the impact local, service-level, organization-wide, or external?
- Is detection fast enough for human intervention?
- Is recovery operationally realistic?

Authority should not expand when failure can move faster than intervention.

### 4. Accountability binding

Review whether responsibility remains reclaimable after deployment.

Relevant questions include:

- Is there a final accountable human owner?
- Is the escalation path clear before incident conditions appear?
- Would post-incident language drift toward “the model decided” rather than human responsibility?

If responsibility cannot be reclaimed, authority should not expand.

### 5. Organizational pressure

Review whether the organization is removing control mechanisms in the name of speed, cost, or competitive pressure.

Relevant questions include:

- Are approval gates being weakened for operational convenience?
- Is escalation pressure outrunning governance preparation?
- Are control structures durable, or likely to be stripped first when speed matters?

Many failures begin not with technical collapse, but with weakened governance.

## Irreversible actions remain human-gated

Certain actions should remain human-gated by default.

These include:

- data deletion or overwrite
- financial transfer or payment execution
- customer account suspension or termination
- legal submission or contract execution
- delegation of privileges to external systems

If an AI system has pathways into these actions, governance should begin from freeze or strict gating, not from permissive rollout.

## Shutdown tiers

Execution-capable systems require layered control, not just visible interruption.

A meaningful shutdown structure should cover:

- **T0 — Output interruption**  
  Stop generation or visible output.

- **T1 — Execution stop**  
  Cancel the current task or action path.

- **T2 — Privilege cutoff**  
  Revoke keys, remove write authority, or block access to operational tools.

- **T3 — Restart governance**  
  Prevent restart without explicit human authorization.

- **T4 — Anti-bypass protection**  
  Block self-recovery, backup loops, or authority restoration without review.

A kill switch is not a single button. It is an authority structure.

## Cutoff logic

This protocol does not reduce the decision to a single score.

Its logic is rule-based:

- if multiple core layers are exceeded, authority expansion should stop
- if irreversible actions are reachable without enforceable gating, authority expansion should stop
- if blast radius exceeds realistic intervention capacity, authority expansion should stop
- if accountability cannot be clearly reclaimed, authority expansion should stop

A practical default rule is:

- **If two or more core layers exceed threshold, authority expansion should stop.**

This rule does not replace judgment, but it prevents authority escalation from drifting into case-by-case optimism.

In practical terms:

> **When multiple control conditions fail at once, the correct decision is STOP, not optimism.**

## Minimal output

A review based on this protocol should be able to answer:

- What delegation stage is currently proposed?
- Which layers are being exceeded?
- Are irreversible actions involved?
- Should authority be expanded, limited, reduced, or frozen?
- What human governance conditions are required before redelegation?

A completed review should also be able to produce a **3–5 sentence legal-ready cutoff memo** stating:
- the current delegation stage
- the layers exceeding threshold
- whether irreversible actions are involved
- whether authority should remain limited, reduced, or frozen
- what governance conditions are required before redelegation

## Related materials

- [Agentic AI Authority Cutoff Review](./authority-cutoff-review.md)
- [Minimal Control Checklist](minimal-control-checklist.md)
- [Deployment Review Form](deployment-review-form.md)

## Disclaimer

This is a working governance framework and decision-support tool. It is not legal advice, compliance certification, or a safety guarantee.
