# 🎨 Enhanced Neural Style Transfer using VGG‑19 and Gram Matrix

> A deep learning‑based system for artistic style transfer combining the structural patterns of one image with the textures of another — delivering photo‑realistic stylizations with advanced performance benchmarking.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE) 
[![Python](https://img.shields.io/badge/Python-3.10-blue.svg)]()
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg)]()
[![PyTorch](https://img.shields.io/badge/PyTorch-1.13+-red.svg)]()
[![Paper](https://img.shields.io/badge/Research-Published-green.svg)](https://drive.google.com/file/d/17j1QJ3JQ0NJ8wjKVsAOBrOH_Wf41V8Z_/view?usp=sharing)

---

## 🧠 Overview

This repository implements an **Enhanced Neural Style Transfer (NST)** system based on **VGG‑19** and **Gram matrix correlation** to capture intricate textures and global artistic patterns.  
Built upon both **TensorFlow** and **PyTorch**, the implementation focuses on computational efficiency, stylistic accuracy, and detailed metric benchmarking.

The project has been **published in FMDB Transactions on Sustainable Computing Systems, Vol. 3, 2025.**

---

## ✨ Features

- **High‑Fidelity Style Transfer** using VGG‑19 and Gram matrix‑based texture learning  
- **Supports Multiple Architectures:** VIT, MobileVIT, EfficientNet, and ResNet  
- **Automated Metric Logging:** SSIM, PSNR, LPIPS, Loss values  
- **Per‑iteration Analytics:** logs saved as `.csv` files  
- **Optional BLIP‑2 Integration** for automatic image captioning  
- **Complete Reproducibility:** lightweight, pip‑installable dependencies  

---

## 📦 Installation

Clone the repository and install dependencies:

git clone https://github.com/your-username/enhanced-nst.git
cd enhanced-nst
pip install -r requirements.txt


All dependencies (TensorFlow, PyTorch, Matplotlib, LPIPS, timm, scikit-image, Pillow, pandas) are available on PyPI.

---
## 🧾 Notes for Usage

These versions are chosen to be cross-compatible with **TensorFlow ≥2.13** and **PyTorch ≥2.1** (2025-supported stable versions).  

If your project runs on lower hardware tiers or CPU only, you can uninstall GPU CUDA packages automatically with:

pip uninstall nvidia-cublas-cu12 nvidia-cudnn-cu12 torch torchvision

To install everything:

pip install -r requirements.txt

---

## 🚀 Quick Start

1. Place your content and style images in the `images/` directory.
2. Run the model you want for the process from the available set of models.
3. Generated image and the metrics will be currently stored in the same directory as the notebook.


---

## 📊 Metrics & Output

- **Output Image:** `.jpg` stylized result  
- **Metrics CSV:** `Metrics/metrics.csv` containing iteration‑wise:
  - Structural Similarity (SSIM)
  - Peak Signal‑to‑Noise Ratio (PSNR)
  - Learned Perceptual Image Patch Similarity (LPIPS)
  - Content/Style/Total Loss values

---

## 📁 Repository Structure

├── images/ # Content, style, and result images
├── Metrics/ # Stored metric logs in CSV
├── Notebooks/ # Jupyter notebooks for experimentation
├── requirements.txt # Dependency list
└── README.md # Project documentation


---

## 🧪 Research Citation

If you use this code, please cite:

@article{sheriff2025NST,
title={Enhanced Neural Style Transfer using VGG-19 and Gram Matrix Computation},
authors={Nawaz Sheriff K.N , Mahesh Bala B, Rogit S},
journal={FMDB Transactions on Sustainable Computing Systems},
year={2025}
}


---

## 🤝 Contributing

Pull requests are welcome. For significant changes, open an issue first to discuss your ideas.  
Ensure any updates are thoroughly documented.


## 💬 Contact

For academic inquiries or collaboration opportunities, please contact:  
**nawazsheriffkn@gmail.com**

---

> _Crafted with precision and science — merging the aesthetics of art with the logic of AI._
