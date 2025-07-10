# 🐶🐱 Dogs vs Cats Classification using CNN (VGG16 + Transfer Learning)

This project implements a deep learning classifier to distinguish between dog and cat images using **Convolutional Neural Networks (CNNs)**. It uses the popular **VGG16** architecture for **transfer learning**, along with **data augmentation**, **dropout**, and **batch normalization** to improve generalization and training stability.

---

## 📂 Dataset

- **Source**: [Kaggle - Dogs vs. Cats](https://www.kaggle.com/datasets/salader/dogs-vs-cats)
- **Total Samples**: 25,000 images
- **Labels**: `dog` and `cat`
- **Format**: JPEG

---

## 🧠 Model Features

### ✅ Transfer Learning (VGG16)
- Pre-trained on ImageNet
- `include_top=False` (custom classifier added on top)
- Frozen base layers, fine-tuned top layers

### ✅ Data Augmentation
- Horizontal flip
- Rotation
- Zoom
- Width/height shift
- Rescale (Normalization)

### ✅ Regularization
- **Dropout**: Prevents overfitting
- **Batch Normalization**: Stabilizes training and accelerates convergence

---

## ⚙️ Dependencies

```txt
ipykernel
tensorflow==2.19.0
matplotlib
opencv-contrib-python
Pillow==10.2.0
scipy

