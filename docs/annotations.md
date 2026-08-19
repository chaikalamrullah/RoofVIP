---
layout: page
title: Annotations
permalink: /docs/annotations/
eyebrow: Documentation
description: RoofVIP uses structured roof geometry rather than treating roof reconstruction only as raster segmentation.
---
## Geometry-oriented annotation

The original release contains manually created roof-plane polygon geometry stored in NumPy (`.npy`) representation and designed around LoD2-oriented roof structure.

RoofVIP is intended to support research where prediction quality depends not only on pixel occupancy but also on corners, edges, polygons, and structural relationships.

## Release-specific schema

The complete serialized field schema should be documented per stable release before users rely on it programmatically. Future annotation extensions should be introduced as explicit release changes rather than silently modifying earlier formats.
