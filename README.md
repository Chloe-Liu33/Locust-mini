


# Locust-mini Dataset 🦗

[![Associated Model](https://img.shields.io/badge/Model-EG--PraNet-blue.svg)](https://github.com/Chloe-Liu33/PraNet-object-segmentation)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> Official dataset for the paper: **"Camouflaged locust segmentation based on PraNet"** (Computers and Electronics in Agriculture, 2022).

## 📌 Overview

**Locust-mini** is a specialized semantic segmentation dataset designed to tackle the highly challenging task of camouflaged object detection in complex agricultural and natural environments. 

The dataset primarily features locusts, mantises, grasshoppers, and similar insects that naturally blend their textures, colors, and contours into their surroundings. It serves as a robust benchmark for evaluating the feature extraction and generalization capabilities of computer vision models in real-world, high-noise scenarios.
[trainset link](https://drive.google.com/drive/folders/1MCLtYOzBNVjeUM2jjHdpBwfU4kj_ywei?usp=drive_link)\

[testset link](https://drive.google.com/drive/folders/1RIyv1FAsqrmwSr61D4vVTCb7sdoJQra9?usp=drive_link)\

## 📊 Dataset Details

The dataset provides high-quality images alongside precise pixel-level ground truth masks. It is carefully split to ensure rigorous model evaluation:

*   **Total Images:** 994
*   **Training Set:** 874 images
*   **Testing Set:** 120 images
*   **Subjects:** Camouflaged locusts, mantises, ants, bugs, grasshoppers, and bees.

## 🚀 Associated Model: EG-PraNet

This dataset was built in tandem with our custom segmentation architecture to solve real-world agricultural pest detection. 

To see how this dataset is utilized in an end-to-end deep learning pipeline, please visit our official model repository:
👉 **[EG-PraNet: Camouflaged Locust Segmentation](https://github.com/Chloe-Liu33/PraNet-object-segmentation)**

The EG-PraNet repository contains the complete execution pipeline, demonstrating how to leverage the Locust-mini dataset to achieve state-of-the-art accuracy and real-time inference throughput for plant protection robots.

## 📁 Directory Structure

Please ensure the dataset is structured as follows when loading it into your dataloader:

```text
Locust-mini/
│
├── train/
│   ├── images/          # 874 training images
│   └── masks/           # 874 ground truth masks
│
└── test/
    ├── images/          # 120 testing images
    └── masks/           # 120 ground truth masks# Locust-mini





