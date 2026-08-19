---
layout: page
title: Data structure
permalink: /docs/data-structure/
eyebrow: Documentation
description: The organizational contract connecting RoofVIP samples, modalities, vectors, and metadata.
---
## Conceptual structure

RoofVIP associates a stable sample identifier with the modalities available in a particular release.

For the multimodal fixed-scene release **v1.0.3.0**, the conceptual relationship is:

```text
Scene ID
├── RGB
├── DSM
├── DTM
├── nDSM
├── LiDAR point cloud
├── vector roof geometry
└── split / metadata
```

All products belonging to a scene describe the same spatial extent. Version 1.0.3.0 uses **256 × 256 pixel scenes** on a **0.2 m scene grid**, corresponding to approximately **51.2 × 51.2 m** on the ground.

The original v1.0.0.0 release has a different, primarily object-centred organization. The exact physical folder structure, serialized fields, and modality availability should therefore always be read from the corresponding release page rather than inferred from another version.

## Why keep this separate from release pages?

The documentation defines the *meaning* of common concepts. A release page defines the *actual contents* of one published dataset version. Keeping those roles separate lets RoofVIP add new representations without rewriting the historical contract of older releases.
