# Multiclass Classification with Neural Network (Softmax Output)

This project implements a simple neural network for solving multiclass classification problems. It features a Softmax output layer, which transforms logits into class probabilities, making the model suitable for interpreting categorical outcomes.

## Features

- Custom Softmax implementation
- Forward pass logic for neural networks
- Multi-class classification support
- Clean and readable code with explanations

## Mathematical Background

The Softmax function converts raw logits \( z \) into probabilities:

\[
\sigma(z)_i = \frac{e^{z_i}}{\sum_{j=1}^{n} e^{z_j}}
\]

This ensures all outputs are in the range (0, 1) and sum to 1, making them interpretable as class probabilities.

## Requirements

- Python 3.6+
- NumPy
- Jupyter Notebook

## Running the Project

1. Clone this repository.
2. Open `softmax.ipynb` in Jupyter Notebook.
3. Run the notebook to explore the step-by-step Softmax implementation and classification example.

## Applications

- Neural network output layer
- Multiclass classification
- NLP and vision tasks involving probability outputs

## Author

Himwan Singh Shekhawat
