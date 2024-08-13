# Oral Cancer Image Classification Project

## Project Description

This project focuses on developing and evaluating deep learning models for classifying oral cancer images. The dataset consists of high-resolution images categorized into two classes: Normal and Oral Squamous Cell Carcinoma (OSCC). The primary objective is to leverage various convolutional neural networks (CNNs) to accurately distinguish between these classes, aiding in the early detection of oral cancer.

## Models Utilized

The models used in this project include VGG16, ResNet50, LeNet-5, MobileNetV2, and Inception V3. Each model was fine-tuned and trained on the provided dataset to evaluate their performance. The selection of these models was based on their architecture complexity and suitability for medical image classification tasks.

## Performance Summary

The models were assessed on accuracy, precision, recall, and F1-score. Notably, MobileNetV2 achieved the highest accuracy at 95.41%, with a strong balance across precision and recall. In contrast, Inception V3 showed limitations with an accuracy of 51.86%, despite achieving a recall close to 99.21%, indicating its tendency to identify positive cases at the expense of more false positives.

## Conclusion

This project demonstrates the effectiveness of CNNs in medical image classification, with MobileNetV2 showing the most promise for real-world applications. Future work could explore model optimization and deployment on resource-constrained devices for faster, more accessible diagnostics in clinical settings.

## Installation
```bash
pip install -r requirements.txt

Oral cancer Comparative Study:	

Detection of Normal or OSCC cells 

Comparing various Models VGG16,ResNet-50,LeNet-5,MobileNetV2 and Inception V3.

Dataset Availability:
Original Dataset
Link: https://data.mendeley.com/datasets/ftmp4cvtmb/1
