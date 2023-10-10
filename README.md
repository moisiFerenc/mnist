# mnist
This code implements a simple neural network for training and testing on the "MNIST" handwritten digit recognition dataset. The code is written in Python and consists of the following main steps:

Data Loading: Loading the MNIST dataset from a CSV file and reshaping and normalizing the data.

Initialization: Initializing the network's parameters (weights and biases).

Forward Propagation: During forward propagation, inputs are passed through the network, ReLU activation is applied after the first layer, and softmax activation is applied after the last layer to make predictions.

Backpropagation: Using the predictions calculated during forward propagation to compute gradients and update weights and biases.

Training: The algorithm repeats forward and backward propagation steps on the dataset according to the number of iterations.

Testing: Testing the network on a test dataset and calculating accuracy.

Menu System: An interactive menu system allows for choosing between different operations, such as training, testing, and checking accuracy.

Notes:
![image](https://github.com/moisiFerenc/mnist/assets/78962708/8e0db742-cf03-4317-8748-591a3d3a3edb)
![image](https://github.com/moisiFerenc/mnist/assets/78962708/922287dd-f181-4745-9cd5-e4c93f825f0a)
