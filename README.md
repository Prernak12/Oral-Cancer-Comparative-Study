# Oral Cancer Detection Using Deep Learning Models

## Project Overview
This project focuses on developing and evaluating deep learning models to detect and classify Oral Squamous Cell Carcinoma (OSCC) using histopathological images. The goal is to create an efficient and accurate system capable of distinguishing between normal and cancerous tissue samples, thereby aiding in early diagnosis and treatment.

## Models Implemented
The project implements several convolutional neural network (CNN) architectures, each with its unique strengths and capabilities:

- *VGG16*: A widely-used CNN model known for its simplicity and effectiveness in image classification tasks.
- *ResNet50*: A deep residual network that addresses the vanishing gradient problem, making it suitable for very deep networks.
- *LeNet-5*: One of the earliest CNN architectures, adapted for this project to handle medical image classification.
- *MobileNetV2*: A lightweight model optimized for mobile and embedded applications, offering a good trade-off between performance and computational efficiency.
- *Inception V3*: A sophisticated model that utilizes inception modules to improve computation efficiency and accuracy in complex image classification tasks.

## Results Summary
After training and evaluating the models on the dataset, the following results were obtained:

- *VGG16* achieved an accuracy of 76.54%, with a precision of 74.90%, recall of 78.99%, and an F1-Score of 76.89%.
- *ResNet50* achieved an accuracy of 71.00%, with a precision of 76.12%, recall of 60.43%, and an F1-Score of 67.28%.
- *LeNet-5* achieved an accuracy of 76.56%, with a precision of 87.00%, recall of 77.00%, and an F1-Score of 81.47%.
- *MobileNetV2* achieved the highest accuracy of 95.41%, with a precision of 95.03%, recall of 89.06%, and an F1-Score of 92.08%.
- *Inception V3* demonstrated an accuracy of 51.86%, with a precision of 51.29%, recall of 99.21%, and an F1-Score of 67.62%.

## Key Insights
Among the models tested, *MobileNetV2* stood out as the most effective, achieving the highest accuracy of 95.41%, making it highly suitable for deployment in resource-constrained environments such as mobile applications. On the other hand, *Inception V3* showed a high recall rate, indicating its sensitivity to detecting cancerous tissues, though with lower precision and accuracy. *VGG16* and *LeNet-5* provided balanced performance, with *LeNet-5* achieving the highest precision among all models. *ResNet50* presented a moderate performance, balancing precision and recall.

This project demonstrates the potential of deep learning models in medical diagnostics, particularly in detecting oral cancer. The results indicate that deep learning can significantly aid in early diagnosis, contributing to better patient outcomes.

## How to Use
1. *Data Preparation*: Structure your dataset according to the model's requirements, with separate directories for each class.
2. *Training*: Use the provided scripts to train the models on your dataset. Adjust hyperparameters as necessary.
3. *Evaluation*: Evaluate model performance using a validation set to assess accuracy, precision, recall, and F1-Score.
4. *Prediction*: Use the trained model to classify new histopathological images, identifying whether they are normal or indicate OSCC.

## Dependencies
- TensorFlow
- Keras
- NumPy
- Pandas
- Scikit-learn

## Installation
```bash
pip install -r requirements.txt

Oral cancer Comparative Study:	

Detection of Normal or OSCC cells 

Comparing various Models VGG16,ResNet-50,LeNet-5,MobileNetV2 and Inception V3.

Dataset Availability:
Original Dataset
Link: https://data.mendeley.com/datasets/ftmp4cvtmb/1
