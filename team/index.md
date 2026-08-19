---
layout: default
title: Team
permalink: /team/
---
<section class="page-hero">
  <div class="shell narrow">
    <div class="eyebrow">Team & attribution</div>
    <h1>Datasets are built by <em>people.</em></h1>
    <p class="page-lead">RoofVIP distinguishes project stewardship, scientific development, and direct data contribution so that recognition remains visible as the dataset grows across releases.</p>
  </div>
</section>
<section class="page-content">
  <div class="shell">
    <div class="section-heading"><div><div class="eyebrow">Core team</div><h2>Project stewardship</h2></div></div>
    <div class="people-grid">
      {% assign core = site.data.team | where: "group", "core" %}
      {% for person in core %}{% include contributor-card.html person=person %}{% endfor %}
    </div>

    <div class="section-heading spaced"><div><div class="eyebrow">Dataset contributors</div><h2>Annotation & data contribution</h2></div></div>
    <div class="people-grid">
      {% assign contributors = site.data.team | where: "group", "contributor" %}
      {% for person in contributors %}{% include contributor-card.html person=person %}{% endfor %}
    </div>

    <div class="content-note attribution-note">
      <div><strong>Attribution principle</strong><p>The Team page records contribution to the resource. Formal paper authorship and dataset-release attribution can remain separately defined where appropriate.</p></div>
      <a class="text-link" href="{{ '/docs/citation/' | relative_url }}">Citation guidance →</a>
    </div>
  </div>
</section>
