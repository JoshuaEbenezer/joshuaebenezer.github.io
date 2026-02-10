---
layout: page
title: Conditional Wasserstein GANs for Image Dehazing
description: Novel application of CWGANs for single image dehazing
img: assets/img/projects/cwgan.png
importance: 2
date: 2018-08-01
category: research
---

**Project Supervisor:** Professor Sudipta Mukhopadhyay (IIT Kharagpur)

Achieved state-of-the-art results for single image dehazing by training a conditional Wasserstein GAN using the pix2pix model architecture. The approach combined multiple loss functions (perceptual loss, MSE, L1, and texture loss) and was evaluated on standard fog removal datasets (D-Hazy and O-Haze).

**Implementation Details:**

- Framework: PyTorch
- Model: Conditional Wasserstein GAN (pix2pix)
- Training datasets: D-Hazy, O-Haze
- Key innovation: Multi-component loss function design for fog removal

**Result:** Significantly improved dehazing quality compared to traditional methods, with realistic reconstruction of haze-occluded regions.

[Project Paper](/assets/pdf/cwgan.pdf) | [Publication: EUSIPCO 2019](https://ieeexplore.ieee.org/document/8902992)
