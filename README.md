# MNIST Classification using Fully Connected Network

This repository contains an IPython Notebook (`DL_Number_Classification.ipynb`) where I explore different techniques for classifying the MNIST dataset using a fully connected network.

## Dataset

The MNIST dataset is a collection of handwritten digits widely used for benchmarking machine learning algorithms. It consists of 60,000 training samples and 10,000 test samples, with each image being a grayscale 28x28 pixel image of a single digit.

## Methods Explored:

The notebook showcases the exploration of various methods to improve the classification accuracy on the MNIST dataset. The following techniques are covered:

1. Regularization: Investigating the effects of regularization techniques, such as L1 and L2 regularization, to prevent overfitting and improve generalization.

2. Batch Normalization: Examining the impact of applying batch normalization to the network layers, which can help with training stability and accelerating convergence.

3. Early Stopping: Implementing early stopping to prevent overfitting by monitoring the validation loss during training and stopping when it starts to increase.

4. Activation Functions: Evaluating different activation functions, such as ReLU, sigmoid, and tanh, to observe their effects on the model's performance.

5. Network Sizes: Experimenting with different network architectures, including varying the number of hidden layers and the number of neurons in each layer, to find the optimal configuration.

6. Grid Search CV: Utilizing grid search cross-validation to systematically explore combinations of hyperparameters and identify the best set of values for improved performance.

## Results
The notebook showcases the exploration of various techniques and their impact on the classification accuracy. It presents the results in the form of visualizations and heatmaps, demonstrating the improvements obtained as different methods are explored.

