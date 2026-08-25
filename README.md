# 🧠 INT422 — Deep Learning

**Course Code:** INT422  
**Course:** Deep Learning  
**Session:** 2026–27  
**Credits:** 3  
**L-T-P:** 2-0-2  

This repository contains my **notes, implementations, practicals, experiments, and projects** for the **INT422: Deep Learning** course.

The main goal of this repository is to learn Deep Learning concepts from fundamentals and implement them practically using **TensorFlow, Keras, CNNs, Autoencoders, RNNs, LSTMs, GANs, Docker, and Streamlit**.

---

## 📊 My Learning Progress

| Stage | Topic | Status |
|------|-------|--------|
| Stage 1 | Building Models with TensorFlow | 🟡 In Progress |
| Stage 2 | Building Models with Keras | 🟡 In Progress |
| Stage 3 | NVIDIA DGX Station A100 | 🔴 Not Started |
| Stage 4 | Deep Convolutional Neural Networks | 🔴 Not Started |
| Stage 5 | Autoencoders & Pre-trained CNNs | 🔴 Not Started |
| Stage 6 | RNNs & GANs | 🔴 Not Started |

### Legend

- 🟢 Completed
- 🟡 In Progress
- 🔴 Not Started

---

# 🎯 Course Outcomes

By completing this course, I aim to:

- **CO1:** Understand TensorFlow to build and optimize Deep Learning models.
- **CO2:** Understand the hardware and software architecture of the NVIDIA DGX Station A100.
- **CO3:** Apply deep Convolutional Neural Networks (CNNs) for image classification.
- **CO4:** Apply Autoencoders and pre-trained CNNs for data compression and image processing.
- **CO5:** Examine Recurrent Neural Networks for modelling sequential data.
- **CO6:** Apply Generative Adversarial Networks (GANs) to develop interactive AI applications using Streamlit.

---

# 📚 Course Syllabus

## Stage Folders

- [Stage 1 — Building Models with TensorFlow](Stage1/README.md)
- [Stage 2 — Building Models with Keras](Stage2/README.md)
- [Stage 3 — NVIDIA DGX Station A100](Stage3/README.md)
- [Stage 4 — Deep Convolutional Neural Networks](Stage4/README.md)
- [Stage 5 — Autoencoders & Pre-trained CNNs](Stage5/README.md)
- [Stage 6 — RNNs & GANs](Stage6/README.md)

## Stage 1 — Building Models with TensorFlow

### Topics

- [x] Introduction to TensorFlow
- [x] TensorFlow Installation
- [x] TensorFlow Ranks and Tensors
- [x] TensorFlow Computation Graphs
- [x] Variables in TensorFlow
- [x] TensorFlow Optimizers
- [x] Transforming Tensors as Multidimensional Data Arrays
- [x] TensorBoard
- [x] Introduction to Deep Learning
- [x] Applications of Deep Learning

### Practical Work

- [x] TensorFlow basics
- [x] Creating and manipulating tensors
- [x] TensorFlow variables
- [x] TensorFlow optimizers
- [x] TensorBoard visualization

---

## Stage 2 — Building Models with Keras

### Topics

- [x] Introduction to Keras
- [x] Keras Installation
- [x] Keras Layers
- [x] Keras Models
- [x] Sequential Model
- [x] Dense Layer
- [x] Activation Functions
- [x] Regression Model
- [x] MSE Loss
- [x] MAE Metric
- [x] Model Training using `fit()`
- [x] Model Evaluation using `evaluate()`
- [x] Prediction using `predict()`
- [x] Saving Models
- [x] Loading Models
- [ ] Multi-layer Perceptron Classification
- [ ] Image Classification with Keras
- [ ] Text Classification
- [ ] Overfitting
- [ ] Underfitting
- [ ] Hyperparameter Tuning

### Practical Work

- [x] Regression model using Keras
- [x] Model training and evaluation
- [x] Model prediction and saving/loading
- [ ] MLP classification workflow
- [ ] Keras image/text classification experiments
- [ ] Hyperparameter tuning exercises

---

## Stage 3 — NVIDIA DGX Station A100

### Topics

- [ ] Hardware architecture of NVIDIA DGX Station A100
- [ ] Software stack and deep learning environment
- [ ] GPU acceleration and performance considerations
- [ ] AI workstation setup for large-scale model training
- [ ] Use cases of high-performance computing in deep learning

### Practical Work

- [ ] DGX architecture study
- [ ] GPU training workflow overview
- [ ] Performance and resource analysis

---

## Stage 4 — Deep Convolutional Neural Networks

### Topics

- [ ] Introduction to CNNs
- [ ] Convolution operation and receptive fields
- [ ] Pooling and feature extraction
- [ ] Filters, kernels, and activation maps
- [ ] CNN architectures for image classification
- [ ] Training and optimization of CNNs
- [ ] Evaluation of deep CNN models

### Practical Work

- [ ] Build a CNN model from scratch
- [ ] Train a CNN on image data
- [ ] Evaluate model performance
- [ ] Compare CNN performance with shallow networks

---

## Stage 5 — Autoencoders & Pre-trained CNNs

### Topics

- [ ] Autoencoders: concept and working
- [ ] Types of autoencoders
- [ ] Data compression and reconstruction
- [ ] Pre-trained CNN architectures
- [ ] Transfer learning for image tasks
- [ ] Feature extraction using pre-trained models

### Practical Work

- [ ] Implement an autoencoder
- [ ] Train and reconstruct images
- [ ] Use pre-trained CNNs for feature extraction
- [ ] Apply transfer learning on a dataset

---

## Stage 6 — RNNs & GANs

### Topics

- [ ] Recurrent Neural Networks (RNNs)
- [ ] Long Short-Term Memory (LSTM)
- [ ] Gated Recurrent Units (GRU)
- [ ] Sequence modeling and time-series data
- [ ] Generative Adversarial Networks (GANs)
- [ ] Generator and discriminator networks
- [ ] GAN applications in image generation and interactive AI

### Practical Work

- [ ] Build and train an RNN/LSTM model
- [ ] Explore sequential data modeling
- [ ] Develop a simple GAN model
- [ ] Deploy a small AI app using Streamlit

---

## 🏠 Current Project — Boston Housing Price Prediction

A regression model built using **TensorFlow/Keras** to predict house prices.

### Model Architecture

```text
Input
13 Features
    │
    ▼
Dense(20)
ReLU
    │
    ▼
Dense(15)
Tanh
    │
    ▼
Dense(10)
Sigmoid
    │
    ▼
Dense(1)
Linear
    │
    ▼
House Price Prediction