# 🌿 Plant Disease Prediction using CNN

This project aims to build a deep learning model using Convolutional Neural Networks (CNNs) to automatically detect plant diseases from images of leaves. The goal is to aid farmers and agriculturists by providing a fast, reliable tool to identify diseases early and improve crop health through timely interventions.

---

## 🧩 Problem Statement

In agriculture, early identification of crop diseases is critical for minimizing damage and maximizing yield. Traditionally, disease diagnosis requires expert knowledge and manual inspection, which is time-consuming and often inaccessible in rural or underdeveloped regions.

This project solves the problem by automating the identification of crop diseases using a CNN-based image classifier, enabling accurate and real-time disease detection using simple leaf images.

---

## 📂 Dataset Description

- The dataset consists of **87,000+ RGB images** of healthy and diseased crop leaves.
- It is categorized into **38 different classes**, each representing a specific crop-disease combination (e.g., Apple Scab, Corn Rust, Healthy Tomato, etc.).
- The dataset is divided into:
  - **80% Training set**
  - **20% Validation set**
- A separate **test set of 33 images** was created for final evaluation and prediction.

The directory structure is preserved for class-based training, and images are preprocessed and resized to ensure consistency.

---

## 🧠 Model: CNN-Based Image Classifier

The project uses a Convolutional Neural Network (CNN), a deep learning architecture highly effective for image classification tasks. Key features:

- **Convolutional layers** extract features such as leaf patterns, colors, and shapes.
- **Pooling layers** reduce dimensionality and preserve essential patterns.
- **Dense layers** at the end classify the extracted features into one of 38 disease classes.
- **Softmax activation** is used for multi-class classification.
- Model is trained using **categorical cross-entropy** loss and **Adam optimizer**.

CNNs are chosen due to their capability to learn spatial hierarchies in image data, making them ideal for visual tasks like plant disease detection.

---

## 🧪 Results

- High classification accuracy on both training and validation sets.
- Successfully predicted diseases on new, unseen images from the test set.
- Misclassifications were analyzed and found to be minimal and mostly due to visual similarity among certain diseases.

---

## 🚀 Conclusion & Application

This CNN-based plant disease detection model can be integrated into:

- 📱 **Mobile apps** for farmers to scan leaves in real-time
- 💻 **Advisory systems** for agronomists and extension workers
- 🌾 **Agricultural decision support tools** for early warning and timely treatment

By automating disease detection, this tool helps reduce crop loss, improve productivity, and empower farmers with modern AI-driven solutions.

---

## 📌 Technologies Used

- Python
- TensorFlow / Keras
- NumPy, Matplotlib
- Jupyter Notebook
