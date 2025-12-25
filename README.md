# 🖼️ Small Image Classification Using Convolutional Neural Networks (CNN)

## 📌 Project Overview
This repository contains a combined mini deep learning project that demonstrates three different Convolutional Neural Network (CNN) approaches for small image classification:

1. Basic CNN on CIFAR dataset  
2. CNN with Data Augmentation  
3. CNN using Transfer Learning  

The project highlights the progression from a simple CNN model to more advanced techniques that improve accuracy and generalization.

---

## 🧠 Problem Statement
Traditional machine learning methods require manual feature extraction and do not perform well on image data.  
This project solves the problem using Convolutional Neural Networks (CNNs), which automatically learn spatial features directly from images.

The project further explores how data augmentation and transfer learning enhance model performance and robustness.

---

## 🚀 Project Components

### 1️⃣ CNN on CIFAR Dataset
- Custom CNN architecture built from scratch
- Trained on a small image dataset (CIFAR-like)
- Establishes a baseline model for comparison

Notebook:
- `cnn_cifar.ipynb`

---

### 2️⃣ CNN with Data Augmentation
- Image augmentation techniques applied:
  - Rotation
  - Zoom
  - Horizontal flipping
- Helps reduce overfitting
- Improves generalization on unseen data

Notebook:
- `cnn_flower_image_data_augmentations.ipynb`

---

### 3️⃣ CNN with Transfer Learning
- Uses a pre-trained CNN model (e.g., VGG / ResNet)
- Leverages learned features from large-scale datasets
- Achieves better accuracy with faster convergence

Notebook:
- `cnn_transfer_learning.ipynb`

---

## 🛠️ Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 📂 Dataset
- Small image datasets such as CIFAR-10 and flower image datasets
- Images are resized and normalized
- Dataset split into training, validation, and testing sets

---

## 🏗️ Model Architecture (Generic)
- Convolutional Layers
- ReLU Activation
- MaxPooling Layers
- Fully Connected (Dense) Layers
- Softmax Output Layer

---

## 📊 Results & Observations
- Basic CNN provides a strong baseline
- Data augmentation improves model generalization
- Transfer learning achieves the best overall performance
- Progressive improvement observed across all approaches

---

## 🎯 Learning Outcomes
- Practical understanding of CNNs
- Experience with image preprocessing and augmentation
- Knowledge of transfer learning techniques
- Ability to compare different deep learning strategies

---

## 📌 Conclusion
This combined mini project demonstrates a complete deep learning workflow for image classification and serves as a strong portfolio project for academic evaluation, internships, and interviews.

---

## 📬 Author
**Anshul Verma**  
B.Tech CSE (AI & ML), 3rd Year  
COER University, Roorkee
