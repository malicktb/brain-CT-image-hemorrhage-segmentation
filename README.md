# 🧠 Brain Hemorrhage CT Image Segmentation and Classification

This project explores the automatic detection, segmentation, and classification of brain hemorrhages from CT scan images using both traditional machine learning techniques and deep learning models.

## 📌 Overview

Intracranial hemorrhages are critical medical conditions where bleeding occurs inside the skull. Fast and accurate identification of the hemorrhage type is essential for timely treatment. This project aims to support that process by developing models that can:

- Segment the hemorrhage area in brain CT scans
- Classify the type of hemorrhage (e.g., subdural, epidural, subarachnoid, intraparenchymal, etc.)

We utilize both handcrafted feature-based models and deep learning techniques to evaluate performance across various approaches.

## 🗂️ Dataset

The dataset was provided by **Zeta Surgical**, a biotech company based in Boston. It includes:

- Brain CT scan slices (512x512 resolution)
- Images captured under different window settings (e.g., brain, bone)
- Polygon-labeled hemorrhage regions (.csv format)
- Metadata: hemorrhage types, labeler agreement, region of interest (ROI) counts

**Note:** Due to data licensing, the dataset cannot be made publicly available.

## 🧑‍💻 Authors

- Malick Tobe  
- Juan Attias
- Daniel Ma
- Priya Mandala

## 📜 Acknowledgments

- Zeta Surgical for providing the CT dataset  
- Northeastern University – Project done as part of course MATH7243

---

**Disclaimer**: This repository is for educational and research purposes only and is not intended for clinical use.
