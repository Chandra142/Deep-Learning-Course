# Stage 2 — Building Models with Keras

## Overview
This stage focuses on Keras, a high-level deep learning API used for building and training models efficiently.

## Topics Covered
- Introduction to Keras
- Keras installation
- Keras layers
- Keras models
- Sequential model
- Dense layer
- Activation functions
- Regression model
- MSE loss
- MAE metric
- Model training using `fit()`
- Model evaluation using `evaluate()`
- Prediction using `predict()`
- Saving and loading models
- Multi-layer perceptron classification
- Image classification with Keras
- Text classification
- Overfitting
- Underfitting
- Hyperparameter tuning

## Practical Work
- Regression model using Keras
- Model training and evaluation
- Model prediction and saving/loading
- MLP classification workflow
- Keras image classification experiment using Intel dataset
- Hyperparameter tuning exercises

## Files and Notebooks

### hyperParameterTuning.ipynb
Automated hyperparameter tuning workflow using Keras Tuner:
- **Data Generation**: Creates synthetic classification dataset (2000 samples, 15 features)
- **Model Builder**: Defines a tunable neural network with:
  - Dense layer with variable units (10-32, step=5)
  - Activation function choice (ReLU or Tanh)
  - Tunable dropout rate (0.1-0.5)
  - Binary classification output layer
- **Tuner**: Uses `RandomSearch` with 3 trials to find optimal hyperparameters
- **Optimization**: Trains best model for 30 epochs and visualizes accuracy/loss curves

## Current Progress
- [x] Downloaded Intel image dataset via `kagglehub`
- [x] Loaded training and testing image datasets
- [x] Built a CNN model architecture
- [x] Compiled model with optimizer, loss, and accuracy metric
- [x] Implemented hyperparameter tuning with Keras Tuner
  - [x] Data preprocessing and feature scaling
  - [x] Model builder function with tunable hyperparameters
  - [x] RandomSearch tuner execution
  - [x] Best model training and evaluation
  - [x] Accuracy and loss visualization
- [ ] Train the CNN model on the dataset
- [ ] Evaluate model performance
- [ ] Improve model accuracy

## Status
In Progress - Hyperparameter tuning complete, CNN training pending
