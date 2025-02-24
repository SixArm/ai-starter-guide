# Activation function

An activation function is a mathematical function applied to the output of an artificial neural network neuron to introduce non-linearity into the model. An activation function determines whether a neuron should be activated (i.e., "fire") or not.

The activation function takes the weighted sum of inputs and biases at a neuron and transforms it into the neuron's output. Without activation functions, the neural network would behave as a linear model, regardless of the number of layers, making it limited in its ability to learn complex patterns.

**Key aspects:**

* **Non-Linearity**: Activation functions introduce non-linearity into the neural network, enabling the model to learn and approximate complex, nonlinear relationships in the data.

* **Differentiability**: Activation functions need to be differentiable, as most neural networks use gradient-based optimization techniques (e.g., backpropagation) to update model parameters during training.

* **Monotonicity**: Monotonic activation functions preserve the order of inputs, ensuring that increasing the inputs always results in an increase in the outputs.

Commonly used activation functions in neural networks include the sigmoid function, hyperbolic tangent (tanh), rectified linear unit (ReLU), and scaled exponential linear unit (SELU).

The choice of activation function can significantly impact the performance of the neural network. ReLU and its variants, such as Leaky ReLU and Parametric ReLU, are commonly used for most layers in modern neural networks due to their simplicity and effectiveness.