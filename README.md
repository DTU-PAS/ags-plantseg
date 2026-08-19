# Scale Matters: Adaptive Granularity Selection for Cross-Species 3D Plant Organ Segmentation

<p align="center">
  <a href="https://dtu-pas.github.io/ags-plantseg/"><img src="https://img.shields.io/badge/🌐-Project%20Page-green" alt="Project Page"></a>
  <a href="https://arxiv.org/abs/2608.17803"><img src="https://img.shields.io/badge/📄-arXiv-b31b1b" alt="arXiv"></a>
</p>

<p align="center">
  <a href="https://scholar.google.com/citations?user=HnjzYD0AAAAJ&hl=en">Carla Salazar</a> ·
  <a href="https://scholar.google.com/citations?user=YAx9230AAAAJ&hl=en">Lazaros Nalpantidis</a>
</p>

<p align="center">
  <em>CVPPA Workshop @ ECCV 2026 — Computer Vision in Plant Phenotyping and Agriculture</em>
</p>

---

Official repository for the paper *"Scale Matters: Adaptive Granularity Selection for
Cross-Species 3D Plant Organ Segmentation"* (CVPPA Workshop @ ECCV 2026), introducing
**AGS-PlantSeg**, a few-shot 3D plant organ segmentation method that combines frozen Utonia
features with an **Adaptive Granularity Selection (AGS)** module. Instead of a single fixed
spatial granularity, AGS selects per-plant feature scales during training and inference using
prototype-based measures of class separation, compactness, and boundary consistency, improving
cross-species generalization and outperforming the best fixed-granularity baseline by 2.5 mIoU.

> **Code is being finalized and will be released soon.** Star/watch this repo to be notified.

## Citation

If you find this work useful, please cite:

```bibtex
@inproceedings{salazar2026scalematters,
  title     = {Scale Matters: Adaptive Granularity Selection for Cross-Species 3D Plant Organ Segmentation},
  author    = {Salazar, Carla and Nalpantidis, Lazaros},
  booktitle = {Proceedings of the European Conference on Computer Vision (ECCV) Workshops},
  year      = {2026},
  eprint    = {2608.17803},
  archivePrefix = {arXiv},
  primaryClass = {cs.CV}
}
```
