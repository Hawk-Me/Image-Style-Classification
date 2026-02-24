# 🎨 Image Style Classification

A deep learning project that classifies images as either **Stylized (Cartoon/Anime)** or **Real-World Photographs**.

This project demonstrates practical computer vision skills including dataset preparation, data augmentation, duplicate removal, model training, and performance evaluation.

---

## 📌 Overview

The objective of this project is to build a binary image classification model capable of distinguishing between:

- **Stylized images** (cartoon, anime, illustrated content)
- **Real-world photographs**

The model learns domain-level visual differences such as texture patterns, color distributions, edge sharpness, and structural composition.

---

## 📊 Dataset

- Total Images: **1228**
- Real Images: **535**
- Cartoon Images: **693**
- Image Size: **224x224**

### Dataset Processing

- All images resized to 224x224 resolution
- Pixel-based duplicate images removed
- Training data enhanced using augmentation techniques
- Balanced validation strategy applied

---

## 🔄 Data Augmentation

To improve generalization and reduce overfitting, the following techniques were applied:

- Horizontal Flip
- Rotation
- Brightness Adjustment
- Zoom Transformation

A custom web-based augmentation tool was developed to streamline dataset expansion.

---

## 🧠 Model Description

A Convolutional Neural Network (CNN) was used to perform binary classification between stylized and real images.

The model learns high-level visual features that differentiate artistic renderings from natural photographic content.

---

## 🚀 Applications

This model can be extended for:

- Content moderation systems
- Dataset cleaning pipelines
- Preprocessing filters for generative AI models
- Style-domain detection systems
- Media classification tools

---

## 🔮 Future Improvements

- Transfer learning integration (e.g., MobileNet / EfficientNet)
- Web-based real-time inference demo
- Similarity-based image filtering (perceptual hashing)
- Larger and more diverse dataset
- Multi-class style classification

---

## 💼 Author

Developed by Hawk Development

---