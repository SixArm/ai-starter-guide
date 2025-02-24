# Hyperbolic tangent activation function

The hyperbolic tangent activation function, often abbreviated as tanh, is a non-linear activation function widely used in artificial neural networks. It is similar to the sigmoid activation function but has a range between -1 and 1, making it a zero-centered function.

Formula:

* $\tanh x = \frac{\sinh x}{\cosh x} = \frac {e^x - e^{-x}} {e^x + e^{-x}}
= \frac{e^{2x} - 1} {e^{2x} + 1}$

* $x$ is the input to the neuron.

* $e$ is the base of the natural logarithm, approximately equal to 2.71828.

**Key aspects:**

Range: The tanh function maps the input to a range between -1 and 1. This means that negative inputs will be mapped close to -1, zero inputs to 0, and positive inputs to values close to 1.

Zero-Centered: Unlike the sigmoid function, the tanh function is zero-centered, which means its output has a mean value of zero. This property can help in mitigating certain issues related to gradients during training, as it reduces the impact of vanishing gradients.

Non-Linearity: The tanh function introduces non-linearity into the neural network, enabling it to learn and model complex, non-linear relationships in the data.

Symmetry: The tanh function is symmetric around the origin (0, 0), meaning that it maps both positive and negative inputs close to 0.
