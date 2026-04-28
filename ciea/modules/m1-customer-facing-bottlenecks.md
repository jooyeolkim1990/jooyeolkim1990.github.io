# CIEA-M1
## Customer-Facing Bottleneck Module

**Status:** Public module v0.4.2  
**Parent:** [CIEA Core](../core.md)  
**Type:** Domain-specific audit module

CIEA-M1 applies the CIEA audit engine to customer-facing and user-facing interfaces.

---

## Core question

> When an organization claims efficiency, automation, service optimization, or cost reduction at the interface, did it actually improve the core, or did it move waiting, frustration, distrust, verification burden, and emotional labor onto customers and frontline workers?

Shorter:

> **Did the bottleneck disappear, or was it pushed into someone’s time, anger, body, or verification burden?**

---

## Target interfaces

- AI chatbots
- call centers
- ARS / IVR phone trees
- customer-service desks
- public-service complaint windows
- platform support systems
- help desks
- hospital or clinic reception systems
- self-checkout systems
- online support forms
- account verification and recovery processes
- AI counseling or advisory interfaces

---

## Main mechanisms

| Mechanism | Short meaning |
|---|---|
| **Bottleneck Externalization** | Organizational processing cost becomes customer time or frontline emotional labor. |
| **Anger Routing** | Failed layers concentrate frustration at the final human interface. |
| **Organizational Analgesia** | Support channels narrow, making the organization quieter but less sensitive. |
| **Last-Bottleneck Memory** | A final bottleneck can overwrite an otherwise acceptable experience. |
| **Risk Classification Burden** | Users must decide whether an answer is low-risk information or consequential guidance. |
| **Reliance–Warranty Split** | The interface creates reliance while the responsibility layer weakens or withdraws warranty. |
| **Output QA Displacement** | The system produces answers faster while moving verification and correction work to users or workers. |

---

## New v0.4.2 mechanism: Reliance–Warranty Split

This mechanism is especially important for AI customer support, public AI counseling, financial-service automation, platform appeals, and other interfaces where a generated answer may look actionable.

Structure:

```text
interface looks helpful
→ answer appears actionable
→ user relies or prepares to act
→ terms / disclaimer / responsibility layer says output is not binding or must be verified
→ user inherits risk classification and verification burden
→ human or institutional layer receives escalation later
```

Diagnostic sentence:

> **The interface creates trust; the responsibility layer withdraws warranty.**

This does not prove deception by itself.

It means the interface must be audited against:

- user comprehension;
- legal or operational effect;
- escalation access;
- correction routes;
- verification cost;
- responsibility recovery.

---

## M1 counter-surfaces for AI support claims

| Claimed improvement | Required counter-surfaces |
|---|---|
| chatbot use increased | issue completion rate, user comprehension, escalation need |
| answer speed improved | accuracy, reliance risk, verification burden |
| call volume decreased | abandonment, quiet exit, unresolved demand |
| human calls reduced | remaining-case complexity, frontline emotional labor |
| complaint volume decreased | complaint access difficulty, external complaints |
| self-service increased | retry burden, vulnerable-user access, failure rate |
| staffing optimized | worker stress, complex-case concentration, burnout |
| customer satisfaction improved | recontact, churn, trust after failure |

---

## M1 audit move

```text
interface claim
→ real service core
→ decision table
→ excluded customer/user burden
→ excluded frontline burden
→ reliance-warranty split check
→ counter-surfaces
→ displacement judgment
```

---

## Public sample

- [Fast Answers, Slow Responsibility: AI Customer Support Korea](../cases/ai-customer-support-korea.md)

## Related CIEA extension

- [Automation Quality Audit Extension](../automation-quality-audit.md)

[Back to CIEA Modules](index.md)
