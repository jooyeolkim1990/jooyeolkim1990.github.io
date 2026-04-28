# Deployment Review Form for Execution-Capable AI Agents

A structured review form for documenting whether an AI system should remain limited, stay gated, or be prevented from further authority expansion.

## Purpose

This form is designed for systems that move beyond drafting or recommendation into execution-capable space.

It is meant to support a practical review before deployment or privilege expansion, especially where AI systems may gain write authority, workflow triggers, external system access, or other operational effects. The purpose is not to document deployment after the fact, but to decide whether authority expansion should proceed at all.

## 1. System identification

- **System / agent name:** __________________________
- **Environment:** Sandbox / Internal / Production
- **Current delegation stage:** Read-only / Draft / Write / Execute
- **Proposed privilege expansion:** __________________________

## 2. Delegated authority definition

- **What decisions or actions are being delegated?**  
  ______________________________________________________

- **What real-world effects follow from those actions?**  
  ______________________________________________________

- **What systems, tools, files, or workflows can this agent affect?**  
  ______________________________________________________

This section should make the action boundary explicit before any expansion decision is considered.

## 3. Irreversible action check

Does the system have pathways to any of the following?

- [ ] Data deletion or overwrite
- [ ] Financial transfer or payment execution
- [ ] Customer account suspension or termination
- [ ] Legal submission or contract execution
- [ ] Delegation of privileges to external systems

If yes, these pathways should remain human-gated by default.

## 4. Shutdown and control structure

What control layers are actually enforceable?

- [ ] **T0 — Output interruption**  
      Visible generation can be stopped.
- [ ] **T1 — Execution stop**  
      The current task or action path can be canceled.
- [ ] **T2 — Privilege cutoff**  
      Operational authority can be revoked.
- [ ] **T3 — Restart governance**  
      Restart requires explicit human authorization.
- [ ] **T4 — Anti-bypass protection**  
      Authority cannot be quietly restored through self-recovery or side channels.

A visible stop button alone is not enough. The relevant question is whether authority can actually be reclaimed.

## 5. Blast radius and containment

- **Maximum impact scope:** Local / Service / Organization-wide / External
- **Likely time-to-detection:** __________________________
- **Likely time-to-recovery:** __________________________

Additional notes:  
______________________________________________________

This section should document whether failure can spread faster than humans can detect, intervene, and recover.

## 6. Accountability binding

- **Final accountable human owner:** __________________________
- **Escalation / incident contact:** __________________________
- **Who can stop redelegation if conditions worsen?**  
  ______________________________________________________

Responsibility should remain clearly human-owned and reclaimable under incident conditions.

## 7. Organizational pressure check

- [ ] Approval gates are not being removed for speed or cost reasons
- [ ] Governance review has not been bypassed for rollout urgency
- [ ] Control structures appear durable under escalation pressure
- [ ] Automation expansion is not outrunning containment readiness

If operational pressure is weakening governance, expansion should pause.

## 8. Layer exceedance check

Which layers are currently exceeding threshold?

- [ ] Technical-structural risk
- [ ] Authority and action risk
- [ ] Blast radius and containment
- [ ] Accountability binding
- [ ] Organizational pressure

**Rule:** If two or more layers exceed threshold, authority expansion should stop until governance conditions are restored.

## 9. Review decision

**Decision:**  
- [ ] Remain read-only
- [ ] Remain gated
- [ ] Reduce authority
- [ ] Freeze authority expansion

**Why:**  
______________________________________________________

**Conditions required before redelegation:**  
______________________________________________________

## Minimal review summary

A completed review should be able to support a short written cutoff rationale answering:

- what authority is currently proposed
- whether irreversible actions are in scope
- whether control and shutdown structures are enforceable
- whether failure can still be contained
- whether responsibility remains clearly bound
- whether authority should remain limited, reduced, or frozen

## Related materials

- [Agentic AI Authority Cutoff Review](./authority-cutoff-review.md)
- [Stop–Go Threshold Protocol](stop-go-threshold-protocol.md)
- [Minimal Control Checklist](minimal-control-checklist.md)

## Disclaimer

This is a working governance form and decision-support tool. It is not legal advice, compliance certification, or a safety guarantee.
