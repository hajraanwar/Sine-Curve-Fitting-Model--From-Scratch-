# Neural Network from Scratch

This repository contains a simple neural network implementation developed from scratch using only NumPy. The neural network is designed to learn and predict a sine curve. It serves as an educational project to understand the fundamentals of neural networks and backpropagation.

## Overview

The neural network is implemented for two scenarios:

1. **Case 1:** When there is one input corresponding to one output, e.g., `y = sin(x)`.
2. **Case 2:** When there are multiple inputs and one corresponding output.

For both cases, the neural network architecture includes an input layer, a hidden layer, and an output layer. The activation function used is the sigmoid function, and the mean squared error loss function is employed for training.

## Files

- **`neural_network_case1.py`:** Implementation for Case 1 with a sine curve example.
- **`neural_network_case2.py`:** Implementation for Case 2 with a dataset split into training and testing sets.

## Dependencies

- NumPy
- scikit-learn (for dataset splitting in Case 2)
- Matplotlib (for visualization)

## Results
The results include training the neural network, evaluating its performance on testing data, and visualizing the predicted values against the target values and the original sine curve.

## Performance Metrics
Mean Squared Error (MSE) and R-squared (R2) scores are calculated and printed for evaluating the performance of the neural network on the testing set.

## Note
This project was developed entirely from scratch using only the NumPy library. For a more comprehensive implementation using popular deep learning libraries, check out [https://github.com/hajraanwar/Sine-Curve-Fitting-NN-Model--Using-Libraries-/edit/main/README.md].

Feel free to explore and experiment with the code. If you find any issues or have suggestions for improvements, please open an issue.

Happy learning and coding!
