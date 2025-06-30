# WeaponVision-AI

# WeaponVision AI 🔫📹

**WeaponVision AI** is a cutting-edge deep learning-based surveillance software for **real-time weapon detection** in CCTV feeds, videos, and images. It is powered by a modified **YOLOv7** architecture, trained on over 79,000 curated firearm images and optimized for both **low-light performance** and **edge deployment**.

[![Paper DOI](https://img.shields.io/badge/Published-Springer%20Int.%20J.%20Inf.%20Technol.-blue)](https://doi.org/10.1007/s41870-024-02375-y)
[![GitHub Repo](https://img.shields.io/badge/GitHub-Repository-green)](https://github.com/PavinderYadav0/WeaponVision-AI)

---

## 🔍 Features

- **Real-time detection** of handguns and rifles from live video, images, or webcam.
- **Low-light vision** support via integrated **YOLOv7-DarkVision**.
- User-friendly **Graphical User Interface (GUI)** with controls for:
  - FPS monitoring
  - Night-mode activation
  - Sound alerts
  - Live webcam feed
  - Email notifications
- Deployment on **CPU** (standard and quantized) and **GPU** configurations.
- Precision up to **91.75%** and mAP up to **92.15%** across real-world scenarios.

---

## 📥 Downloads

You can download precompiled versions of WeaponVision AI below:

| Version | Platform | FPS | Size | Download |
|--------|----------|-----|------|----------|
| WeaponVision AIGPU-0.1 | GPU (YOLOv7) | ~60 | 2.90 GB | [Download](https://drive.google.com/drive/folders/1t_10FD1ufkXGL4Od0IO39KHQa0LjVe62?usp=sharing) |
| WeaponVision AICPU-0.1 | CPU (YOLOv7) | ~5 | 825 MB | [Download](https://drive.google.com/file/d/13t7sG2aQHYBUOXpR7XpaB9CZqu64h1Y0/view?usp=sharing) |
| WeaponVision AICPU_optimized-0.1 | CPU (Quantized) | ~20 | 261 MB | [Download](https://drive.google.com/file/d/1GKYhsB3Smup-AGLu0RcYQloHPBUKG-PU/view?usp=sharing) |

> 📦 All software versions are tested on Intel i5/i7 13th Gen, AMD Ryzen 5000, and NVIDIA GPUs.

---

## 🧪 Dataset Overview

WeaponVision AI was trained on a comprehensive dataset of **79,558 images**, covering:

- **Sources**: PDD, YouTubeGDD, MAD, WDD, and a self-created dataset
- **Classes**: Handgun, Rifle
- **Conditions**: Blurry, dark background, night scenes, real-world settings

---

## ⚙️ Installation

1. Download the appropriate software version for your platform.
2. Extract the ZIP file.
3. Run the executable or launch from your terminal.
4. Use GUI options to upload files, enable webcam, or toggle night mode.

---

## 📈 Performance Metrics

| Metric | Value |
|--------|-------|
| Precision | 91.75% |
| Recall | 88.34% |
| F1-Score | 92.75% |
| mAP@0.5 | 92.15% |

Tested across real-world CCTV datasets and conditions.

---

## 📄 Citation

If you use this software for research or publication, please cite:

> Yadav, P., Gupta, N., & Sharma, P.K. (2025). WeaponVision AI: a software for strengthening surveillance through deep learning in real-time automated weapon detection. Int. J. Inf. Technol. https://doi.org/10.1007/s41870-024-02375-y

---

## 📧 Contact

- 📬 Pavinder Yadav – [pavinder.yadav0@gmail.com](mailto:pavinder.yadav0@gmail.com)
- 🧑‍💻 GitHub – [@PavinderYadav0](https://github.com/PavinderYadav0)

---

## 🔒 License

This project is for **research and academic use** only. Please refer to the LICENSE file in the repository for more information.
