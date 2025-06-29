# 🧠 Cross-Domain Adaptation using CNNs (DANN + EfficientNet-B0)

This project implements **Domain-Adversarial Neural Networks (DANN)** using **EfficientNet-B0** for cross-domain adaptation on the Office-31 dataset. It includes **targeted data augmentation (fog)** and **class-balanced training** for robust domain transfer learning.

---

## 📁 Dataset

- **Office-31** dataset
- Source: **Amazon**
- Target: **Webcam**
- Mounted via **Google Drive** in Colab

---

## 🚀 Features

- EfficientNet-B0 for feature extraction
- Gradient Reversal Layer (GRL) for domain adaptation
- Dense fog augmentation for realism
- Class weighting for data imbalance
- Domain + Label prediction
- Checkpoint saving after every epoch

---

## 📓 Run on Google Colab

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Vinukollu-Chandrashekar/CrossDomain/blob/main/cross_domain_adaptation.ipynb)

---

## 📂 Files

- `cross_domain_adaptation.ipynb` — Main training code
- `README.md` — Project overview and instructions

---

## 💡 Requirements

- PyTorch ≥ 1.12
- torchvision
- numpy
- Pillow
- Google Colab
