# Research Projection System

## Purpose

This system turns one public research-object record or public output record into consistent cards across the website.

The source of truth for public cards is data, not copied HTML in route pages.

## Where to edit

| Change needed | Edit this file |
|---|---|
| Research object name, summary, type, status, themes, route, or link | `_data/research_objects.yml` |
| Paper, case, toolkit, or other output card | `_data/research_outputs.yml` |
| Research object card layout | `_includes/research-object-card.html` |
| Research output card layout | `_includes/research-output-card.html` |
| Placement rules for Ideas | `ideas/index.md` |
| Placement rules for Diagnostic Work | `diagnostics/index.md` |
| Placement rules for papers and conference outputs | `essays/index.md` |
| Acceptance, presentation, conversion, or publication status authority | `cv.md` |

Do not copy an object's public name, summary, status, or themes into route-page HTML. Edit the data record once.

## Research object record

```yaml
- id: lfc
  show_card: true
  route: ideas
  order: 10
  name: LFC Axis
  full_name: Legibility / Feedback / Control
  type: Axis
  status: Active Research
  summary: >-
    One public-safe sentence.
  themes:
    - Feedback systems
    - Work
    - Learning
  url:
  link_label:
```

### Field rules

- `id`: stable machine-readable identifier. Do not casually rename it.
- `show_card`: controls whether the public card is rendered. It is not a privacy mechanism.
- `route`: currently `ideas` or `diagnostics`.
- `order`: lower numbers appear first within the generated group.
- `name`: public display name.
- `full_name`: optional expansion shown after an em dash.
- `type`: public object type, such as `Axis`, `Framework`, or `Audit`.
- `status`: public status, such as `Active Research`, `Beta Tool`, or `Released`.
- `summary`: one public-safe sentence.
- `themes`: normally three short public themes.
- `url`: optional site-relative target. Leave blank when no public page exists.
- `link_label`: optional call to action used only when `url` exists.

## Research output record

```yaml
- id: egov-2026-political-judgment
  show_card: true
  route: essays
  section: papers
  order: 10
  title: The output title
  summary: >-
    One public-safe sentence describing what the output does.
  type: Reflections / Viewpoint Paper
  status: Accepted, Not Converted
  venue: EGOV-CeDEM-ePart 2026 / IFIP EGOV 2026
  uses:
    - political-scam
  themes:
    - Political Scam
    - Digital governance
    - Responsibility recovery
  public_file: /records/example.pdf
  link_label: View public summary and record →
  record_anchor: /cv.html#relevant-record
```

### Output field rules

- `uses` contains research-object IDs, not display names.
- `public_file` points to the public projection or public record file, not an internal manuscript.
- `record_anchor` points to the status-authority entry in `cv.md` when one exists.
- `status` must not imply presentation, publication, or proceedings conversion unless the Public Record supports it.

## Rendering flow

```text
research_objects.yml
  → route filter
  → research-object-card.html
  → Ideas or Diagnostic Work

research_outputs.yml
  → route and section filter
  → research-output-card.html
  → Essays & Papers or another approved output route
```

Existing manually authored cards can remain alongside generated cards during migration. New research-object cards governed by this system should be added through the data files.

## Public-data safety rule

This repository is public.

Never place selective or internal material in `_data/research_objects.yml` or `_data/research_outputs.yml`, including:

- unpublished mechanism detail;
- internal scoring rules or thresholds;
- private source traces;
- embargoed claims;
- internal relation maps;
- unpublished manuscripts;
- personal or confidential correspondence.

`show_card: false` only suppresses rendering. The content remains visible in the public repository.

## Standard update workflow

1. Edit one record in the relevant `_data` file.
2. Confirm `show_card`, `route`, `status`, and links.
3. Check the rendered route page.
4. Check mobile wrapping and long titles.
5. Confirm that `cv.md` remains the status authority for conference and publication claims.
6. Merge only after rendered review.

## Current pilot

Research objects:

- LFC Axis → `ideas`
- IERF → `ideas`
- Cost Justice Audit (CJA) → `diagnostics`
- Political Scam → registered for output relations but not currently rendered as an object card

Research output:

- EGOV 2026 political-judgment paper → `essays`, `papers`

This pilot establishes the reusable pipeline. It does not automatically generate new substantive claims, summaries, cases, or internal-to-public disclosure decisions.
