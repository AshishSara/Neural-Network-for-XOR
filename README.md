# Neural-Network-for-XOR
Neural Network for XOR Function

**Overview**
This Python script demonstrates the implementation of a basic neural network with one hidden layer. The neural network is trained to learn the XOR (⊕) function, a fundamental function in computing. The XOR function returns 1 if an odd number of inputs are true, and 0 otherwise. This is a binary classification problem that can't be solved by a single-layer perceptron, making it an interesting challenge for a neural network with at least one hidden layer.

**Libraries Used**
NumPy for numerical operations and matrix manipulations.

**Network Architecture**
**Input Layer:** 2 neurons (for 2 binary input features)
**Hidden Layer:** 2 neurons
**Output Layer:** 1 neuron (for binary classification)


**Activation Function**
Sigmoid function for both hidden and output layers

**Learning Parameters**
Epochs: 10,000
Learning Rate: 0.1

**Code Description**
Initialize random weights and biases for the hidden and output layers.
Use forward propagation to calculate the predicted output.
Compute the error between predicted and actual output.
Use backpropagation to update the weights and biases.
Repeat steps 2-4 for 10,000 epochs to train the model.

**Output and Interpretation**
The output after 10,000 epochs is: [0.07129174] [0.92693885] [0.92968861] [0.08180656]


0⊕0=0, Prediction: 0.07129174 (Close to 0)

0⊕1=1, Prediction: 0.92693885 (Close to 1)

1⊕0=1, Prediction: 0.92968861 (Close to 1)

1⊕1=0, Prediction: 0.08180656 (Close to 0)

The predictions are close to the expected output, which proves that the neural network has successfully learned to approximate the XOR function.
