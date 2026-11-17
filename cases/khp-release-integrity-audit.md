---
title: "KHP v2.5: Data Release Integrity & Downstream Impact Audit"
description: "Independent October 2026 audit of a Korea Health Panel release discrepancy, provider correction, cross-format reconciliation, and longitudinal analysis impact."
permalink: /cases/khp-release-integrity-audit/
---

<p class="feature-meta">Public case study · October 2026 · independently initiated</p>

# When a data-release error changes the research sample

**Korea Health Panel (KHP), second cohort, 2019–2024 · annual data v2.5**

A discrepancy in the publicly distributed Stata and SPSS files was identified across six annual releases and raised with the data provider in a documented inquiry on **21 October 2026**. On **22 October**, the provider issued a correction notice acknowledging missing records in the distributed Stata/SPSS files and re-uploaded corrected data.

The independent work did not stop at reporting the discrepancy. It compared preserved releases with the current SAS reference, reproduced historical analyses on the affected data, reran the same specifications on corrected data, and measured the consequences for linked samples and selected descriptive findings.

<div class="index-grid">
  <div class="index-item">
    <h3>35 / 35</h3>
    <p>Corrected cross-format table pairs matched on normalized variables, row contents and multiplicities within the tested scope.</p>
  </div>
  <div class="index-item">
    <h3>125,086</h3>
    <p>Restored <strong>table-year records</strong> across 30 Stata tables (2019–2024). This is not a count of unique people or households.</p>
  </div>
  <div class="index-item">
    <h3>8 / 8</h3>
    <p>Preserved historical analysis specifications reproduced before their corrected-data reruns; 66/66 archived CSV/TXT outputs matched byte for byte.</p>
  </div>
  <div class="index-item">
    <h3>+47.9%</h3>
    <p>Increase in the six-year common-household analysis sample, from 3,429 to 5,071, under the preserved analysis rules.</p>
  </div>
</div>

## Why the timing mattered

The 2026 KHP operating plan placed **release of the 2024 annual data**, **the 18th KHP academic conference**, and **data quality management and utilization** within the same annual program. The conference call accepted research using KHP first-cohort (2008–2018) or second-cohort (2019–2024) annual data. The paper-submission deadline was **16 October 2026**, before the correction notice.

| Date | Documented event |
| --- | --- |
| **16 Oct 2026** | Deadline for the 18th KHP conference's paper submissions. |
| **21 Oct 2026** | A written inquiry identified cross-year record shortfalls, an approximately one-in-sixteen pattern, and household–individual linkage discrepancies in the distributed files. |
| **22 Oct 2026** | The data provider notified users that Stata and SPSS records had been omitted during file transfer/conversion and re-uploaded corrected files. |
| **23 Oct 2026** | The independent release reconciliation and historical-analysis impact assessment were completed. |

The sequence establishes that a specific discrepancy was reported **before** the provider's general correction notice. **It does not establish whether the inquiry caused the correction** or when the provider first identified the issue internally. Nor does it establish which conference submissions, if any, used the affected formats and versions.

The institutional context is supported by the [official conference call](https://www.kihasa.re.kr/news/notice/view?seq=76354) and the [2026 KHP operating-plan record](https://www.kihasa.re.kr/api/kihasa/file/download?seq=32952).

## What the audit established

### 1. The discrepancy was systematic, not a user-side filter

The initial inquiry compared official annual household counts with unmodified downloaded Stata files. Across 2019–2024, the household shortfalls were **421, 388, 369, 354, 341 and 462 records** respectively. Corresponding issues were identified in individual files. In the 2023 pre-correction release, **700 individual rows did not match a same-year household identifier**; in the corrected release, the same unmatched count was zero.

Further reconciliation showed that removing records at a repeated positional interval—positions 15, 31, 47, and so forth, using one-based row positions—from the corrected tables reproduced the tested pre-correction contents. This is an **observed release pattern**, not proof of a specific software product, license issue or internal conversion defect.

### 2. Corrected formats were reconciled against SAS

The audit preserved the affected and corrected releases as separate inputs, then compared table schemas, normalized row content, row multiplicities and selected identifiers. All **35 tested corrected Stata/SPSS-to-SAS table pairs** matched within the documented scope. Across the 30 pre-correction Stata tables, no old row content was absent from the corresponding corrected file.

The provider attributed the discrepancy to the SAS-to-SPSS/Stata transfer/conversion process. The independent checks support the observable record-loss and corrected-content account; they do not independently reconstruct the provider's internal conversion environment.

### 3. Longitudinal linkage amplified the analytic impact

| Preserved analysis sample | Before correction | After correction | Change |
| --- | ---: | ---: | ---: |
| Three-year common households | 4,328 | 5,236 | +21.0% |
| Six-year common households | 3,429 | 5,071 | +47.9% |
| Six-year common individuals | 7,620 | 11,225 | +47.3% |

These are **analysis sample counts**, not survey response rates. They demonstrate how a comparatively modest release-level omission can compound under repeated longitudinal linkage.

### 4. Not every substantive interpretation survived unchanged

Eight preserved historical specifications were first reproduced against their original outputs. The same specifications were then rerun on the corrected release, without silently changing the analytical rules.

Some narrow descriptive conclusions remained stable. Others changed materially. For example, among households with cost-related unmet need and recorded dental use in one **six-year balanced-panel** tabulation, the recorded medical-burden measure had previously fallen from **65.0% to 60.2%** between 2023 and 2024. The corrected-data result was **62.3% to 62.3%**. In that specific table, a description of a decline no longer held. A separate three-year sample still showed a smaller decline and should not be conflated with this result.

This is a bounded historical rerun, **not** a claim that all KHP-based studies were affected or that population-level bias has been established.

## Deliverables and verification trail

<div class="index-grid">
  <div class="index-item">
    <h3>Release-integrity record</h3>
    <p>Old/corrected file inventory, checksum and provenance checks, cross-format reconciliation, row-position diagnostics, and identifier-linkage tests.</p>
  </div>
  <div class="index-item">
    <h3>Downstream impact record</h3>
    <p>Eight historical baseline reproductions, eight corrected reruns, analytic membership changes, a 28,857-cell comparison register, and conclusion-level review.</p>
  </div>
</div>

The evidence archive preserves the **21 October inquiry**, the provider's **22 October correction notice**, the **23 October follow-up reply**, source snapshots, checksums, scripts and comparison outputs. Original correspondence and restricted-distribution data are **not posted on this public page**.

## Scope and attribution

<div class="page-note">
  <strong>Status:</strong> Independent, researcher-initiated audit; <strong>not a provider-commissioned contract, provider-endorsed certification or paid client engagement.</strong> The provider's correction and the independent impact audit are distinct activities.
</div>

The audit does **not** establish the exact internal cause of the conversion failure; whether the 21 October inquiry triggered the correction; which third-party conference papers or publications used the affected version; or a general population-bias or causal-effect estimate. Those questions would require additional evidence.

What it does establish is a **timestamped pre-correction identification**, the provider's subsequent acknowledgement and corrected release, and a reproducible assessment of how release integrity affected concrete analysis outputs.

---

**Related work:** [Research Claim Due Diligence](/due-diligence/) · [Selected Work](/selected-work.html) · [Work With Me](/work-with-me.html)

For scoped data-release checks, replication or research-impact assessments: **[contact@jooyeolkim.com](mailto:contact@jooyeolkim.com)**.
