# NN-from-scratch

#### This project implements a neural network from scratch using Python and NumPy. 
##### It includes the following key components:
  
  - Data Generation: It generates a synthetic dataset with 2 features and 3 classes.
  - Layer_Dense Class: This class represents a dense (fully connected) layer in the neural network. It initializes with random weights and zero biases and has a forward method for calculating the output of the layer.
  - Activation_ReLU Class: This class implements the Rectified Linear Unit (ReLU) activation function, which is applied element-wise to the layer's output in the forward method.
  - Activation_softmax Class: This class implements the softmax activation function, used for converting raw output values into class probabilities.
  - Loss and Categorical Cross-Entropy Loss: It defines a Loss base class and a specific loss function class for categorical cross-entropy. The loss is calculated based on the negative log-likelihood of predicted class probabilities compared to the true class labels.
  - Training and Evaluation: It creates a neural network by connecting two dense layers with ReLU and softmax activation functions. It computes the loss based on the network's output and the ground truth labels.
  - The code then demonstrates the forward pass of the neural network on the generated dataset and calculates the categorical cross-entropy loss. The result of the loss is printed.

In summary, this project is a basic neural network implementation that can handle simple classification tasks using feedforward architecture with ReLU activation and softmax output, while calculating the associated loss for training and evaluation.




