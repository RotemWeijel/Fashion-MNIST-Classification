# Fashion-MNIST-Classification
Project completed as part of ML course at Bar-Ilan University.
This project implements neural networks for classifying handwritten digits (MNIST) and fashion items (Fashion-MNIST) using both pure NumPy and PyTorch approaches.

## Overview
The project consists of two main parts:

  1. MNIST digit classification using a custom neural network built with NumPy
  2. Fashion-MNIST classification using a CNN implemented in PyTorch

## Features

  - Custom implementation of backpropagation and gradient descent
  - Batch processing for efficient training
  - Real-time visualization of training progress
  - Model comparison tools (trained vs untrained)
  - Interactive prediction visualization

## Model Architectures
### MLP (NumPy Implementation)
  - Input Layer: 784 neurons (28x28 pixels)
  - Hidden Layer: 128 neurons with sigmoid activation
  - Output Layer: 10 neurons with softmax activation

### CNN (PyTorch Implementation)
  - 3 Convolutional layers with ReLU activation
  - Max pooling after each conv layer
  - 2 Fully connected layers
  - Dropout for regularization

## Results
  - MLP on MNIST: ~87% accuracy
  - CNN on Fashion-MNIST: ~90% accuracy
