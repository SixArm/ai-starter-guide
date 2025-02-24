# Activation function

In artificial neural networks, an activation function is a mathematical function applied to the output of a neuron (or node) to introduce non-linearity into the model. Activation functions play a crucial role in neural networks as they determine whether a neuron should be activated (i.e., "fire") or not, influencing the flow of information through the network.

The activation function takes the weighted sum of inputs and biases at a neuron and transforms it into the neuron's output. Without activation functions, the neural network would behave as a linear model, regardless of the number of layers, making it limited in its ability to learn complex patterns.

**Key aspects:**

* **Non-Linearity**: Activation functions introduce non-linearity into the neural network, enabling the model to learn and approximate complex, nonlinear relationships in the data.

* **Differentiability**: Activation functions need to be differentiable, as most neural networks use gradient-based optimization techniques (e.g., backpropagation) to update model parameters during training.

* **Monotonicity**: Monotonic activation functions preserve the order of inputs, ensuring that increasing the inputs always results in an increase in the outputs.

* **Commonly used activation functions in neural networks include**:

* **Sigmoid Function**: The sigmoid activation function maps the weighted sum of inputs to a value between 0 and 1. It was commonly used in the past but is less popular now due to issues with vanishing gradients and the "vanishing gradient" problem.

* **Rectified Linear Unit (ReLU)**: The ReLU activation function outputs the input if it is positive, and 0 otherwise. It is computationally efficient and helps mitigate the vanishing gradient problem.

* **Leaky ReLU**: Leaky ReLU is a variant of ReLU that allows a small, non-zero output for negative inputs, which helps prevent some of the issues with dead neurons that can occur with ReLU.

* **Hyperbolic Tangent (tanh)**: The tanh activation function maps the weighted sum of inputs to a value between -1 and 1. It is similar to the sigmoid function but has a range from -1 to 1, which can be beneficial in certain cases.

* **Scaled Exponential Linear Unit (SELU)**: SELU is a self-normalizing activation function that has been shown to improve training performance in deep neural networks, particularly in architectures with many layers.

The choice of activation function can significantly impact the performance of the neural network. ReLU and its variants, such as Leaky ReLU and Parametric ReLU, are commonly used for most layers in modern neural networks due to their simplicity and effectiveness. However, the selection of the activation function should be based on the specific problem and network architecture to achieve the best results.