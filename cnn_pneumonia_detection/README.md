# Pneumonia Detection using CNN

## Overview
This project uses a Convolutional Neural Network (CNN) to classify chest X-ray images into two categories: **Normal** and **Pneumonia**.

## Dataset
- 5,863 chest X-ray images
- Total classes: Normal and Pneumonia
- Data is split into training, validation, and test sets


## Data handling and preprocessing
- Images resized and normalised
- Class weights used to handle class imbalance
- Early stopping is used during training


## Model Training
- Convolutional layers for feature extraction
- Max pooling layers for downsampling
- Dropout layers to reduce overfitting
- Dense layers for final classification
- Sigmoid activation for binary output


## Results

- Good precision, recall, and F1-score for both classes
- The model can detect pneumonia cases
Although the model performs well in identifying the correct classes, it may still show mild overfitting to the training data, which can be seen from the fluctuations in the validation loss during training. 
