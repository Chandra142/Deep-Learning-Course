# 🧠 Deep Learning Course — Professional ML Engineering Portfolio

> A comprehensive deep learning course project demonstrating proficiency in neural network architecture design, model optimization, and production-ready ML workflows.

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=flat-square&logo=python)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?style=flat-square&logo=tensorflow)](https://www.tensorflow.org/)
[![Keras](https://img.shields.io/badge/Keras-Latest-red?style=flat-square&logo=keras)](https://keras.io/)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Active%20Development-brightgreen?style=flat-square)](#-learning-progress)

---

## 📋 Project Overview

This repository contains a **complete deep learning engineering curriculum** with implementations of core ML concepts and practical applications. It demonstrates professional practices in:

- **Architecture Design**: Building scalable neural networks from first principles
- **Model Optimization**: Hyperparameter tuning, regularization, and performance metrics
- **Production Readiness**: Model serialization, evaluation pipelines, and reproducibility
- **Data Engineering**: Dataset handling, preprocessing, and augmentation workflows
- **Advanced Techniques**: CNNs, RNNs, LSTMs, GANs, Transfer Learning, and Autoencoders

---

## 🎯 Key Technical Achievements

| Area | Technologies | Status |
|------|--------------|--------|
| **Foundational ML** | TensorFlow, Computation Graphs, Tensors | ✅ Complete |
| **Neural Networks** | Keras, Dense Layers, Activation Functions | ✅ Complete |
| **Computer Vision** | CNNs, Pooling, Feature Extraction | 🟡 In Progress |
| **Advanced Models** | RNNs, LSTMs, Autoencoders, GANs | 📋 Planned |
| **Model Optimization** | Hyperparameter Tuning, Regularization | ✅ Complete |
| **Hardware Acceleration** | NVIDIA DGX A100, GPU Computing | 📋 Planned |

---

## 📁 Repository Structure

```
Deep-Learning-Course/
├── Stage1/                          # TensorFlow Fundamentals
│   ├── basic.ipynb                 # Tensor operations & computation graphs
│   ├── house_price_pred.ipynb      # Regression model implementation
│   ├── boston_house_pred.keras     # Trained model artifact
│   ├── requirements.txt            # Stage dependencies
│   └── README.md                   # Detailed stage documentation
│
├── Stage2/                          # Keras & Neural Networks
│   ├── hyperParameterTuning.ipynb  # Automated hyperparameter optimization
│   ├── image_classification.ipynb  # CNN on Intel dataset
│   ├── models/                     # Saved model checkpoints
│   ├── requirements.txt
│   └── README.md
│
├── Stage3/                          # GPU & Hardware Architecture
│   ├── dgx_architecture.md         # DGX A100 study materials
│   └── README.md
│
├── Stage4/                          # Deep CNNs
│   ├── cnn_architectures.ipynb     # Custom CNN models
│   └── README.md
│
├── Stage5/                          # Transfer Learning & Autoencoders
│   ├── autoencoders.ipynb
│   ├── pretrained_cnns.ipynb
│   └── README.md
│
├── Stage6/                          # RNNs & GANs
│   ├── lstm_sequence_modeling.ipynb
│   ├── gan_generation.ipynb
│   └── README.md
│
└── README.md                        # This file
```

---

## 🚀 Quick Start

### Prerequisites
- Python 3.8+
- pip or conda
- CUDA 11.0+ (optional, for GPU acceleration)

### Installation & Setup

```bash
# Clone repository
git clone https://github.com/Chandra142/Deep-Learning-Course.git
cd Deep-Learning-Course

# Install dependencies (choose your stage)
pip install -r Stage1/requirements.txt

# Launch Jupyter notebooks
jupyter notebook
```

### Running Key Projects

**Stage 1: House Price Prediction**
```python
# See Stage1/house_price_pred.ipynb
# Demonstrates: Regression, TensorFlow Basics, Model Training
```

**Stage 2: Image Classification with Hyperparameter Tuning**
```python
# See Stage2/hyperParameterTuning.ipynb
# Demonstrates: CNN Architecture, Keras Tuner, Grid Search
```

---

## 📚 Course Outcomes & Learning Objectives

By completing this course, I am developing expertise in:

| CO | Outcome | Evidence |
|----|---------|----------|
| **CO1** | Build & optimize deep learning models with TensorFlow | [Stage 1](Stage1/README.md) - Tensor manipulation & optimization |
| **CO2** | Understand GPU architecture (NVIDIA DGX A100) | [Stage 3](Stage3/README.md) - Hardware study |
| **CO3** | Apply CNNs for image classification at scale | [Stage 2](Stage2/README.md) & [Stage 4](Stage4/README.md) |
| **CO4** | Implement Autoencoders & Transfer Learning | [Stage 5](Stage5/README.md) - Feature extraction |
| **CO5** | Model sequential data with RNNs & LSTMs | [Stage 6](Stage6/README.md) - Time series |
| **CO6** | Deploy interactive AI apps with GANs & Streamlit | [Stage 6](Stage6/README.md) - GAN applications |

---

## 📖 Detailed Stage Breakdowns

### [Stage 1 — TensorFlow Fundamentals](Stage1/README.md)
**Status:** ✅ **Complete**

Core concepts: Tensors, Computation Graphs, Variables, Optimizers, TensorBoard

**Key Implementation:** Boston Housing Price Prediction
- Dense neural network with 4 layers
- MSE loss optimization
- Training/validation accuracy tracking
- Model serialization in Keras format

**Outputs:**
- 13-feature regression model
- Real-time TensorBoard visualization
- Model checkpoint: `boston_house_pred.keras`

**Skills Demonstrated:**
- Tensor manipulation & broadcasting
- Custom training loops with tf.GradientTape
- Model evaluation and metrics
- Gradient descent optimization

---

### [Stage 2 — Keras & Model Optimization](Stage2/README.md)
**Status:** 🟡 **In Progress**

Core concepts: Sequential Models, Dense Layers, Activation Functions, Hyperparameter Tuning

**Key Implementation:** Intel Image Classification with Keras Tuner
- Automated hyperparameter search (RandomSearch, 3 trials)
- Tunable parameters: hidden units (10-32), activation (ReLU/Tanh), dropout (0.1-0.5)
- Dataset: 25,000+ Intel images across 6 categories
- Model evaluation pipeline with metrics visualization

**Technical Highlights:**
- Data augmentation strategies
- Cross-validation setup
- Learning curve analysis
- Hyperparameter space exploration

**Skills Demonstrated:**
- High-level Keras API usage
- Automated machine learning (AutoML) with Keras Tuner
- CNN architecture design
- Performance monitoring and visualization

---

### [Stage 3 — GPU & Hardware Architecture](Stage3/README.md)
**Status:** 📋 **Planned**

Topics: NVIDIA DGX A100, GPU compute, distributed training, performance optimization

---

### [Stage 4 — Deep Convolutional Neural Networks](Stage4/README.md)
**Status:** 🟡 **In Progress**

Advanced CNN architectures, pooling strategies, receptive field analysis

---

### [Stage 5 — Transfer Learning & Autoencoders](Stage5/README.md)
**Status:** 📋 **Planned**

Feature extraction, pre-trained models (ResNet, VGG), data compression

---

### [Stage 6 — RNNs, LSTMs & GANs](Stage6/README.md)
**Status:** 📋 **Planned**

Sequential modeling, time-series forecasting, generative models, Streamlit deployment

---

## 💡 Technical Highlights & Best Practices

### Code Quality
- ✅ Modular notebook structure with clear sections
- ✅ Comprehensive comments and documentation
- ✅ Reproducible seeds for experiment replication
- ✅ Error handling and validation checks

### ML Engineering Practices
- ✅ Train/validation/test data splits
- ✅ Hyperparameter configuration tracking
- ✅ Model checkpoint management
- ✅ Performance metrics and visualization
- ✅ Requirements files for dependency management

### Scalability & Production
- ✅ Model serialization (Keras format)
- ✅ Batch processing capabilities
- ✅ TensorBoard integration for monitoring
- ✅ Documentation for reproducibility

---

## 🔗 Key Concepts Demonstrated

```
Neural Network Fundamentals
├── Tensor Operations
├── Computational Graphs
├── Backpropagation & Optimization
│
Deep Learning Architectures
├── Feed-Forward Networks
├── Convolutional Neural Networks (CNNs)
├── Recurrent Neural Networks (RNNs)
│   └── LSTM & GRU
├── Autoencoders
└── Generative Adversarial Networks (GANs)
│
Model Engineering
├── Hyperparameter Tuning
├── Regularization Techniques
├── Transfer Learning
├── Model Serialization
└── Performance Evaluation
```

---

## 📈 Progress Dashboard

```
Legend: ✅ Complete | 🟡 In Progress | 📋 Planned | 🔴 Not Started

✅ Stage 1 ████████████████████ 100% — TensorFlow Fundamentals
🟡 Stage 2 ███████████░░░░░░░░░ 55%  — Keras & Optimization
📋 Stage 3 ░░░░░░░░░░░░░░░░░░░░ 0%   — GPU Architecture
🟡 Stage 4 ███████░░░░░░░░░░░░░ 35%  — Deep CNNs
📋 Stage 5 ░░░░░░░░░░░░░░░░░░░░ 0%   — Transfer Learning
📋 Stage 6 ░░░░░░░░░░░░░░░░░░░░ 0%   — RNNs & GANs
```

---

## 📊 Performance Metrics

### Completed Models
| Project | Model Type | Best Accuracy | Loss | Status |
|---------|-----------|---------------|------|--------|
| Boston Housing | 4-Layer Dense | MSE: < 30 | Training: Converged | ✅ Complete |
| Intel Images | CNN | 85%+ | Cross-entropy: < 0.5 | 🟡 Tuning |

---

## 🛠️ Tech Stack

| Component | Technology |
|-----------|-----------|
| **Language** | Python 3.8+ |
| **ML Framework** | TensorFlow 2.x, Keras |
| **Data Processing** | NumPy, Pandas |
| **Visualization** | Matplotlib, TensorBoard |
| **Hyperparameter Tuning** | Keras Tuner |
| **GPU Computing** | CUDA, cuDNN |
| **Notebooks** | Jupyter Lab |

---

## 🎓 Prerequisites & Skills

### Required Knowledge
- Python programming fundamentals
- Linear algebra (vectors, matrices, operations)
- Calculus (derivatives, gradients, chain rule)
- Basic ML concepts (supervised/unsupervised learning)

### Technical Requirements
- Python 3.8+
- NumPy, Pandas, Matplotlib
- TensorFlow 2.x, Keras
- Jupyter Lab/Notebook
- CUDA Toolkit (optional, for GPU)

---

## 📝 Notable Implementations

### 1. **Hyperparameter Tuning Pipeline** (Stage 2)
Demonstrates industry-standard practices for automated model optimization using Keras Tuner with RandomSearch strategy.

### 2. **CNN Architecture from Scratch** (Stage 2 & 4)
Custom convolutional neural networks with pooling, dropout, and batch normalization for image classification.

### 3. **Transfer Learning Application** (Stage 5 — Planned)
Leveraging pre-trained models for feature extraction and fine-tuning on custom datasets.

### 4. **Production Model Serialization** (All Stages)
Saving and loading models in Keras format for deployment and inference.

---

## 🎓 Learning Resources Used

- TensorFlow Official Documentation
- Keras API Reference
- Research papers on CNN architectures
- NVIDIA CUDA & GPU computing guides
- Advanced ML optimization techniques
- Stanford CS231N - CNNs for Visual Recognition

---

## 📧 Contact & Portfolio

**GitHub:** [Chandra142](https://github.com/Chandra142)  
**Repository:** Deep Learning & ML Engineering Portfolio

---

## ✨ Why This Repository?

**For Recruiters:**
- 📊 Demonstrates full ML engineering pipeline
- 🔧 Production-ready code practices
- 📈 Clear progression from fundamentals to advanced topics
- 💼 Professional documentation and organization
- 🎯 Real-world projects with measurable results

**For Students:**
- 🎓 Comprehensive curriculum structure
- 📚 Detailed explanations and code comments
- 🚀 Progressive difficulty levels
- 💡 Best practices for ML development
- 🔄 Reproducible experiments

---

## ⭐ Show Your Support

If you found this repository helpful, please consider giving it a star! It helps others discover comprehensive deep learning course materials.

---

**Course Code:** INT422  
**Credits:** 3 | **Structure:** 2-0-2 (Lectures-Tutorials-Practicals)  
**Session:** 2026–27  
**Status:** ✅ Active Development  
**Last Updated:** September 2026
