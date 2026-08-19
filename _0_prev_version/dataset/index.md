---
layout: default
title: Dataset
permalink: /dataset/
---
<section class="page-hero">
  <div class="shell narrow">
    <div class="eyebrow">Dataset</div>
    <h1>One project. <em>Explicit releases.</em></h1>
    <p class="page-lead">RoofVIP is maintained as a living, versioned dataset. Each release records a reproducible state of the available observations, annotations, metadata, and supporting documentation.</p>
  </div>
</section>
<section class="page-content">
  <div class="shell">
    <div class="release-grid release-grid-wide">
      {% for release in site.data.releases %}{% include release-card.html release=release %}{% endfor %}
    </div>
    <div class="content-note">
      <div><strong>Why version the dataset?</strong><p>Release-specific pages keep experimental inputs, citations, modalities, and known limitations traceable as RoofVIP evolves.</p></div>
      <a class="text-link" href="{{ '/docs/versioning/' | relative_url }}">Versioning policy →</a>
    </div>
  </div>
</section>
