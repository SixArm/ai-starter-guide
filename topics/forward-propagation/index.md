# Forward propagation

Forward propagation is the process in which input data is fed into a neural network, and the data is processed through the network's layers to produce an output or prediction.

Steps…

Input Data: Feed input data to the neural network. For example, input could be an image represented as a matrix of pixel values. Each neuron in the input layer represents a specific attribute of the input data.

Weights and Biases: Each connection between neurons in different layers has associated weights and biases. These weights represent the strength of the connection. Biases are additional values that adjust the output of a neuron.

Weighted Sum: For each neuron in the hidden and output layers, multiply the input data by the corresponding weights, and compute the weighted sum of the inputs. The weights determine the importance of each input attribute.

Activation Function: Pass the weighted sum through an activation function, which introduces non-linearity to the output. Common activation functions include ReLU (Rectified Linear Unit), sigmoid, and tanh. Use the activation function output as the input for the next layer.

Iterate: Repeat the steps through each layer of the neural network, including the hidden layers, until the output layer is reached. The output layer produces the final prediction.

During training, the network makes predictions on the training data, and backpropagation is used to improve the weights and biases.

During inference, forward propagation is used to make predictions on new, unseen data after the neural network has been trained. The forward pass is computationally efficient and is executed rapidly in modern deep learning frameworks.