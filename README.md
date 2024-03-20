# Practice Lab: Neural Networks for Handwritten Digit Recognition, Multiclass
ASSIGNMENT 2 - QUESTION

## Intro

***Github Link*** : [https://github.com/Qmumu/ml_lab2](https://github.com/Qmumu/ml_lab2)
  
***Medium Link*** : [https://medium.com/@751153214/practice-lab2-neural-networks-for-handwritten-digit-recognition-multiclass-407a77327d7e](https://medium.com/@751153214/practice-lab2-neural-networks-for-handwritten-digit-recognition-multiclass-407a77327d7e)



This repository contains a practice lab focused on using neural networks to recognize handwritten digits (0-9) using TensorFlow. Through this exercise, you will gain a practical understanding of how to construct and train a neural network for a multiclass classification problem.

## Outline

- [1 - Packages](#1-packages)
- [2 - ReLU Activation](#2-relu-activation)
- [3 - Softmax Function](#3-softmax-function)
  - [Exercise 1](#exercise-1)
- [4 - Neural Networks](#4-neural-networks)
  - [4.1 Problem Statement](#41-problem-statement)
  - [4.2 Dataset](#42-dataset)
  - [4.3 Model Representation](#43-model-representation)
  - [4.4 TensorFlow Model Implementation](#44-tensorflow-model-implementation)
  - [4.5 Softmax Placement](#45-softmax-placement)
    - [Exercise 2](#exercise-2)

## 1 Packages

This lab requires the following Python packages:
- NumPy: A library for numerical computations.
- TensorFlow: An open-source machine learning framework.
- Matplotlib (optional): A library for plotting and visualization.

## 2 ReLU Activation

Discussion on the Rectified Linear Unit (ReLU) activation function and its importance in neural networks.

## 3 Softmax Function

Introduction to the softmax function, its role in multiclass classification, and a guided exercise to implement the softmax function from scratch.

### Exercise 1

Implement the softmax function in Python using NumPy.

## 4 Neural Networks

### 4.1 Problem Statement

The objective is to build a neural network model that can accurately recognize handwritten digits from 0 to 9.

### 4.2 Dataset

The dataset used in this lab is the MNIST dataset, which consists of 28x28 grayscale images of handwritten digits.

### 4.3 Model Representation

Description of the neural network architecture, including the input layer, hidden layers, and the output layer.

### 4.4 TensorFlow Model Implementation

Step-by-step guide to implementing the neural network model in TensorFlow, including model compilation and training.

### 4.5 Softmax Placement

Explanation of the numerical stability improvement by grouping the softmax function with the loss function during model training, and implications for model building and usage.

#### Exercise 2

Construct a three-layer neural network using the Keras Sequential model and Dense layers with ReLU activation for the hidden layers.

---

Feel free to clone this repository and follow along with the exercises to get hands-on experience with neural network-based handwritten digit recognition.
