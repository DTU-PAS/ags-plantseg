# Scale Matters: Adaptive Granularity Selection for Cross-Species 3D Plant Organ Segmentation

[![Project Page](https://img.shields.io/badge/Project_Page-dtu--pas.github.io-2f6f4f?style=flat-square)](https://dtu-pas.github.io/ags-plantseg/)
[![Paper](https://img.shields.io/badge/Paper-Coming_Soon-lightgrey?style=flat-square)]()
[![Venue](https://img.shields.io/badge/Venue-CVPPA_@_ECCV_2026-4c72b0?style=flat-square)]()

**[Carla Salazar](https://scholar.google.com/citations?user=HnjzYD0AAAAJ&hl=en) · [Lazaros Nalpantidis](https://scholar.google.com/citations?user=YAx9230AAAAJ&hl=en)**
DTU PAS, Technical University of Denmark

---

## Overview

AGS-PlantSeg is a few-shot 3D plant organ segmentation method that combines frozen Utonia features with an Adaptive Granularity Selection (AGS) module. Instead of using a single fixed spatial granularity, AGS selects suitable feature scales for each plant during training and inference using prototype-based measures of class separation, compactness, and boundary consistency. The selected features are classified with a lightweight MLP, improving cross-species generalization and outperforming the best fixed-granularity baseline by 2.2 mIoU points.

## Highlights

- Few-shot 3D plant organ segmentation, generalizing across species with minimal supervision
- Frozen Utonia backbone features, no backbone fine-tuning required
- Adaptive Granularity Selection (AGS): per-plant scale selection via prototype-based class separation, compactness, and boundary consistency
- Lightweight MLP classifier head on top of the selected features
- +2.2 mIoU over the best fixed-granularity baseline, with stronger cross-species generalization

## Status

Code coming soon.

Project page: **https://dtu-pas.github.io/ags-plantseg/**

## Citation

The paper has been accepted to the CVPPA Workshop (Computer Vision in Plant Phenotyping and Agriculture) at ECCV 2026. The full citation (pages, DOI, proceedings link) will be added once the proceedings are published — in the meantime, here is a placeholder you can use:

```bibtex
@inproceedings{salazar2026scalematters,
  title     = {Scale Matters: Adaptive Granularity Selection for Cross-Species 3D Plant Organ Segmentation},
  author    = {Salazar, Carla and Nalpantidis, Lazaros},
  booktitle = {Proceedings of the ECCV Workshop on Computer Vision in Plant Phenotyping and Agriculture (CVPPA)},
  year      = {2026},
  note      = {TODO: add pages, DOI, and proceedings URL once published}
}
```
