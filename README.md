
# PointNet from Scratch in PyTorch (Google Colab)

This project is a clean **from-scratch implementation of the PointNet architecture** for 3D point cloud classification using **PyTorch**.

The work has been entirely done and tested on **Google Colab**, allowing for easy replication and GPU acceleration without local setup.

---

## 🚀 Project Overview

- Implemented **PointNet** as described in the original paper:
  > [PointNet: Deep Learning on Point Sets for 3D Classification and Segmentation](https://arxiv.org/abs/1612.00593)
  
- Built the architecture **modularly** with separate blocks:
  - Input Transform Network (T-Net)
  - Feature Transform Network (T-Net)
  - Shared MLP layers
  - Global feature extraction (Max pooling)
  - Classification head

- Trained and evaluated on the **ModelNet40 dataset**, fully inside **Google Colab**.

---
## 🖼️ PointNet Architecture

![PointNet Architecture](https://raw.githubusercontent.com/charlesq34/pointnet/master/doc/pointnet_architecture.png)
## 🔧 Technologies Used

- Python 3.x
- PyTorch
- NumPy
- Matplotlib (for point cloud visualization)
- Open3D (optional, for better visualization)
- Google Colab environment (with GPU)

---

## 📦 Dataset

- **ModelNet40**
  - Public 3D CAD dataset of 40 categories.
  - Preprocessed
