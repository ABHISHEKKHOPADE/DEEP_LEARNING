# Deep Learning Projects

This repository contains three deep learning projects implemented using TensorFlow/Keras:

1. **Cat vs Dog Classifier**
2. **Handwritten Digit Recognition (MNIST)**
3. **Fashion MNIST Classification**

---

## 📁 Projects Overview

### 1️⃣ Cat vs Dog Classifier
**Goal:** Classify images as either "Cat" or "Dog" using Convolutional Neural Networks (CNNs).

- **Dataset:** [Kaggle Dogs vs Cats Dataset](https://www.kaggle.com/c/dogs-vs-cats/data)
- **Techniques:**
  - Image preprocessing with `ImageDataGenerator`
  - Data augmentation for better generalization
  - CNN architecture with Conv2D, MaxPooling2D, Dropout, and Dense layers
- **Results:** Achieved accuracy of ~90% on validation data.
- **Usage:**
  ```bash
  python cat_dog_classifier.py
  python mnist_digit_recognition.py
2️⃣ Handwritten Digit Recognition (MNIST)
Goal: Recognize digits (0–9) from handwritten grayscale images.

Dataset: MNIST Handwritten Digits

Techniques:

Data normalization

Simple CNN architecture

Softmax output layer for multiclass classification

Results: Achieved ~99% test accuracy.

Usage:

bash
Copy
Edit
python mnist_digit_recognition.py
3️⃣ Fashion MNIST Classification
Goal: Classify clothing items (e.g., shirts, shoes, coats) from grayscale images.

Dataset: Fashion MNIST

Techniques:

Normalization and reshaping

CNN with batch normalization and dropout

Adam optimizer with learning rate scheduling

Results: Achieved ~92% accuracy.

Usage:

bash
Copy
Edit
python fashion_mnist_classifier.py
