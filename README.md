# Monkeypox Detection Using Computer Vision in Python

This project implements a computer vision-based approach to detect Monkeypox skin lesions using transfer learning with the MobileNetV2 model. The dataset includes images of Monkeypox, Chickenpox, and Measles lesions. The goal is to classify images into two categories: 'Monkeypox' and 'Others.'

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Results](#results)
- [References](#references)

## Overview
Monkeypox is a contagious viral disease that presents with skin lesions. Early detection is critical to prevent outbreaks. This project leverages deep learning and transfer learning techniques to classify skin lesion images efficiently.

## Dataset
The project uses the **Monkeypox Skin Lesion Dataset** from Kaggle. The dataset is divided into:
- **Training Set**: 70%
- **Validation Set**: 10%
- **Test Set**: 20%

The dataset includes:
- **Monkeypox**
- **Others** (Chickenpox and Measles)

Augmented images are also included to improve model performance.

## Model Architecture
The project uses **MobileNetV2** for transfer learning. The model is fine-tuned on the dataset to classify images into the target categories. Key features include:
- Pre-trained MobileNetV2 backbone
- Class-weighted loss function to handle class imbalance
- Evaluation on training, validation, and test sets

## Results
- **Accuracy**: Achieved high accuracy on the test set.
- **Confusion Matrix**: Demonstrates the classification performance for each class.
- **Precision, Recall, F1-Score**: Evaluated to ensure robust model performance.

## References
- [Monkeypox Skin Lesion Dataset on Kaggle](https://www.kaggle.com)
- [MobileNetV2 Paper](https://arxiv.org/abs/1801.04381)
- [WisdomML: Monkeypox Detection Using Computer Vision](https://wisdomml.in/monkeypox-detection-using-computer-vision-in-python/)

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

