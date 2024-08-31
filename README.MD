# MNIST Classification with NumPy

This repository contains implementations of three different machine learning models to classify the MNIST dataset using only NumPy.

## Models Implemented

1. **Logistic Regression**
   - A linear model that predicts the probability of an input belonging to a particular class.

2. **Softmax Regression**
   - A generalization of logistic regression that handles multiple classes by assigning probabilities to each class.

3. **Multi-Layer Perceptron (MLP)**
   - A simple neural network with one or more hidden layers that can capture non-linear relationships in the data.

## Dataset

The MNIST dataset consists of 70,000 images of handwritten digits (0-9), each 28x28 pixels in size. The dataset is split into 60,000 training images and 10,000 test images.

- **Training set**: 60,000 images
- **Test set**: 10,000 images

## Requirements

- Python 3.x
- NumPy

You can install the required packages using:

```bash
pip install -r requirements.txt
