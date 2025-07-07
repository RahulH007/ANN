# 🧠 Artificial Neural Network (ANN) Implementations

This repository contains two implementations of an **Artificial Neural Network (ANN)** for digit classification on the **MNIST dataset**:

1. **TensorFlow/Keras-based ANN** – High-level, production-ready deep learning model using the Keras API.
2. **Hardcoded ANN using NumPy** – Educational, from-scratch neural network implementation without any ML libraries.

---

## 🔍 Project Overview

This project demonstrates how ANNs work by comparing a high-level implementation with a raw, manual one. Both models are trained on the [MNIST dataset](https://en.wikipedia.org/wiki/MNIST_database), which contains 28x28 grayscale images of handwritten digits (0–9).

---

### ✅ Keras-Based ANN
- Uses `tensorflow.keras`
- 1 hidden layer (customizable)
- `ReLU` and `Softmax` activations
- Optimized using `SGD` or `Adam`
- Easily extensible with dropout, additional layers, etc.

### ✅ Hardcoded ANN (NumPy)
- Built fully from scratch (no ML frameworks)
- 1 hidden layer with `ReLU`
- Forward pass, backpropagation, and weight updates manually implemented
- Uses `softmax` + `cross-entropy` loss
- Great for learning and educational purposes

---

## 📊 Accuracy

| Model           | Accuracy (Test) |
|----------------|------------------|
| Keras ANN      | ~97%             |
| NumPy ANN      | ~92%             |

> *Note: Results may vary slightly depending on hyperparameters and training time.*
