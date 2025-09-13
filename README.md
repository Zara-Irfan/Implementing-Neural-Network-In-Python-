Custom Neural Network for Insurance Prediction

This project demonstrates a lightweight neural network designed to predict whether a customer will purchase insurance based on their age and affordability. It is implemented from scratch using Python and NumPy, providing a clear understanding of the fundamentals of neural networks and gradient descent.

Overview

The model uses a simple neural network architecture with a single hidden layer and a sigmoid activation function. It predicts probabilities for binary classification, indicating the likelihood of a customer buying insurance. The network is trained using gradient descent with an adjustable learning rate and early stopping, ensuring efficient convergence.

Features

Custom Neural Network Implementation: Built from scratch without relying on heavy frameworks.

Gradient Descent Training: Optimizes model weights and bias based on the training data.

Early Stopping: Stops training when the loss reaches a defined threshold to prevent overfitting.

Single and Batch Predictions: Supports predictions for individual customers as well as entire datasets.

Probability Output: Returns the likelihood of a positive outcome, suitable for classification tasks.

Use Cases

This neural network can be used for:

Predicting customer decisions in insurance and financial domains.

Educational purposes to understand neural network internals.

Demonstrating basic concepts of gradient descent and activation functions.

Key Benefits

Lightweight and easy to understand.

Flexible with adjustable epochs and loss threshold.

Scalable for small to medium datasets.

Provides interpretable model parameters, such as weights and bias.

Notes

Proper scaling of input features is important for efficient training.

Early stopping ensures that the model reaches the target loss without unnecessary iterations.

This project is ideal for learning the core concepts of machine learning and neural networks from scratch.

License

This project is licensed under the MIT License.
