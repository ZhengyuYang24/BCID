# BCID: Bridge Crack Image Dataset 🌉

![Status: Under Review](https://img.shields.io/badge/Status-Under%20Review-orange)
![Dataset Size: 2092](https://img.shields.io/badge/Dataset%20Size-2092%20Images-blue)
![Task: Semantic Segmentation](https://img.shields.io/badge/Task-Semantic%20Segmentation-brightgreen)

> **📌 Important Note to Reviewers / Editors:**
> Thank you for taking the time to review our manuscript. The full BCID dataset, including all raw images, pixel-level annotations, and the fixed data split files, is fully prepared. **It will be completely open-sourced and maintained in this repository immediately upon the acceptance of our paper.** > 
> Below is a comprehensive overview of the dataset structure and sample previews to demonstrate our readiness for release.

---

## 📖 Introduction
**BCID** is a self-constructed and meticulously annotated semantic segmentation dataset specifically designed for surface cracks in concrete bridges. The images were collected from real-world bridge inspection reports during routine maintenance operations, capturing cracks under diverse and realistic field conditions (e.g., complex concrete textures, spalling, and varying lighting).

Accurate crack segmentation is a prerequisite for reliable geometric quantification (length and width). This dataset aims to provide a robust benchmark for evaluating pixel-level crack detection algorithms.

## 📊 Dataset Statistics
* **Total Images:** 2,092 high-resolution image patches.
* **Image Resolution:** 512 × 512 pixels.
* **Annotation Type:** Pixel-level binary masks for semantic segmentation (Crack vs. Background).
* **Data Split:** The dataset is divided into training, validation, and test sets using a strict **8:1:1** ratio.

## 📁 Repository Structure (Upcoming)
Upon release, the repository will be organized as follows:

```text
BCID_Dataset/
├── train/
│   ├── images/          # Training images (1673 files)
│   └── masks/           # Pixel-level annotations (1673 files)
├── val/
│   ├── images/          # Validation images (209 files)
│   └── masks/           # Pixel-level annotations (209 files)
├── test/
│   ├── images/          # Test images (210 files)
│   └── masks/           # Pixel-level annotations (210 files)
└── splits/
    └── fixed_split.txt  # Explicit file list to ensure reproducibility
