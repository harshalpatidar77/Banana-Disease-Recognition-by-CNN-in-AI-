## Project Title
Banana Disease Recognition using Convolutional Neural Networks (CNN)

## Overview
This project is a deep learning-based image classification system designed to detect diseases in banana plants using CNN. The model identifies healthy and infected banana leaves using image data sourced from Kaggle.

## Objective
To help farmers and agricultural systems detect banana plant diseases early using AI-based image classification.

## Dataset
* Source: Kaggle(not uploaded due to large size)
* link: https://www.kaggle.com/datasets/sujaykapadnis/banana-disease-recognition-dataset/data 
* Type: Plant leaf image dataset
* Classes: Healthy leaves + multiple disease categories

##  Technologies Used
* Python
* TensorFlow / Keras
* NumPy
* Pandas
* Matplotlib

## Model Architecture
* Convolutional Neural Network (CNN)
* Feature extraction using convolution layers
* Pooling layers for dimension reduction
* Fully connected dense layers
* Softmax activation for multi-class classification
  
## Workflow
* Dataset collection from Kaggle
* Image preprocessing (resizing, normalization)
* Data augmentation
* CNN model training
* Model evaluation 

## Evaluation Metrics
* Accuracy
* Loss
* Confusion Matrix
* Classification Report

## Results
* Model effectively detects banana leaf diseases
* High performance in distinguishing healthy vs infected leaves

##  Future Improvements 
* Deploy model in mobile app for farmers
* Improve accuracy using Transfer Learning (MobileNet / ResNet)
* Integrate real-time image capture system
