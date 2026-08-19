---
layout: page
title: Evaluation
permalink: /benchmark/evaluation/
eyebrow: Benchmark protocol
description: A placeholder for the versioned RoofVIP evaluation specification.
---
## Protocol status

The benchmark protocol is **not yet released**. Metric definitions shown in future drafts should be treated as provisional until a protocol version is assigned.

## Planned specification

The released protocol should state, at minimum:

- benchmark task and admissible model inputs;
- exact RoofVIP dataset version used for evaluation;
- train/validation/test split definition;
- prediction confidence and filtering rules;
- reference-to-prediction matching procedure;
- point, line, polygon, and topology metrics where applicable;
- geometry conversion rules for methods with different native outputs;
- leaderboard ranking criterion and tie handling;
- submission format and reproducibility requirements.

## Version binding

A benchmark result should identify both a **dataset release** and a **benchmark protocol version**. This lets RoofVIP evolve without making historical leaderboard entries ambiguous.
