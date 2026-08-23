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

| Unit | Topic | Status |
|------|-------|--------|
| Unit I | Building Models with TensorFlow | 🟡 In Progress |
| Unit II | Building Models with Keras | 🟡 In Progress |
| Unit III | NVIDIA DGX Station A100 | 🔴 Not Started |
| Unit IV | Deep Convolutional Neural Networks | 🔴 Not Started |
| Unit V | Autoencoders & Pre-trained CNNs | 🔴 Not Started |
| Unit VI | RNNs & GANs | 🔴 Not Started |

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

## Unit I — Building Models with TensorFlow

### Topics

- [ ] Introduction to TensorFlow
- [ ] TensorFlow Installation
- [ ] TensorFlow Ranks and Tensors
- [ ] TensorFlow Computation Graphs
- [ ] Variables in TensorFlow
- [ ] TensorFlow Optimizers
- [ ] Transforming Tensors as Multidimensional Data Arrays
- [ ] TensorBoard
- [ ] Introduction to Deep Learning
- [ ] Applications of Deep Learning

### Practical Work

- [ ] TensorFlow basics
- [ ] Creating and manipulating tensors
- [ ] TensorFlow variables
- [ ] TensorFlow optimizers
- [ ] TensorBoard visualization

---

# 🧩 Unit II — Building Models with Keras

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