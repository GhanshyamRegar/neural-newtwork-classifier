# Neural Network Classifier

## Features
- No external ML libraries used
- One hidden layer with sigmoid activation
- Custom backpropagation and gradient descent
- Visualizes loss over epochs
- Displays predictions using `matplotlib`

## Structure
- `neural_network_classifier.ipynb`: Full code
- `README.md`: Project explanation

## How it Works
1. Images of A, B, C are binary vectors of 30 pixels.
2. One-hot encoding is used for labels.
3. A neural network with 30 input nodes, 10 hidden nodes, and 3 output nodes is trained using MSE loss.
4. After training, predictions are made and shown visually.

## Results
Achieved perfect classification on training data after ~1000 epochs.

## To Run
```bash
pip install numpy matplotlib
python neural_network_classifier.ipynb
