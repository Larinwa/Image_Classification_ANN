# Image Classification on MNIST Using Artificial Neural Network (ANN)

## Overview
This project uses a fully connected Artificial Neural Network built with PyTorch to classify handwritten digits (0–9) from the MNIST dataset. 
It demonstrates key steps in data preprocessing, model training, and performance evaluation.

## Implementation Summary
- Dataset: MNIST (60,000 train, 10,000 test images)
- Model: Feedforward ANN with ReLU activations and CrossEntropy loss
- Optimizer: Stochastic Gradient Descent (learning rate = 0.0001)
- Epochs: 5

## Results
- Training Loss: Decreased steadily across epochs  
- Test Accuracy: ~96%  
- F1 Score: 0.96

The model achieved strong generalization, accurately distinguishing digits with minimal overfitting.

## Key Insight
A simple ANN can perform remarkably well on MNIST when properly normalized and tuned, demonstrating the power of basic neural architectures for image classification.

## Tools
PyTorch, Torchvision, NumPy, Matplotlib, Scikit-learn
