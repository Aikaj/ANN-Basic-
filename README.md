# ANN-Basic-
Implements the Basic ANN

The provided code is a collection of various neural network models implemented in different deep learning frameworks, including TensorFlow, Keras, and PyTorch. Here's a summary of the code:

1. TensorFlow and Keras

The code starts by importing necessary libraries, including TensorFlow, NumPy, and Matplotlib.
It loads the Fashion MNIST dataset, a popular dataset for image classification tasks.
The dataset is preprocessed, and the images are normalized to have values between 0 and 1.
A simple neural network model is defined using the Keras API, consisting of two dense layers with ReLU and softmax activations, respectively.
The model is compiled with the Adam optimizer and sparse categorical cross-entropy loss.
The model is trained on the training data for 10 epochs, and the test accuracy is evaluated.
The code also defines two plotting functions to visualize the predictions and the probability distributions.

2. Perceptron
   
A simple perceptron model is defined, which takes in input values and outputs a binary classification result based on the dot product of the inputs and weights.
TensorFlow (again)
The code loads the MNIST dataset and preprocesses it.
A shallow neural network model is defined using the Keras API, consisting of two dense layers with ReLU and softmax activations, respectively.
The model is compiled with the Adam optimizer and sparse categorical cross-entropy loss.
The model is trained on the training data for 5 epochs, and the test accuracy is evaluated.

3. PyTorch

A simple neural network model is defined using PyTorch, consisting of two linear layers with ReLU and softmax activations, respectively.
The model is instantiated, and the architecture is printed.
The loss function and optimizer are defined, and the model is trained on synthetic data for 1000 epochs.
The accuracy of the trained model is evaluated.

4. Custom PyTorch Model
   
A custom neural network model is defined using PyTorch, with a custom forward pass that uses the tanh activation function.
The model is instantiated, and the architecture is printed.
Synthetic data is generated, and the model is trained on it for 1000 epochs.
The accuracy of the trained model is evaluated.

In summary, the code demonstrates various neural network models implemented in different deep learning frameworks, including TensorFlow, Keras, and PyTorch. It covers simple neural networks, perceptrons, and custom models, and showcases the training and evaluation processes.





