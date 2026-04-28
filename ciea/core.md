# CIEA Core
## Efficiency Claim Audit Architecture

**Status:** Public v0.4.2 patch  
**Type:** Practical audit engine  
**Scope:** Performance claims, automation claims, cost-cutting claims, productivity claims, service-optimization claims, and AI-output claims.

## One-line definition

CIEA tests whether a better-looking metric is real improvement or hidden displacement.

Expanded for AI automation:

> **CIEA tests whether AI automation reduced real work, or merely moved verification, rollback, and responsibility costs outside the performance table.**

---

## Four basic elements

| Element | Meaning |
|---|---|
| **Core** | The real underlying object of evaluation. |
| **Surface** | The observable metric or signal used to infer the core. |
| **Decision table** | The values treated as legitimate inputs for a performance decision. |
| **Residue** | Excluded values and harms that do not disappear just because the table omitted them. |

Core sentence:

> What cannot enter the table does not disappear. It returns somewhere else.

---

## Standard audit move

```text
Performance claim
→ core definition
→ decision-table inspection
→ excluded-value check
→ counter-surface check
→ displacement tracking
→ time-delay check
→ rollback and responsibility check
→ structural judgment
```

---

## Core concepts

### 1. Core / Surface distinction

A metric is not the core. It is only a surface used to infer the core.

Examples:

| Claimed surface | Possible core |
|---|---|
| response speed | real service resolution |
| automation rate | real reduction of work |
| call deflection | resolved demand |
| drafting speed | usable output quality |
| lower complaint volume | fewer problems, or weaker complaint access |

### 2. Decision table

The decision table is the set of values allowed into the evaluation.

It often includes:

- cost;
- speed;
- volume;
- automation rate;
- response count;
- headcount reduction;
- projected savings.

It often excludes:

- verification time;
- rework;
- customer/user burden;
- worker emotional labor;
- rollback cost;
- responsibility recovery;
- future trust damage;
- quiet exit.

### 3. Counter-surfaces

A metric improvement is not interpretable until its counter-surfaces are checked.

| Improved surface | Required counter-surfaces |
|---|---|
| cost reduction | quality degradation, burnout, delayed repair cost |
| processing speed | error rate, rework, recontact |
| automation rate | unresolved cases, escalation, abandonment |
| complaint reduction | access difficulty, external complaints, quiet exit |
| answer generation speed | verification time, factual error, reliance risk |
| drafting productivity | expert review cost, revision burden, downstream error |
| code generation speed | test failure, security review, rollback cost |

### 4. Displacement tracking

A cost is not gone merely because it left the reporting line.

Common routes:

| Route | Question |
|---|---|
| internal displacement | Did one team’s improvement become another team’s burden? |
| downward displacement | Did management burden move to workers? |
| external displacement | Did organizational burden move to customers, users, or the public? |
| temporal displacement | Did current savings become future repair cost? |
| formal displacement | Did the same problem change legal, procedural, or accounting form? |
| narrative displacement | Was displacement framed as efficiency, modernization, or innovation? |

---

## v0.4.2 automation patch

This patch adds four audit concepts for AI automation and LLM-based productivity claims.

### 1. Output QA Displacement

**Output QA Displacement** occurs when a system reduces generation or processing time while moving quality assurance work to users, employees, experts, customers, or downstream institutions.

Short definition:

> Automation has not removed work if it has merely relocated verification.

Typical excluded values:

- human review time;
- expert verification;
- factual checking;
- legal or policy review;
- rework;
- correction cycles;
- downstream error handling.

### 2. Warranty Gap

**Warranty Gap** refers to the gap between a product being sold as useful operational capability and the absence or weakness of responsibility for the accuracy, completeness, or use-case fitness of its outputs.

Short definition:

> The system sells capability, but the customer inherits verification.

CIEA does not assume that every vendor contract has the same terms. The audit question is narrower:

```text
Is output quality warranted?
If not, who verifies it?
Was that verification cost included in the performance claim?
```

### 3. Rollback Surface

**Rollback Surface** is the counter-surface that asks whether a faster automated change can be reversed, how much recovery costs, and who owns the recovery path.

Short definition:

> A faster change is not interpretable until rollback cost is visible.

Required checks:

- Is there a known previous state?
- Is rollback technically possible?
- Who can trigger rollback?
- How long does recovery take?
- Does rollback itself create new damage?
- Is recovery cost included in the ROI or efficiency claim?

### 4. Accountability Collateral

**Accountability Collateral** refers to whether a named human or organization has both meaningful control and actual exposure to loss if automated action fails.

Short definition:

> Responsibility is not real if no one can meaningfully lose from failure.

CIEA distinguishes four cases:

| Control | Loss exposure | Judgment |
|---|---|---|
| yes | yes | accountable control |
| yes | no | unaccountable authority |
| no | yes | scapegoat risk |
| no | no | responsibility vacuum |

---

## CIEA automation audit questions

Use these when evaluating a claim that AI automation improved productivity, support, coding, writing, operations, or customer service.

```text
1. What surface improved?
2. What core was supposed to improve?
3. Was output quality warranted, measured, or merely assumed?
4. Who verifies the output?
5. Was verification time counted?
6. What happens when output is wrong?
7. Can the result be rolled back?
8. Who owns rollback?
9. Who bears reputational, legal, financial, or organizational loss if the system fails?
10. Did the automation reduce real work, or move quality assurance and responsibility elsewhere?
```

---

## Judgment types

| Judgment | Meaning |
|---|---|
| **Real core improvement** | Surface improvement aligns with the core and counter-surfaces remain stable. |
| **Real efficiency** | Cost falls without meaningful displacement, delayed damage, or hidden verification burden. |
| **Surface optimization** | Metric improves while the core remains unchanged or worsens. |
| **Cost displacement** | Cost moves to workers, users, customers, contractors, public systems, or the future. |
| **Output QA displacement** | Generation work decreases but verification, review, or correction work moves elsewhere. |
| **Warranty gap risk** | The output drives work but accuracy, completeness, or use-case fitness remains unwarranted or weakly warranted. |
| **Rollback insufficiency** | Faster execution creates changes that are costly, unclear, or impossible to reverse. |
| **Responsibility recoverability failure** | No actor with real control and real exposure can be made answerable after failure. |
| **Table residue risk** | Excluded values are likely to return as damage later. |
| **Insufficient evidence** | The core cannot be judged with available data. |

---

## Current public module

- [CIEA-M1: Customer-Facing Bottleneck Module](modules/m1-customer-facing-bottlenecks.md)

## Current public sample

- [AI Customer Support Korea](cases/ai-customer-support-korea.md)

## Cross-cutting extension

- [Automation Quality Audit Extension](automation-quality-audit.md)

[Back to CIEA](index.md)
