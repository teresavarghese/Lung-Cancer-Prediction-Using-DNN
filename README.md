# Lung-Cancer-Prediction-Using-DNN

This repository contains a Python script for predicting lung cancer using a deep learning model implemented with Keras, a high-level neural networks API. The model analyzes a dataset containing various health indicators and demographic information to predict the likelihood of an individual having lung cancer.

## Model Architecture

The script preprocesses the dataset, encodes categorical variables, separates features from the target variable, and splits the dataset into training and testing sets. The deep learning model architecture consists of fully connected (Dense) layers with ReLU activation functions, followed by a sigmoid output layer. The model is trained using the Adam optimizer and binary cross-entropy loss function.

## Code Overview

The Python script utilizes Keras to build and train the deep learning model. Here's a summary:

- **Data Preprocessing:** Encodes categorical variables and separates features from the target variable.
- **Model Building:** Defines a deep learning model with Dense layers using Keras's Sequential API.
- **Model Training:** Trains the model on the training data for a specified number of epochs.
- **Model Evaluation:** Evaluates the trained model's performance on the test data and calculates the overall confidence average of its predictions.

## Dependencies

- Python 3
- pandas
- numpy
- matplotlib
- scikit-learn
- keras
