# CNN Image Classification on CIFAR-10 Dataset
This project demonstrates how to build, train, evaluate, and visualize a Convolutional Neural Network (CNN) for multi-class image classification using the CIFAR-10 dataset in TensorFlow/Keras.

# Project Overview
The goal of this project is to classify images into 10 different categories using a custom-built CNN model. The dataset used is CIFAR-10, which consists of 60,000 color images of size 32×32 distributed across 10 classes.

# Objectives
Load and preprocess the CIFAR-10 dataset <br>
Visualize sample images and their labels <br>
Build and train a CNN model <br>
Evaluate training and validation performance<br>
Predict and visualize test results with confidence scores <br>

## Dataset Details
Dataset: CIFAR-10 <br>
Total Images: 60,000  <br>
Training Images: 50,000  <br>
Testing Images: 10,000  <br>
Image Size: 32 × 32 × 3  <br>

## Sample Images
<img width="829" height="772" alt="image" src="https://github.com/user-attachments/assets/03a87398-c50f-4ce8-bd11-f4ed9e9e4f78" />

## Data Preprocessing
Steps Performed: <br>
Normalization: Pixel values scaled from [0–255] to [0–1] <br>
One-Hot Encoding: Converts class labels into 10-dimensional vectors <br>

## CNN Model Architecture
The CNN consists of:<br>
3 × Convolution layers<br>
2 × MaxPooling layers<br>
1 × Flatten layer<br>
2 × Fully Connected (Dense) layers<br1>

## Model Summary
<img width="636" height="417" alt="image" src="https://github.com/user-attachments/assets/fda1bcb9-127f-4e49-aa3c-96acfbe91848" />

## Model Training
Epochs: 13 <br>
Batch Size: 64 <br>
<img width="675" height="511" alt="image" src="https://github.com/user-attachments/assets/6fa736cd-8480-4b9d-adbe-94084dd72551" />

## Model Prediction
<img width="783" height="410" alt="image" src="https://github.com/user-attachments/assets/77f0ef76-063a-486f-b778-f75eeae78aeb" />
