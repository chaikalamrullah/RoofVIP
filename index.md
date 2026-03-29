# RoofVIP

**RoofVIP** (Roof Vector Image Pair) is a high-resolution dataset for building roof modeling, designed to support geometry-aware deep learning and 3D urban reconstruction.

Accurate roof modeling is fundamental to urban analytics, digital twins, and large-scale city reconstruction. However, progress in deep learning–based reconstruction remains constrained by the limited availability of diverse, high-resolution datasets with detailed geometric annotations.  
RoofVIP addresses this gap by providing very high-resolution RGB orthophotos paired with structured 2D roof vector annotations across diverse urban morphologies.

---

## Dataset Overview

RoofVIP is developed as a **living, versioned dataset**, supporting continuous updates and community-driven improvements.

### Current Release

#### v1.0.0.0 — Munich, Germany

- **Resolution:** 20 cm (Very High Resolution RGB orthophotos)  
- **Source:** Digitales Orthophoto RGB 20 cm (DOP20 RGB)  
- **Provider:** Bavarian Surveying Administration (Bayerische Vermessungsverwaltung) via Bavarian Open Geodata  

**Content:**
- Tiled aerial image patches centered on individual buildings  
- Manual roof annotations following **Level of Detail 2 (LoD2)** principles in polygon annotations stored in NumPy format (`.npy`)
- Designed for:
  - Roof segmentation  
  - Vectorization  
  - Geometry-aware learning  
  - 3D reconstruction  

**Dataset (Zenodo):** https://doi.org/10.5281/zenodo.19315864  
**Paper (ISPRS Congress 2026):** Link will be provided upon publication  

---


## Community & Collaboration

RoofVIP is not only a dataset but also a **collaborative platform**.

Use GitHub Discussions to:
- Ask questions  
- Share research insights  
- Discuss methods and results  

Use Issues to report annotation errors or data inconsistencies.
We encourage community contributions to improve dataset quality and coverage.

---

## Contributors

**v1.0.0.0 — Munich, Germany**

- Chaikal Amrullah, Daniel Panangian, Guneet Mutreja, Youssef Abdelhedi, Dr. Ksenia Bittner [German Aerospace Center (DLR)]

---

## License

This dataset is released under the **Creative Commons Attribution 4.0 International License (CC BY 4.0)**.
RoofVIP v1.0.0 is derived from DOP20 RGB imagery provided by the Bavarian Surveying Administration (Bayerische Vermessungsverwaltung).

---

## Citation

Will be provided upon publication

---
