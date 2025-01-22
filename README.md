# Stack Overflow Question Tag Prediction

This repository contains a multi-class classification project aimed at predicting the programming language tag (Python, C#, JavaScript, or Java) of Stack Overflow questions based on their text content. This project uses TensorFlow and Keras to preprocess data, build a neural network, and evaluate the model.

## Dataset
The dataset comprises thousands of Stack Overflow programming questions, each labeled with one tag:

Python
C#
JavaScript
Java

The dataset was preprocessed and structured before training.

## Objective
To create a multi-class classifier that takes a programming question as input and predicts the correct programming language tag.

## Key Features

### Data Preprocessing:

Text tokenization and vectorization for model input.
Train-validation-test split to evaluate model performance.

### Model Architecture:

Built using the TensorFlow Keras Sequential API.
Includes an Embedding layer and fully connected Dense layers.
Final Dense layer outputs probabilities for 4 classes.

### Training:

Optimized with SparseCategoricalCrossentropy loss function.
Accuracy metric used for evaluation.

### Evaluation:

Model tested on a separate dataset to validate performance.

### Regularization:

Added dropout layers and L2 regularization to prevent overfitting
