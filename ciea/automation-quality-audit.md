# CIEA Automation Quality Audit Extension
## Output Warranty, Rollback, and Accountability Counter-Surfaces

**Status:** Public v0.4.2 patch  
**Parent:** CIEA Core  
**Type:** Cross-cutting extension for AI automation and LLM productivity claims  
**Scope:** AI-generated answers, drafts, summaries, code, customer responses, operational recommendations, and other outputs that are presented as productivity or automation gains.

---

## 1. Core claim

> **AI automation should not be evaluated by generation speed alone. It must be evaluated by total quality cost: verification, rework, rollback, responsibility recovery, and downstream harm.**

Shorter:

> **Automation has not removed work if it has merely moved quality assurance.**

---

## 2. Why this extension exists

Many AI products are evaluated through visible surfaces:

- answer speed;
- drafting speed;
- automation rate;
- ticket deflection;
- call reduction;
- code generation volume;
- lower apparent labor time;
- faster document production.

Those surfaces can be real.

But they are not enough.

A system can generate faster while moving the remaining work into:

- human verification;
- expert review;
- factual checking;
- legal or policy validation;
- rework;
- correction;
- rollback;
- customer escalation;
- downstream responsibility disputes.

CIEA therefore asks:

```text
Did automation reduce the real work?
Or did it move verification, repair, and responsibility outside the performance table?
```

---

## 3. New audit concepts

### 3.1 Output QA Displacement

**Definition**

Output QA Displacement occurs when an automated system reduces generation or processing time while shifting quality assurance to another actor.

Common receiving actors:

- end users;
- frontline workers;
- reviewers;
- managers;
- legal teams;
- engineers;
- customers;
- public agencies;
- downstream affected people.

Diagnostic sentence:

> **If output quality is not warranted and verification capacity is not funded, automation has not removed work; it has relocated quality assurance.**

---

### 3.2 Warranty Gap

**Definition**

Warranty Gap occurs when a system is sold or adopted as operational capability, while the accuracy, completeness, or fitness of its outputs remains weakly warranted, unwarranted, or shifted to the customer’s verification duty.

The audit does not need to claim bad faith.

It asks a narrower question:

```text
Is the output treated as operationally useful in the sales or adoption story,
while treated as unguaranteed or customer-verified in the responsibility layer?
```

Diagnostic sentence:

> **Capability is sold upstream; verification is assigned downstream.**

---

### 3.3 Rollback Surface

**Definition**

Rollback Surface is the counter-surface that asks whether an automated result or change can be reversed, how much recovery costs, and who owns the recovery pathway.

A fast automated action is not necessarily efficient if rollback is unclear or expensive.

Required questions:

```text
What was changed?
Can the change be reversed?
Who can reverse it?
How long does reversal take?
What is lost during recovery?
Was recovery cost included in the performance claim?
```

Diagnostic sentence:

> **A faster automated change is not interpretable until rollback cost, recovery ownership, and post-action audit burden are checked.**

---

### 3.4 Accountability Collateral

**Definition**

Accountability Collateral refers to the structure that makes an actor answerable because they have both meaningful control and actual exposure to loss if the system fails.

The relevant question is not only whether a name appears on a process chart.

It is:

```text
Can this actor stop the system?
Can this actor be made answerable?
Does this actor actually lose something if failure occurs?
```

Diagnostic sentence:

> **If no one can meaningfully lose from automation failure, no one can meaningfully be trusted with automation authority.**

---

### 3.5 Reliance–Warranty Split

**Definition**

Reliance–Warranty Split occurs when an interface or product presentation encourages practical reliance, while the responsibility layer withdraws or weakens warranty for the output.

Common pattern:

```text
interface creates reliance
→ output looks actionable
→ terms or responsibility layer withdraw warranty
→ user/customer inherits risk classification and verification burden
```

Diagnostic sentence:

> **The interface creates trust; the responsibility layer withdraws warranty.**

---

## 4. Surface / counter-surface table

| Improved surface | Required counter-surfaces |
|---|---|
| answer generation speed | factual error, verification time, reliance risk |
| document drafting speed | review burden, revision cycles, expert correction cost |
| coding speed | test failure, security review, rollback cost |
| customer-service automation | resolution rate, escalation, recontact, abandonment, frustration |
| call deflection | unresolved demand, human escalation, quiet exit |
| productivity gain | hidden review time, rework, downstream error cost |
| lower staffing need | remaining-case complexity, worker stress, service degradation |
| faster operational change | rollback clarity, recovery time, blast radius |
| lower complaint volume | complaint access difficulty, suppressed reporting, external complaints |

