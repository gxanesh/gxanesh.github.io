---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My research focuses on **visual localization in GPS-denied environments**, combining deep learning with geometric reasoning to build accurate, robust, and deployable positioning systems using only passive sensors.

---

## Research Themes

### 1. Visual Localization without GPS
Developing localization systems that operate reliably in environments where GPS is unavailable, degraded, or adversarially denied.

- Passive sensing using cameras only  
- No reliance on RF, LiDAR, or external infrastructure  
- Robustness to environmental variations and viewpoint changes  

---

### 2. Landmark-Based Localization

Replacing traditional anchors (e.g., satellites or radio beacons) with **pre-mapped visual landmarks**.

- Landmark detection using deep neural networks  
- Semantic anchoring for localization  
- Integration of perception and geometry  

---

### 3. Stereo Vision and Depth Estimation

Estimating metric distance using stereo image pairs.

- Disparity-based depth estimation  
- Region-of-interest (ROI) depth extraction from detected landmarks  
- Noise-aware depth aggregation for robust range estimation  

---

### 4. Learning-Based Perception

Designing efficient and accurate models for landmark recognition.

- YOLO-based architectures for real-time detection  
- Multi-class landmark recognition  
- Data augmentation for robustness under real-world conditions  

---

### 5. SLAM / Visual Odometry Benchmarking

Evaluating learning-based localization against classical and modern baselines.

- Comparison with SLAM and VO systems  
- Metrics: Absolute Pose Error (APE), RMSE  
- Cross-dataset and sequence-level evaluation  

---

## Current Research

### LanBLoc: Landmark-Based Visual Localization

LanBLoc is a **passive visual localization framework** that leverages visual landmarks as anchors for position estimation.

#### Key Contributions

- **Landmark-driven localization** using semantic detection instead of geometric features alone  
- **Stereo-based distance estimation** for accurate range measurement  
- **Trilateration-based positioning** using multiple landmark observations  
- **Integration of deep learning and geometric optimization**  

#### System Pipeline

1. Detect landmarks using a deep learning model  
2. Estimate distance using stereo depth  
3. Retrieve landmark positions from a map  
4. Compute position via trilateration  
5. Refine estimates using optimization  

#### Performance

- Achieves significantly lower localization error compared to SLAM/VO baselines  
- Demonstrates strong robustness in structured outdoor environments  
- Suitable for real-time deployment with lightweight models  

---

## Ongoing Work

### LanBLoc-2L: Two-Landmark Localization

- Resolving geometric ambiguity with fewer landmarks  
- Candidate generation via geometry  
- Disambiguation using image retrieval and descriptor matching  

---

### Cross-View Geo-Localization

Exploring alignment between aerial and ground views for large-scale localization.

- Feature learning for viewpoint invariance  
- Coarse-to-fine retrieval pipelines  
- Integration with localization frameworks  

---

### Model Benchmarking and Optimization

Systematic evaluation of detection models for landmark recognition.

- YOLO variants (v5–v12)  
- Transformer-based detectors (RT-DETR)  
- Two-stage models (Faster R-CNN)  

Focus on:
- Precision / Recall / mAP  
- Inference latency  
- Deployment feasibility  

---

## Research Vision

My long-term goal is to develop **scalable, infrastructure-free localization systems** that can operate reliably in real-world, constrained, and adversarial environments.

This includes:

- Fully passive navigation systems  
- Hybrid learning + geometry frameworks  
- Deployment on edge and resource-constrained devices  
- Real-world validation in challenging environments  

---