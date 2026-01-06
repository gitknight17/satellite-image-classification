# Satellite Image Classification using CNNs and Transfer Learning

This project implements a deep learning–based satellite image classification system using convolutional neural networks (CNNs) and transfer learning to classify land-use categories from satellite imagery.

---

## Project Overview

Satellite image classification plays an important role in remote sensing applications such as land-use analysis and environmental monitoring.  
This project evaluates multiple CNN architectures to understand performance trade-offs between accuracy and model efficiency on satellite image data.

---

## Dataset

- RSI-CB256 satellite image dataset
- Multi-class classification task
- Classes include: desert, green area, cloudy, and water
- Images were preprocessed and split into training and validation sets

---

## Methodology

- Applied image preprocessing and normalization
- Implemented transfer learning using pre-trained CNN architectures
- Trained and evaluated the following models:
  - MobileNet
  - VGG19
  - ResNet50
  - Custom CNN
- Compared model performance using test accuracy and loss

---

## Results and Analysis

- MobileNet achieved the highest test accuracy (~99%)
- Custom CNN achieved competitive performance (~90%)
- VGG19 achieved moderate performance (~86%)
- ResNet50 underperformed on this dataset compared to other architectures

The results highlight the effectiveness of lightweight transfer learning models for satellite image classification tasks.

---

## Tech Stack

- Python
- TensorFlow, Keras
- NumPy
- Matplotlib
- Jupyter Notebook


