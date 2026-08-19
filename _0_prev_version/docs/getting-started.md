---
layout: page
title: Getting started
permalink: /docs/getting-started/
eyebrow: Documentation
description: Choose a RoofVIP release based on the sample organization, modality, and experiment you need.
---
## 1. Start from the release, not from “latest”

For reproducible experiments, record the exact RoofVIP version you use. The [Dataset]({{ '/dataset/' | relative_url }}) page lists released and provisional versions separately.

## 2. Choose the sample organization you need

The original **v1.0.0.0** benchmark is primarily object-centred. **v1.0.3.0** instead provides fixed **256 × 256 pixel scenes**, retaining multiple buildings and partial buildings where they intersect scene boundaries.

## 3. Choose modalities explicitly

For RGB + roof-vector experiments, the original release may be sufficient. For elevation-, point-cloud-, or multimodal experiments, [v1.0.3.0]({{ '/dataset/v1.0.3.0/' | relative_url }}) provides co-registered **RGB, DSM, DTM, nDSM, LiDAR, and vector** products using common scene identifiers.

## 4. Use the predefined split for v1.0.3.0 benchmarking

Version 1.0.3.0 provides **8,195 training**, **1,022 validation**, and **1,028 test** scenes. The geographic domain is partitioned before tiling to reduce spatial leakage, and the subsets are balanced using PCA-based structural-complexity descriptors.

## 5. Record the benchmark protocol separately

When using the RoofVIP Benchmark evaluation layer, report both the **dataset release** and the **benchmark protocol version**. The dataset release v1.0.3.0 is available now; the formal evaluation protocol and leaderboard specification remain under development.
