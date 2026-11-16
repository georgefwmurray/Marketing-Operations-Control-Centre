---
layout: default
title: "Insights | George Murray"
description: "Practical articles on marketing operations leadership, MarTech, multi-brand operating models and AI agent governance."
permalink: /insights/
---

<section class="page-hero">
  <p class="eyebrow">Insights</p>
  <h1>Notes on marketing operations and technology.</h1>
  <p class="page-lead">Practical thinking drawn from work across marketing operations, CRM, automation, multi-brand environments and AI governance.</p>
</section>
<section class="content-section">
  {% assign insights_today = site.time | date: "%Y-%m-%d" %}
  <div class="cards">
    {% if insights_today >= "2026-12-01" %}
    <article class="card"><p class="kicker">AI automation · Commercial value</p><h2><a href="{{ '/insights/measuring-the-business-value-of-ai-automation/' | relative_url }}">AI automation: what does the business actually get back?</a></h2><p>Five measures for assessing automation value, with a transparent breakdown of released capacity, external spend reduction and estimated benefits.</p><p class="section-cta"><a href="{{ '/insights/measuring-the-business-value-of-ai-automation/' | relative_url }}">Read article ↗</a></p></article>
    {% endif %}
    <article class="card"><p class="kicker">AI governance</p><h2><a href="{{ '/insights/governing-ai-agents-marketing-operations/' | relative_url }}">Governing AI agents in marketing operations</a></h2><p>Ownership, risk, human review and lifecycle governance for agents used in marketing workflows.</p><p class="section-cta"><a href="{{ '/insights/governing-ai-agents-marketing-operations/' | relative_url }}">Read article ↗</a></p></article>
    <article class="card"><p class="kicker">Operating model</p><h2><a href="{{ '/insights/multi-brand-marketing-operations-operating-model/' | relative_url }}">Building a marketing operations model across multiple brands</a></h2><p>How to balance shared standards, brand flexibility, team capability and technology ownership.</p><p class="section-cta"><a href="{{ '/insights/multi-brand-marketing-operations-operating-model/' | relative_url }}">Read article ↗</a></p></article>
  </div>
</section>
