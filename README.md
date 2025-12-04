## Artificial Neural Network for Customer Churn Prediction

This project implements an Artificial Neural Network (ANN) to predict customer churn using the Churn Modelling dataset.
The workflow includes preprocessing, model training, evaluation, and saving the final model for future use.

## Project Overview

The goal is to classify whether a customer will leave the bank (churn) based on demographic and financial features.
The model is built using TensorFlow/Keras and follows a full machine-learning pipeline:

Importing and preprocessing data

Encoding categorical features

Feature scaling

Building a multi-layer ANN

Training and evaluating the model

Saving the trained network

## Model Architecture

Input layer (after preprocessing)

Dense layer: 6 units, ReLU

Dense layer: 6 units, ReLU

Output layer: 1 unit, Sigmoid
The model uses binary_crossentropy loss and the Adam optimizer.

## Evaluation

After training, the model produces:

Predictions on the test set

Confusion Matrix

Accuracy score

Visualization using ConfusionMatrixDisplay

## Saving the Model

The final trained ANN is saved in:

models/artifical_neural_networks.keras


This file can be loaded later for inference or further training.

## Requirements

Python 3.8+

TensorFlow

NumPy, Pandas

scikit-learn

Matplotlib