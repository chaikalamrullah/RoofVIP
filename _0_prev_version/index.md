---
layout: default
title: Home
---
<section class="home-hero">
  <div class="shell hero-grid">
    <div class="hero-copy">
      <div class="eyebrow">Roof Vector Image Pair</div>
      <h1>Building-roof geometry as a <em>versioned research resource.</em></h1>
      <p>RoofVIP pairs very-high-resolution remote-sensing observations with structured roof geometry to support segmentation, vectorization, graph reconstruction, and geometry-aware learning.</p>
      <div class="hero-actions">
        <a class="button primary" href="{{ '/dataset/' | relative_url }}">Explore dataset</a>
        <a class="button secondary" href="{{ '/benchmark/' | relative_url }}">View benchmark</a>
      </div>
    </div>
    <div class="modality-stack" aria-label="RoofVIP modalities">
      <div class="modality-card"><span>01</span><strong>RGB</strong><small>Very-high-resolution imagery</small></div>
      <div class="modality-card"><span>02</span><strong>DSM</strong><small>Surface elevation</small></div>
      <div class="modality-card"><span>03</span><strong>DTM</strong><small>Terrain elevation</small></div>
      <div class="modality-card"><span>04</span><strong>nDSM</strong><small>Normalized height</small></div>
      <div class="modality-card featured"><span>05</span><strong>Vector</strong><small>Structured roof geometry</small></div>
    </div>
  </div>
</section>

<section class="section latest-release">
  <div class="shell">
    <div class="section-heading">
      <div><div class="eyebrow">Latest release</div><h2>RoofVIP v1.0.3.0</h2></div>
      {% include status-badge.html status="released" label="Released" %}
    </div>
    <div class="feature-band">
      <div class="feature-number">1.0.3.0</div>
      <div>
        <p>10,245 geographically separated 256 × 256 scenes for multimodal roof reconstruction across approximately 18 km² of Munich.</p>
        <div class="tag-row"><span class="tag">RGB</span><span class="tag">DSM</span><span class="tag">DTM</span><span class="tag">nDSM</span><span class="tag">LiDAR</span><span class="tag">Vector</span></div>
      </div>
      <div class="feature-actions"><a class="text-link" href="{{ '/dataset/v1.0.3.0/' | relative_url }}">Release details →</a><a class="text-link" href="https://zenodo.org/records/22015175">Zenodo ↗</a></div>
    </div>
  </div>
</section>

<section class="section">
  <div class="shell">
    <div class="section-heading"><div><div class="eyebrow">Release history</div><h2>A dataset designed to evolve.</h2></div><a class="text-link" href="{{ '/dataset/' | relative_url }}">All releases →</a></div>
    <div class="release-grid">
      {% for release in site.data.releases limit:4 %}{% include release-card.html release=release %}{% endfor %}
    </div>
  </div>
</section>

<section class="section section-dark">
  <div class="shell split-callout">
    <div><div class="eyebrow">Benchmark</div><h2>From dataset to comparable reconstruction results.</h2></div>
    <div><p>RoofVIP v1.0.3.0 now provides the fixed-scene benchmark dataset. The formal evaluation protocol and public leaderboard specification remain under development.</p><a class="button light" href="{{ '/benchmark/' | relative_url }}">Benchmark preview</a></div>
  </div>
</section>

<section class="section">
  <div class="shell">
    <div class="section-heading"><div><div class="eyebrow">Project log</div><h2>News & updates</h2></div></div>
    {% include news-list.html %}
  </div>
</section>

<section class="section section-rule">
  <div class="shell quick-links">
    <a href="{{ '/docs/data-structure/' | relative_url }}"><span>01</span><strong>Data structure</strong><small>How RoofVIP is organized</small></a>
    <a href="{{ '/docs/versioning/' | relative_url }}"><span>02</span><strong>Versioning</strong><small>Release states and policy</small></a>
    <a href="{{ '/team/' | relative_url }}"><span>03</span><strong>Contributors</strong><small>People behind the dataset</small></a>
    <a href="{{ '/docs/citation/' | relative_url }}"><span>04</span><strong>Citation</strong><small>How to reference RoofVIP</small></a>
  </div>
</section>
