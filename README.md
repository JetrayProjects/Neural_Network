# Neural Network for Pattern Recognition using Back-propagation learning rule

Neural Network Implementation with NumPy: Identity Matrix Prediction

## Overview
This project implements a simple neural network using NumPy, featuring a single hidden layer and backpropagation for learning. The network is designed to predict an identity matrix from a given input dataset, demonstrating the fundamentals of neural networks and gradient descent.

## Features
- **Custom Implementation**: Built entirely with NumPy without high-level machine learning libraries.
- **Backpropagation**: Implements gradient descent to minimize mean squared error (MSE).
- **Visualization**: Plots the learning curve by showing the MSE over iterations.
- **Educational Focus**: Provides a hands-on example to learn neural network mechanics.

## How It Works
1. **Initialization**:
   - Random weights and biases are initialized for the input, hidden, and output layers.
   - The activation function used is the sigmoid function.

2. **Training**:
   - The network is trained over multiple iterations using backpropagation to adjust weights and biases.
   - Utilized the sigmoid activation function to update the weights.
   - The error is calculated using mean squared error.

3. **Output**:
   - After training, the network predicts an identity matrix as the target output for the given input dataset.
   - The learning curve is visualized by plotting MSE against the number of iterations.

## Dependencies
- Python 3.x
- NumPy
- Matplotlib

## Usage
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```bash
   cd <project-directory>
   ```

3. Install the required dependencies:
   ```bash
   pip install numpy matplotlib
   ```

4. Run the script:
   ```bash
   python Project_Group_3_code_final.py
   ```

5. Observe the learning curve plot and view the predicted output in the console.

## Example Output
- **Learning Curve**:
  A plot of mean squared error over iterations.

- **Predicted Output**:
  The network predicts a matrix closely resembling the identity matrix after training.

## Key Functions
- `sigmoid_np(x)`: Computes the sigmoid activation function.
- `sigmoidDerivative(y)`: Computes the derivative of the sigmoid function.
- `backpropagationWithNumpy(x, y, iterations, learningRate)`: Trains the neural network and returns the predicted output.



