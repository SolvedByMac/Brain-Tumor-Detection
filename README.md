# Brain-Tumor-Detection
This project focuses on the development and optimization of a deep learning model designed for highly accurate brain tumor detection in Magnetic Resonance Imaging (MRI) scans.


# Project goal:

The objective of this project is to develop a deep learning model capable of detecting and classifying brain tumors from MRI images. This is primarly to assist healthcare professionals in diagnosing brain tumors accurately and quickly.


## The focus of the project:

This project focuses on classifying brain MRI images into four distinct categories: No Tumor, Glioma, Meningioma, and Pituitary Tumor. To address this multi-class classification task effectively, I utilized Convolutional Neural Networks (CNNs) along with transfer learning from pre-trained deep learning models.

To improve the explainability of the model, I applied Grad-CAM (Gradient-weighted Class Activation Mapping) to visualize the specific regions of each MRI scan that the model attends to during prediction. This helps highlight the decision-making process behind each classification.

The training data was sourced from the publicly available Brain Tumor MRI Dataset on Kaggle, which has labeled MRI images suited for medical image analysis.

