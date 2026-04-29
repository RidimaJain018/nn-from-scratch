# Neural Network from Scratch (NumPy)

A 2-layer neural network built from scratch using only NumPy — no PyTorch, no TensorFlow.

## What this covers
- Forward pass through hidden and output layers
- Activation functions — ReLU (hidden layer), Sigmoid (output layer)
- Binary cross-entropy loss
- Backpropagation using chain rule — all gradients computed manually
- Gradient descent weight updates
- Training loop over 1000 epochs

## Architecture
- Input: 3 features
- Hidden Layer: 4 neurons + ReLU
- Output Layer: 1 neuron + Sigmoid (binary classification)

## Key decisions
- Weights initialized randomly (not zeros) to break symmetry
- Bias initialized to zeros
- Learning rate: 0.01
