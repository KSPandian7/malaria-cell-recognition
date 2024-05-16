# Deep Neural Network for Malaria Infected Cell Recognition

## AIM

To develop a deep neural network for Malaria infected cell recognition and to analyze the performance.

## Problem Statement and Dataset
It involves achieving high accuracy in classifying malaria-infected cells versus uninfected cells to aid in the diagnosis of malaria from microscopic images. Your task would be to optimize the model, possibly by tuning hyperparameters, trying different architectures, or using techniques like transfer learning to improve classification accuracy.

![image](https://github.com/KSPandian7/malaria-cell-recognition/assets/113496887/47cd72f7-58a7-474e-a9ca-295180e3d2ba)

## Neural Network Model

![image](https://github.com/KSPandian7/malaria-cell-recognition/assets/113496887/c96c43e4-479f-45a7-b0c2-99d87d9acf0d)


## DESIGN STEPS

### STEP 1:
Import necessary libraries for data manipulation, visualization, and deep learning.
### STEP 2:
Set up TensorFlow session to dynamically allocate GPU memory and log device placement.
### STEP 3:
Define the directory paths for the dataset and inspect their contents.
### STEP 4
Load sample images from both classes (infected and uninfected) for visualization.
### STEP 5:
Explore image dimensions and distributions in the dataset using seaborn.
### STEP 6:
Define the image shape and construct a sequential model using Keras.
### STEP 7:
Add convolutional and pooling layers to the model architecture.
### STEP 8:
Flatten the layer and add dense layers with activation functions.
### STEP 9:
Compile the model specifying loss function, optimizer, and evaluation metrics.
### STEP 10:
Configure image data augmentation using ImageDataGenerator.
### STEP 11:
Set batch size and generate training and testing data batches.
### STEP 12:
Train the model on the training data for a specified number of epochs.
### STEP 13:
Evaluate the model's performance on the test data and visualize training history.
### STEP 14:
Generate predictions on the test data and calculate classification metrics.
### STEP 15:
Use random image selection for inference and display the prediction result.

## PROGRAM

### Name: KULASEKARAPANDIAN K
### Register Number: 212222240052

```python

```

## OUTPUT

### Training Loss, Validation Loss Vs Iteration Plot

Include your plot here

### Classification Report

Include Classification Report here

### Confusion Matrix

Include confusion matrix here

### New Sample Data Prediction

Include your sample cell image input and output of your model.

## RESULT
Thus, a deep neural network for Malaria infected cell recognition is developed and the performance is analyzed.
