# Sigmoid activation function

The sigmoid activation function is a popular non-linear activation function used in artificial neural networks and other machine learning models. It is characterized by its S-shaped curve and maps the input values to a range between 0 and 1, making it suitable for binary classification tasks and problems where the output needs to be interpreted as a probability.

Function:

* $f(x) = 1 / (1 + exp(-x))$

* $x$ is the input to the neuron.

* $f(x)$ is the output of the neuron after applying the sigmoid activation function.

**Key aspects:**

Non-Linearity: The sigmoid function is non-linear, introducing non-linearity into the neural network. This non-linearity is essential for the network to learn and approximate complex, nonlinear relationships in the data.

Output Range: The output of the sigmoid function always lies between 0 and 1. This makes it useful for binary classification tasks, where the output represents the probability of the positive class.

Vanishing Gradient Problem: For very large positive or negative input values, the gradient of the sigmoid function approaches zero. This can lead to slow convergence and difficulty in training.

Symmetry: The sigmoid function is symmetric around the origin (0, 0.5), meaning that it maps both positive and negative inputs close to 0.5.

The sigmoid activation function was widely used in the past. For hidden layers in deep neural networks, the ReLU (Rectified Linear Unit) activation function and its variants (Leaky ReLU, Parametric ReLU, ELU) are commonly preferred.