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

## Four-field version identifiers

RoofVIP currently uses identifiers such as `1.0.0.0` and `1.0.1.0`. Because this resembles—but is not identical to—standard three-field Semantic Versioning, the meaning of all four positions should be treated as a **RoofVIP-specific convention**.

The exact semantics of the four fields are intentionally not asserted here yet. Before additional releases depend on field-level meaning, the project should publish a stable mapping for what constitutes a major, structural/data, extension, or patch-level change.

## Reproducibility rule

Publications and benchmark submissions should report the full dataset version. A benchmark result should additionally report its benchmark protocol version.
