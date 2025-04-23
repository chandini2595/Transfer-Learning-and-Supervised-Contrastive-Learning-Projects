# 🔍 Transfer Learning and Supervised Contrastive Learning Projects

This repository contains a comprehensive set of Colab notebooks demonstrating:
- Supervised contrastive learning vs. traditional softmax classification
- Transfer learning on images, videos, and audio (as both feature extractor & fine-tuning)
- Zero-shot transfer learning with CLIP and BiT models
- State-of-the-art vision classifiers on MNIST, Fashion MNIST, and CIFAR-10
- Medical imaging classification (X-ray pneumonia, 3D CT scans)

---

## 📚 Part 1: Supervised Contrastive Learning vs. Softmax Classification

### 🔗 Colab Notebook
- [Part 1 - SupCon vs. Softmax](https://colab.research.google.com/drive/1LCbBT_IEyWXrlhcB0HclsCHYfO2mzKYB)

### 📌 Description
- Implements classification using:
  - Softmax Cross Entropy Loss
  - Supervised Contrastive Loss (SupCon)
- Includes side-by-side training metrics and embedding visualizations (e.g., t-SNE)

---

## 🎛️ Part 2: Transfer Learning Across Modalities

### 🔗 Colab Notebooks
- [Colab1](https://colab.research.google.com/drive/1Id1q8epAt9t1y3CJdWm-TcZG3HTDhHRZ)
- [Colab2](https://colab.research.google.com/drive/1WsVjF70vKoA5bTfzy9YYU5Mw3v6IuhzY)

### 🧠 Use Cases
- Classification via transfer learning using pretrained models on:
  - **Images** (Dog breeds, Cats vs Dogs)
  - **Videos** (Action recognition)
  - **Audio** (Sound classification)

---

## 🧠 Part 3: Zero-Shot and SOTA Transfer Learning

### 🔗 Colab Notebooks
- [CLIP - Zero Shot](https://colab.research.google.com/drive/1WsVjF70vKoA5bTfzy9YYU5Mw3v6IuhzY?usp=sharing)
- [TFHub BigTransfer (BiT)](https://colab.research.google.com/drive/1y1KbyB6P6oKZVTvstCSiP8baijaafEkx)

### 💡 Highlights
- **CLIP**: OpenAI’s zero-shot model for vision-language tasks
- **BiT**: Scalable image classification with minimal fine-tuning


---

## 🖼️ Part 4: Vision Classifiers on Standard Datasets

### 📁 Datasets
- MNIST
- Fashion MNIST
- CIFAR-10

### 📦 EfficientNet and BiT Models using
- [MNIST Colab](https://colab.research.google.com/drive/1-mb5gsS8Tde5MG0S1fjfYsOKHjYGZCD6)
- [Fashion MNIST Colab](https://colab.research.google.com/drive/1Q3sZFv6-uRUCxVnBNov36-M64gfUmIQK)
- [CIFAR-10 Colab](https://colab.research.google.com/drive/1_K6l_7pRy7UNoYwFdXDWaeYnqB3Pp3i2)

### 🚀 SOTA Models
- [ConvNeXt V2 Colab](https://colab.research.google.com/drive/1DUxaC8MgQ1XH1RCI6fRLMoVywXpa8ZxY)
- [MLP-Mixer Colab](https://colab.research.google.com/drive/1RXfvVg6csyRDRbrFZ4-umZb-DS3RUzY5?usp=sharing)

---

## 🏥 Part 5: Medical Imaging - X-ray & 3D CT Scan

### 🧬 Use Cases
- **X-ray Pneumonia Detection**
  - [Colab](https://colab.research.google.com/drive/1y1KbyB6P6oKZVTvstCSiP8baijaafEkx)
- **3D CT Scan Classification**
  - [Colab](https://colab.research.google.com/drive/16NzVu4kqjJ0CGUtLBeD54ew9Uje9GgW2)


---

## 🧭 Summary

| Part | Topic | Description |
|------|-------|-------------|
| Part 1 | SupCon vs Softmax | Supervised contrastive learning implementation |
| Part 2 | Transfer Learning | Across image, video, and audio domains |
| Part 3 | Zero-Shot / SOTA | CLIP + BiT models for robust inference |
| Part 4 | Vision Classifiers | MNIST, Fashion MNIST, CIFAR-10 + SOTA models |
| Part 5 | Medical Imaging | Pneumonia X-rays & 3D CT scans |

---

**📌 Note**: All notebooks are written in Google Colab using TensorFlow/Keras and TensorFlow Hub APIs. Visualizations, metrics, and model summaries are included for clarity.

## 🎥 YouTube Walkthrough / Demo

Watch the complete demo and walkthrough of all parts on YouTube:  
[![Watch on YouTube]](https://www.youtube.com/watch?v=YOUR_VIDEO_ID)



