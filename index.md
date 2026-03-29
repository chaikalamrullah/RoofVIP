# RoofVIP

**RoofVIP** is a high-resolution dataset for building roof modeling, designed to support geometry-aware deep learning and 3D urban reconstruction.

Accurate roof modeling is fundamental to urban analytics, digital twins, and large-scale city reconstruction. However, progress in deep learning–based reconstruction remains constrained by the limited availability of diverse, high-resolution datasets with detailed geometric annotations. RoofVIP addresses this gap by providing very high-resolution RGB orthophotos paired with structured 2D roof vector annotations across diverse urban morphologies.

---

## Overview

**Version:** v1.0.0 (Munich, Germany)

This dataset provides:

* Tiled aerial image patches (20 cm resolution), each centered on individual buildings
* Roof annotations following Level of Detail 2 (LoD2) principles
* Polygon representations in NumPy format (`.npy`)

🔗 **Dataset (Zenodo):** https://doi.org/10.5281/zenodo.19315864
📄 **Paper (ISPRS Congress 2026):** Link will be provided upon publication

---

## Dataset Characteristics

* Very High Resolution (VHR) RGB orthophotos
* Diverse urban building typologies
* Geometry-focused annotations suitable for:

  * segmentation
  * vectorization
  * graph-based reconstruction

---

## License

This dataset is distributed under the Creative Commons Attribution 4.0 International License (CC BY 4.0).

RoofVIP v1.0.0 is derived from DOP20 RGB imagery provided by the Bavarian Surveying Administration (Bayerische Vermessungsverwaltung).

Users must provide attribution to both:

* the original data provider
* the authors of the RoofVIP dataset

No endorsement by the original licensor is implied.

---

## Citation

If you use this dataset, please cite: ** Link will be provided upon publication
