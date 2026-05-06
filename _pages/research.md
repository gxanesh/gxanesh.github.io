---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
description: "Research on visual localization in GPS-denied environments, landmark-based positioning, stereo vision, and deep learning for autonomous navigation."
---

My research focuses on **visual localization in GPS-denied environments**, combining deep learning with geometric reasoning to build accurate and deployable positioning systems using only passive sensors.

---

## LanBLoc: Landmark-Based Visual Localization

A passive visual localization framework that replaces traditional radio-based anchors with pre-mapped visual landmarks.

- **Landmark detection** using YOLO-based deep learning models
- **Stereo vision** for metric distance estimation
- **Trilateration** for position computation from multiple landmark observations
- **Geometric optimization** for refined, accurate estimates

Achieves significantly lower localization error compared to SLAM/VO baselines and is suitable for real-time deployment.

<img src="/images/lanbloc-light.png" alt="LanBLoc Architecture" class="align-center theme-light-only" style="width: 70%;" />
<img src="/images/lanbloc-dark.png" alt="LanBLoc Architecture" class="align-center theme-dark-only" style="width: 70%;" />

---

## LanBLoc-2L: Two-Landmark Localization

Extending LanBLoc to operate with fewer landmarks by resolving geometric ambiguity through candidate generation and image-retrieval-based disambiguation.

<img src="/images/lanbloc-2l-light.png" alt="LanBLoc-2L Architecture" class="align-center theme-light-only" style="width: 50%;" />
<img src="/images/lanbloc-2l-dark.png" alt="LanBLoc-2L Architecture" class="align-center theme-dark-only" style="width: 50%;" />

---

## Cross-View Geo-Localization

Exploring alignment between drone and satellite views for large-scale UAV geo-localization using viewpoint-invariant feature learning and coarse-to-fine retrieval.

---

## Model Benchmarking

Systematic evaluation of detection architectures for landmark recognition:

- YOLO variants (v5--v12)
- Transformer-based detectors (RT-DETR)
- Two-stage models (Faster R-CNN)

Focused on precision, recall, mAP, inference latency, and deployment feasibility.

---

## Research Vision

My long-term goal is to develop **scalable, infrastructure-free localization systems** that operate reliably in real-world, constrained, and adversarial environments -- fully passive, hybrid learning + geometry, deployable on edge devices.
