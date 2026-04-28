# CIEA
## Core-Inference Evaluation Architecture

CIEA is a practical audit architecture for testing whether an apparent improvement in a metric reflects real progress toward the underlying core, or merely displaces cost, responsibility, frustration, verification work, rollback burden, and long-term damage outside the decision table.

## Core idea

> A metric is not the core. A metric is only a surface signal for inferring the core.

CIEA asks:

```text
What improved?
What was supposed to improve?
What did the decision table count?
What did it leave outside?
Where did the excluded cost, burden, or responsibility go?
Who must now verify, repair, roll back, or answer for the result?
```

## Public package

- [CIEA Core](core.md) — the common efficiency-claim audit engine.
- [Automation Quality Audit Extension](automation-quality-audit.md) — a cross-cutting extension for AI and LLM productivity claims.
- [Modules](modules/) — domain-specific application kits.
- [AI Customer Support Korea case](cases/ai-customer-support-korea.md) — a public sample showing CIEA-M1 in use.

## Current module

- [CIEA-M1: Customer-Facing Bottleneck Module](modules/m1-customer-facing-bottlenecks.md)

## Current sample case

- [Fast Answers, Slow Responsibility: Did AI Customer Support Remove the Bottleneck, or Move It?](cases/ai-customer-support-korea.md)

## Relation to Stop–Go

CIEA and Stop–Go answer different questions.

| Tool | Question |
|---|---|
| **Stop–Go Threshold Protocol** | Should this system be delegated one more step of authority? |
| **CIEA** | Did the claimed improvement actually improve the core, or did it move verification, rollback, and responsibility costs elsewhere? |

Shorter:

> Stop–Go asks whether automation should be allowed to act. CIEA asks whether automation actually improved anything after all excluded costs are counted.

## Related site sections

- [Frameworks](../frameworks/)
- [Cases](../cases/)
- [Briefs](../briefs/)
- [Tools](../tools/)

[Return to Start Here](../start-here.md)
