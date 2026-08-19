---
layout: default
title: Benchmark
permalink: /benchmark/
---
<section class="page-hero benchmark-hero">
  <div class="shell narrow">
    <div class="eyebrow">Benchmark</div>
    <h1>Make roof reconstruction <em>comparable.</em></h1>
    <p class="page-lead">The RoofVIP Benchmark is being designed as a stable evaluation layer above the evolving dataset. The current benchmark dataset is **RoofVIP v1.0.3.0**; the formal evaluation protocol and public leaderboard specification remain under development.</p>
  </div>
</section>
<section class="page-content">
  <div class="shell narrow">
    <div class="task-grid">
      <article><span>01</span><h3>Point geometry</h3><p>Evaluate the localization and detection of structurally meaningful roof points.</p></article>
      <article><span>02</span><h3>Edge structure</h3><p>Evaluate reconstructed roof-line geometry and connectivity.</p></article>
      <article><span>03</span><h3>Roof polygons</h3><p>Evaluate roof-plane or polygon reconstruction after standardized conversion rules.</p></article>
      <article><span>04</span><h3>Topology</h3><p>Reserve a place for graph-structural evaluation where the benchmark task requires it.</p></article>
    </div>

    <div class="prose benchmark-copy">
      <h2>Evaluation protocol</h2>
      <p>The final metric definitions, confidence thresholds, conversion rules, and benchmark test release are still being finalized. They will be published as a versioned protocol rather than silently edited in place.</p>
      <p><a class="text-link" href="{{ '/benchmark/evaluation/' | relative_url }}">Evaluation placeholder →</a></p>

      <h2>Leaderboard</h2>
    </div>
    {% include leaderboard.html %}
    <p class="benchmark-link"><a class="button secondary" href="{{ '/benchmark/leaderboard/' | relative_url }}">Open leaderboard page</a></p>
  </div>
</section>
