🖼️ Small Image Classification Using Convolutional Neural Networks (CNN)
📌 Project Overview

This repository presents a combined mini deep learning project demonstrating three different CNN-based approaches for small image classification:

Basic CNN on CIFAR dataset

CNN with Data Augmentation

CNN using Transfer Learning

The objective is to showcase the evolution of image classification techniques, starting from a custom CNN model and progressing toward more advanced methods to improve performance and generalization.

🧠 Problem Statement

Traditional machine learning methods struggle with image data due to the need for manual feature extraction.
This project addresses the challenge by using Convolutional Neural Networks (CNNs), which automatically learn spatial features and hierarchies directly from raw images.

The project also explores how data augmentation and transfer learning can significantly enhance model accuracy and robustness.

🚀 Project Components
1️⃣ CNN on CIFAR Dataset

Implemented a custom CNN architecture

Trained and evaluated on a small image dataset (CIFAR-like)

Established a baseline model for comparison

📓 Notebook:

cnn_cifar.ipynb

2️⃣ CNN with Data Augmentation

Applied image augmentation techniques such as:

Rotation

Zoom

Horizontal flipping

Reduced overfitting

Improved generalization on unseen data

📓 Notebook:

cnn_flower_image_data_augmentations.ipynb

3️⃣ CNN with Transfer Learning

Used a pre-trained CNN model (e.g., VGG / ResNet)

Leveraged learned features from large-scale datasets

Achieved higher accuracy with faster convergence

📓 Notebook:

cnn_transfer_learning.ipynb

🛠️ Technologies Used

Python

TensorFlow / Keras

NumPy

Matplotlib

Jupyter Notebook

📂 Dataset

Small image datasets such as CIFAR-10 and flower image datasets

Images are:

Resized

Normalized

Dataset split into:

Training set

Validation set

Testing set

🏗️ Model Architecture (Generic)

Convolutional Layers

ReLU Activation

MaxPooling Layers

Fully Connected (Dense) Layers

Softmax Output Layer

📊 Results & Observations

Basic CNN provides a strong baseline

Data augmentation improves generalization

Transfer learning delivers the best performance

Progressive improvement observed across all three approaches

🎯 Learning Outcomes

Hands-on experience with CNNs

Understanding of overfitting and regularization

Practical implementation of data augmentation

Effective use of transfer learning in deep learning projects

📌 Conclusion

This combined project demonstrates a complete learning curve in deep learning for image classification, making it suitable for:

Academic submissions

Internship portfolios

Resume and interview discussions

📬 Author

Anshul Verma
B.Tech CSE (AI & ML), 3rd Year
COER University, Roorkee

