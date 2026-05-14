---
layout: single
title: "CV"
permalink: /cv/
author_profile: true
description: "Curriculum Vitae of Ganesh Sapkota - education, research experience, publications, skills, leadership and awards in computer science and AI."
---

[Download CV (PDF)](/cv/Ganesh_Sapkota_CV.pdf){: .btn .btn--primary}

## Summary

Ph.D. Candidate in Computer Science with 4+ years of **Army Research Laboratory (ARL)-funded** research in GPS-denied visual localization, multi-sensor fusion, and deep learning for autonomous navigation. Published IEEE author (3 peer-reviewed venues) with end-to-end experience from algorithm prototyping to field validation.

---

## Education

**Ph.D. Candidate, Computer Science** | GPA: 3.7/4.0
*Missouri University of Science and Technology, Rolla, MO* | Aug 2021 -- Present
- Advisor: Dr. Sanjay Madria (Army Research Laboratory funded)
- Focus: GPS-Denied Visual Localization, Deep Learning, Multi-Camera Stereo Systems, Sensor Fusion
- Relevant Coursework: Advanced ML in Computer Vision, Machine Learning, Data Mining, NLP


**B.E., Computer Engineering** | GPA: 3.5/4.0
*Tribhuvan University, Institute of Engineering* | Nov 2013 -- Jun 2017

---

## Research Experience

**Graduate Research Assistant -- Army Research Laboratory Funded**
*Missouri University of Science and Technology, Rolla, MO* | Aug 2021 -- Present

- **GPS-Denied Localization Framework (LanBLoc):** Designed and implemented a stereo-vision-based absolute localization system for GNSS-denied outdoor environments; integrated YOLO-based object detection with stereo ranging for landmark-referenced positioning.
- **Navigation Pipeline:** Developed vision-driven navigation pipelines coupling visual localization with obstacle avoidance and path optimization for autonomous ground platforms in GPS-degraded scenarios.
- **Sensor Fusion & Multi-Metric Localization:** Built an image-retrieval-based localization method using dynamic vicinity clustering and multi-metric descriptor scoring (centroid similarity, PCA reconstruction error, k-NN matching) to handle geometric ambiguity in landmark-sparse environments.
- **SLAM/VO Evaluation:** Installed, configured, and benchmarked multiple SLAM and visual odometry systems (DROID-SLAM, DPV-SLAM, GO-SLAM, DPVO, ORB-SLAM3) on real stereo datasets; developed evaluation pipelines for trajectory accuracy (ATE/RTE metrics).
- **Cross-View Geo-Localization (HCVGLoc):** Engineered a multi-GPU DDP training pipeline in PyTorch for UAV-to-satellite geo-localization, incorporating domain adversarial training, rotation-aware modules, and uncertainty quantification for GPS-denied UAV navigation.
- **Dataset Collection & Validation:** Built and released a real-world stereo landmark dataset; designed end-to-end data collection, annotation, and validation pipelines for large-scale outdoor image datasets.
- Authored **3 peer-reviewed IEEE publications** (WoWMoM 2025, WoWMoM 2024, AIPR 2023); active peer reviewer for IEEE conferences and journals.

---

## Professional Experience

**Graduate Teaching Assistant**
*Missouri University of Science and Technology, Rolla, MO* | Aug 2024 -- Present
- Led Data Structures lab sessions in C++ and delivered hands-on big data technology sessions (Hadoop MapReduce, Spark, HBase, MongoDB).

**Lecturer, Computer Science**
*Sagarmatha Engineering College, NP* | Feb 2019 -- Aug 2021
- Taught programming, databases, and operating systems; supervised undergraduate ML/CV capstone projects.

**Software Engineer**
*Pioneer Solutions LLC (acquired by Hitachi Energy), Denver, CO* | Dec 2017 -- Feb 2019
- Developed and maintained ERP modules using SQL Server, PHP, and JavaScript.

---

## Skills

- **Languages:** Python, C/C++, Bash, R, JavaScript, SQL
- **Navigation & Perception:** Visual SLAM/VO (ORB-SLAM3, DROID-SLAM, DPV-SLAM, GO-SLAM, DPVO), Stereo Vision, Structure-from-Motion (SfM), Multi-View Stereo (MVS), 3D Reconstruction
- **Sensor Fusion:** Extended Kalman Filter (EKF), Multi-Sensor Fusion (stereo cameras, IMUs), Sensor-Agnostic Localization
- **Deep Learning & CV:** PyTorch, TensorFlow, OpenCV, MMCV, Object Detection (YOLO, DETR, SSD, RCNN), Transformers, CNNs
- **Simulation & Tools:** ROS (familiarity), Git/GitHub, Docker, Linux/UNIX, Jupyter, NumPy, Pandas, Matplotlib
- **Hardware Familiarity:** NVIDIA GPUs (multi-GPU DDP training), Stereo Camera Rigs, Edge Deployment Pipelines

---

## Selected Publications

1. Sapkota, G., & Madria, S. (2025). *SafeNav: Safe Path Navigation using Landmark Based Localization in GPS-denied Environment.* **IEEE WoWMoM 2025**.
2. Sapkota, G., & Madria, S. (2024). *Landmark-based Localization using Stereo Vision and Deep Learning in GPS-Denied Battlefield Environment.* **IEEE WoWMoM 2024**.
3. Sapkota, G., & Madria, S. (2023). *Landmark Stereo Dataset for Landmark Recognition and Moving Node Localization.* **IEEE AIPR 2023**.

---

## Selected Projects

**HCVGLoc -- Hierarchical Cross-View Geo-Localization for UAVs**
- Designed a 3-stage hierarchical localization pipeline for GPS-denied UAV navigation using satellite imagery, incorporating domain adversarial learning, uncertainty quantification, and Extended Kalman Filter (EKF) fusion.
- Trained on multi-GPU DDP setup (4x GPU) with datasets CVUSA, CVACT, VIGOR, and University-1652; implemented gallery-based evaluation with Recall@K metrics.

**Radiogenomic Brain Tumor Classification**
- Deep learning pipeline for MGMT methylation prediction from MRI integrating DenseNet-169 and SAM; achieved 70% accuracy and 67.54% AUC (RSNA-MICCAI).

---

## Honors & Activities

- **Best Poster Award (1st Place)** -- ISC Poster Presentation, Missouri S&T, Nov 2024
- **Best Poster Award (1st Place)** -- Pathways Symposium, NextGen Precision Health 2026
- **Founder & President**, Nepali Students' Association (NSA-MST), Aug 2023 -- Present
- **Finance Director**, Council of Graduate Students (CGS), Missouri S&T, Aug 2024 -- Present
- **Certifications:** Scientific Computing with Python; ML & Statistical Analysis (WorldQuant University)
