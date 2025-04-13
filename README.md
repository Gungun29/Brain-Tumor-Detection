# Brain-Tumor-Detection

## 📌 Overview

This project aims to detect and classify brain tumors using deep learning techniques on MRI images. It leverages Convolutional Neural Networks (CNNs) to accurately distinguish between different tumor types or the absence of tumors.

## 🚀 Features

- Classification of brain MRI images into:
  - **Glioma**
  - **Meningioma**
  - **Pituitary tumor**
  - **No tumor**
- Based on state-of-the-art deep learning architectures (e.g., ResNet50, VGG16, or custom CNN)

## 🧠 Dataset

The dataset used is a public brain tumor MRI dataset containing labeled images categorized into four classes.
Link: https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset/data

## 📈 Model Evaluation & Results

We evaluated three deep learning models widely used in biomedical image analysis: **CNN**, **ResNet50**, and **VGG16**. Each model was assessed using accuracy scores to determine its effectiveness in classifying different brain tumor categories.

### 🔬 Models Used
- **CNN (Convolutional Neural Network)**
- **ResNet50**
- **VGG16**

### ✅ Accuracy Scores

| Model     | Accuracy  |
|-----------|-----------|
| CNN       | 95.27%    |
| ResNet50  | **96.52%** |
| VGG16     | 95.70%    |

> These accuracy scores indicate the proportion of correctly classified instances and serve as a primary metric of model effectiveness.

Among all models, **ResNet50** yielded the highest accuracy, showcasing its strength in accurately classifying brain tumor types.

