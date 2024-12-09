This project implements an artificial neural network (ANN) for solving a 3-input XOR gate. The implementation is done from scratch using only NumPy.
Inputs: 3 inputs for the XOR logic gate.

Architecture:
3 Input neurons.
4 Hidden layers.
1 Output neuron.
Training: Trained for 1000 epochs using a custom backpropagation algorithm.
 
Model Architecture:-
The ANN uses fully connected layers, with weights and biases initialized randomly.

Training:
Forward Propagation:- Compute activations for each layer.

Backpropagation:- Update weights and biases to minimize error using gradient descent.
Evaluation:

The trained model is evaluated against the XOR truth table.

Results:-
The network correctly learns the XOR function after training.
Output matches the expected values of the 3-input XOR truth table.
Customization

You can modify:
The number of hidden layers or neurons.
The number of epochs or learning rate for experimentation
