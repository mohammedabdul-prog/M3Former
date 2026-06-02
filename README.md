# M³Former: Multi-Scale Network via Multi-Boundary Block and Multi-Refinement Transformer for Polyp Segmentation

This repository contains the official implementation of **M³Former**, a novel hybrid framework for polyp segmentation that combines multi-scale feature aggregation, boundary uncertainty refinement, hard-region mining, and uncertainty-aware frequency refinement.

---

## Framework Overview

<p align="center">
  <img src="images/m3former.jpg" width="900">
</p>

<p align="center">
<b>Figure 1.</b> Overall architecture of the proposed M³Former framework.
</p>

---

## Main Results

### Seen Datasets

| Dataset | Dice (%) | IoU (%) |
|----------|----------|----------|
| Kvasir-SEG | **93.1** | **88.3** |
| CVC-ClinicDB | **95.1** | **91.2** |

### Cross-Dataset Evaluation

| Dataset | Dice (%) | IoU (%) |
|----------|----------|----------|
| ETIS-Larib | **81.3** | **73.4** |
| CVC-ColonDB | **80.1** | **72.7** |

---

## Qualitative Results

<p align="center">
  <img src="images/seen.png" width="900">
</p>

<p align="center">
<b>Figure 2.</b> Segmentation results on Kvasir-SEG and CVC-ClinicDB.
</p>

<br>

<p align="center">
  <img src="images/unseen.png" width="900">
</p>

<p align="center">
<b>Figure 3.</b> Cross-dataset generalization results on ETIS-Larib and CVC-ColonDB.
</p>

---

## Ablation Study

<p align="center">
  <img src="images/ablation.png" width="700">
</p>

<p align="center">
<b>Figure 4.</b> Contribution of the proposed ACF, BUR, AHR, and UAFR modules.
</p>

---

## Datasets

Experiments were conducted on four publicly available benchmark datasets:

- Kvasir-SEG
- CVC-ClinicDB
- CVC-ColonDB
- ETIS-Larib

---

## Code Availability

The source code, pretrained weights, and training scripts will be released after the paper is accepted and officially published.

**Current Status:** Paper under review.

Please stay tuned for updates.

---

## Citation

If you find this work useful in your research, please cite:

```bibtex
@article{almukhtar2026m3former,
  title={M$^{3}$Former: Multi-Scale Network via Multi-Boundary Block and Multi-Refinement Transformer for Polyp Segmentation},
  author={Almukhtar, Mohammed and Wang, Xiaoli and Zhao, Yu-qian and Syed, Akram},
  journal={Under Review},
  year={2026}
}
```

---

## Authors

Mohammed Almukhtar  
Xiaoli Wang  
Yu-qian Zhao  
Akram Syed  

School of Automation, Central South University, China
