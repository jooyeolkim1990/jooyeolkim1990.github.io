---
title: Essays & Papers
description: Longer public arguments, essays, papers, and venue-shaped outputs.
---

# Essays & Papers

<p class="index-lede">This section gathers longer arguments and venue-shaped outputs. A piece may originate in a current event, a framework, or an editorial or conference question; its public form is recorded separately from its origin.</p>

## Working papers

<div class="index-grid">
  <div class="index-item"><h2><a href="2026-07-24-you-agreed-to-the-rule-did-you-agree-to-the-experiment.html">You Agreed to the Rule. Did You Agree to the Experiment?</a></h2><p>ICML 2026 and the missing boundary between review duty and experimental participation. Working paper, Version 1.2; submitted to SSRN and currently under review.</p></div>
</div>

## Public essays

<div class="index-grid">
  <div class="index-item"><h2><a href="2026-07-02-the-landlord-at-the-end-of-the-ai-boom.html">The Landlord at the End of the AI Boom</a></h2><p>Spatial gate rent and the collection of AI-sector value through ownership of urban access.</p></div>
  <div class="index-item"><h2><a href="2026-06-16-the-off-switch-is-the-message.html">The Off-Switch Is the Message</a></h2><p>How frontier AI access can shift from commercial product to revocable security permission.</p></div>
  <div class="index-item"><h2><a href="../cases/systems-risk-absorption.html">When Systems Stop Absorbing Their Own Risk</a></h2><p>Displaced accountability and the politics produced when consequential systems push responsibility out of reach.</p></div>
  <div class="index-item"><h2><a href="../cases/anthropic-moral-ai-gated-access.html">Moral AI, Gated Access</a></h2><p>An essay on moral branding and the access order behind safety rhetoric.</p></div>
  <div class="index-item"><h2><a href="../briefs/labour/2026-06-03-capital-played-global-labor-reads-global-too.html">Capital Played Global. Labor Reads Global Too.</a></h2><p>Why compensation benchmarks travel before full labour institutions do.</p></div>
</div>

## Papers and conference work

<div class="index-grid">
  {% assign paper_outputs = site.data.research_outputs.outputs | where: "show_card", true | where: "route", "essays" | where: "section", "papers" | sort: "order" %}
  {% for output in paper_outputs %}
    {% include research-output-card.html output=output %}
  {% endfor %}
</div>

The [Public Record](../cv.html) is the status authority for working papers, accepted work, presented work, withdrawn work, and accepted-but-not-converted records. Record PDFs verify acceptance or participation; they should not be read as proof of publication unless the record states that publication occurred.

- [Open the Public Record](../cv.html)
- [Open record PDFs and conference status](../cv.html)