---

## 5. Automation quality audit sheet

```text
[1. Performance claim]
- What improved?
- Who claims it improved?
- Which metric is used?

[2. Core]
- What was actually supposed to improve?
- Is the core output quality, user resolution, cost, speed, trust, or accountability?

[3. Output quality]
- Is the output factual, advisory, customer-facing, operational, legal, financial, medical, or administrative?
- Is output quality measured?
- Is output quality warranted?
- What kinds of error are known or foreseeable?

[4. Verification]
- Who verifies the output?
- Is verification mandatory or informal?
- Is verification time counted?
- Is expert review required?
- Is verification capacity funded?

[5. Warranty gap]
- Is the system sold or adopted as operational capability?
- Does the responsibility layer require customer/user validation?
- Does the claimed productivity gain subtract validation cost?

[6. Rollback]
- Can wrong output or automated change be reversed?
- Who owns rollback?
- What is time-to-recovery?
- What is lost during recovery?

[7. Accountability collateral]
- Who has stopping authority?
- Who has final responsibility?
- Who bears loss if failure occurs?
- Is there a compensation, correction, or appeal path?

[8. Judgment]
- Real improvement
- Surface optimization
- Output QA displacement
- Warranty gap risk
- Rollback insufficiency
- Responsibility recoverability failure
- Insufficient evidence
```

---

## 6. Judgment rules

### Real improvement

Use only when:

- output quality is measured or strongly verified;
- verification burden does not increase materially;
- rollback path is clear where needed;
- responsibility remains recoverable;
- downstream counter-surfaces do not worsen.

### Output QA displacement

Use when:

- generation is faster;
- but review, correction, validation, or responsibility-checking work increases elsewhere.

### Warranty gap risk

Use when:

- the product is adopted as operational capability;
- but output accuracy, completeness, or use-case fitness remains unwarranted or customer-verified;
- and the verification burden is missing from the performance table.

### Rollback insufficiency

Use when:

- automated action produces state changes;
- but recovery ownership, recovery time, or prior-state restoration is unclear.

### Responsibility recoverability failure

Use when:

- the system affects real users or decisions;
- but no actor with meaningful control and meaningful exposure can be made answerable.

---

## 7. Minimal application example

Claim:

> An AI system increased document drafting productivity by 40%.

CIEA does not accept this claim directly.

It asks:

```text
Did final usable documents increase?
Did expert review time increase?
Did factual correction increase?
Did legal/policy review increase?
Were rejected drafts counted?
Were downstream errors counted?
Was rollback or correction cost counted?
Who is answerable if a draft causes damage?
```

Possible judgment:

> The system may have improved draft generation speed, but real productivity cannot be accepted unless verification time, correction cycles, and responsibility paths are included. Without those counter-surfaces, the claim remains vulnerable to Output QA Displacement and Warranty Gap risk.

---

## 8. Relation to Stop–Go

This CIEA extension is not a replacement for a delegation cutoff protocol.

| Tool | Function |
|---|---|
| **Stop–Go** | Pre-delegation authority freeze or expansion decision. |
| **CIEA** | Performance-claim audit after or during adoption. |

Short version:

> Stop–Go asks whether the system may act. CIEA asks whether the claimed improvement survived the hidden-cost audit.

---

## 9. Boundary conditions

This extension does not claim:

- all AI automation is fake;
- all LLM outputs are unusable;
- all vendors act in bad faith;
- all outputs require the same level of review;
- every risk can be fully measured;
- every uncertainty makes automation impermissible.

It claims only:

> **AI automation performance claims must include verification, rollback, and responsibility costs before they can be treated as real efficiency.**

---

## 10. Reusable sentences

> **Generation speed is not productivity until verification cost is counted.**

> **A model output is not operational value unless someone can verify, correct, and answer for it.**

> **Capability without output warranty creates customer-side quality assurance.**

> **A cost is not gone merely because it became a review burden.**

> **Automation has not removed work if it has relocated quality assurance, rollback, and responsibility.**

[Back to CIEA](index.md)
