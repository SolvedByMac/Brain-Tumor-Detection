# Brain-Tumor-Detection
This project focuses on the development and optimization of a deep learning model designed for highly accurate brain tumor detection in Magnetic Resonance Imaging (MRI) scans.


# Project goal:

The objective of this project is to develop a deep learning model capable of detecting and classifying brain tumors from MRI images. This is primarly to assist healthcare professionals in diagnosing brain tumors accurately and quickly.


## The focus of the project:

This project focuses on classifying brain MRI images into four distinct categories: No Tumor, Glioma, Meningioma, and Pituitary Tumor. To address this multi-class classification task effectively, I utilized Convolutional Neural Networks (CNNs) along with transfer learning from pre-trained deep learning models.

To improve the explainability of the model, I applied Grad-CAM (Gradient-weighted Class Activation Mapping) to visualize the specific regions of each MRI scan that the model attends to during prediction. This helps highlight the decision-making process behind each classification.

The training data was sourced from the publicly available Brain Tumor MRI Dataset on Kaggle, which has labeled MRI images suited for medical image analysis.

## Dataset Used:

The dataset used in this project is the Brain Tumor Classification (MRI) dataset, publicly available on Kaggle:
🔗 https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri

It consists of T1-weighted contrast-enhanced MRI images classified into four categories: No Tumor, Glioma Tumor, Meningioma Tumor and Pituitary Tumor

The dataset is organized into class-specific folders, with each image stored in .jpg format. It contains thousands of high-quality MRI slices suitable for training deep learning models for medical image classification.

For this project:

* All images were resized to 224×224 pixels to match the input requirements of CNN models.

* Pixel values were normalized to a 0–1 range.


