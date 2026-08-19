---
layout: page
title: Data structure
permalink: /docs/data-structure/
eyebrow: Documentation
description: The organizational contract connecting RoofVIP samples, modalities, vectors, and metadata.
---
## Conceptual structure

A RoofVIP sample is identified by a stable dataset identifier and may be associated with several aligned modalities depending on the release.

```text
RoofVIP ID
├── RGB
├── DSM          (where provided)
├── DTM          (where provided)
├── nDSM         (where provided)
├── vector geometry
└── metadata
```

The exact physical folder structure, field definitions, and modality availability should always be read from the corresponding release page.

## Why keep this separate from release pages?

The documentation defines the *meaning* of common concepts. A release page defines the *actual contents* of one frozen or published dataset version. Keeping those roles separate makes future extensions easier to document without rewriting historical releases.
