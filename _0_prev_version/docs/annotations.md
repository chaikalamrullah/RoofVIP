---
layout: page
title: Annotations
permalink: /docs/annotations/
eyebrow: Documentation
description: RoofVIP uses structured LoD 2.0 roof geometry that can support point, edge, polygon, and graph learning targets.
---
## Geometry-oriented annotation

RoofVIP contains manually labelled building roof structures following a **Level of Detail (LoD) 2.0** representation. Individual roof planes are represented as polygons in a common projected coordinate reference system.

The resulting geometry can be interpreted at several structural levels:

- polygon vertices as **point targets**;
- polygon boundaries as **edge or line targets**;
- roof planes as **polygon targets**; and
- connectivity among geometric entities as **graph-structured targets**.

## Serialized representations

The source vector annotations were initially created in **ESRI Shapefile (`.shp`)** format. For machine-learning workflows, RoofVIP also provides **NumPy-based polygon representations (`.npy`)** where applicable.

The original object-centred release and the fixed-scene release do not necessarily have identical packaging. Users should treat each release page as the authoritative description of the representation provided by that version.

## Partial buildings in v1.0.3.0

In the fixed-scene organization, buildings intersected by a scene boundary are **retained rather than removed**. Their roof-plane geometry is associated with the corresponding scene so that the benchmark reflects realistic scene boundaries instead of only complete isolated objects.
