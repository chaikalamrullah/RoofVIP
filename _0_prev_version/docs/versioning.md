---
layout: page
title: Versioning
permalink: /docs/versioning/
eyebrow: Documentation
description: RoofVIP uses explicit dataset versions and release states so that experiments remain traceable over time.
---
## Release states

RoofVIP pages distinguish four lifecycle states:

- **Planned** — a reserved future release with no stable specification.
- **In development** — implementation or data preparation is underway, but the contract may still change.
- **Release candidate** — the intended content is stable enough for final validation.
- **Released** — a published dataset state intended to be cited and reproduced.

The current site therefore treats **v1.0.0.0**, **v1.0.1.0**, and **v1.0.3.0** as released datasets, while **v1.0.2.0** remains in development.

## Four-field version identifiers

RoofVIP uses identifiers such as `1.0.0.0`, `1.0.1.0`, and `1.0.3.0`. Because this resembles—but is not identical to—standard three-field Semantic Versioning, the four positions should be understood as a **RoofVIP-specific dataset-version convention** rather than assumed to follow SemVer semantics.

The precise field-level semantics are not yet declared as a normative policy. Until that policy is fixed, the **complete four-field identifier** should be treated as an indivisible release identifier.

## Release relationships

A numerically later RoofVIP release does not necessarily mean that every earlier release is obsolete. Releases may provide different organizations or modalities for the same underlying geographic domain. For example:

- **v1.0.0.0** — original object-centred RGB + roof-vector benchmark;
- **v1.0.1.0** — elevation extension aligned to the original release;
- **v1.0.3.0** — multimodal fixed-scene representation with RGB, DSM, DTM, nDSM, LiDAR, and vector annotations.

Researchers should therefore select the release that matches the experimental contract and report it explicitly.

## Reproducibility rule

Publications and benchmark submissions should report the **full dataset version**. A benchmark result should additionally report its **benchmark protocol version** once a formal protocol is released.
