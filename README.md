# 🧠 Neural Network for Handwritten Digits Classification

This repository contains a neural network implementation for classifying handwritten digits (0–9) using the **MNIST** dataset. The model is built using **TensorFlow** and **Keras**, trained on grayscale images of handwritten digits, and evaluated for performance using accuracy and loss metrics.

---

## 🖼️ Dataset

We use the **MNIST** dataset:
- 60,000 training images
- 10,000 test images
- Each image is 28x28 pixels in grayscale
- Labels range from 0 to 9 (digits)

The dataset is loaded directly from `tensorflow.keras.datasets`.

---

## 🏗️ Model Architecture

- **Input Layer:** 784 nodes (flattened 28x28 image)
- **Hidden Layers:**
  - Dense layer with 128 neurons + ReLU activation
  - Dropout for regularization
- **Output Layer:** Dense layer with 10 neurons (one per digit) + Softmax activation

---

## 🚀 Getting Started

### 🔧 Requirements

Make sure you have the following Python libraries installed:

```bash
pip install tensorflow matplotlib numpy
