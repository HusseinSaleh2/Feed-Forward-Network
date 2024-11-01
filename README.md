# Simple Feed-Forward Neural Network Implementation

## Overview
This repository contains an implementation of a simple feed-forward neural network built from scratch using Python and NumPy. The implementation features two hidden layers, with 8 neurons in the first layer and 4 in the second. The neural network is designed to be modular, allowing users to adapt and extend it for various machine learning tasks.

This network was applied to a classification dataset determining whether or not a person has diabetes based on a multitude of health-related factors, showcasing its application in real-world scenarios and its ability to handle binary classification tasks.

## Files
- **`diabetes.csv`**: The dataset used for training and testing the neural network. This dataset contains various features related to health metrics used for predicting diabetes.
- **`NeuralNetwork.py`**: The Python file containing the `NeuralNetwork` class, which includes methods for initialization, forward propagation, backpropagation, training, and prediction.
- **`NeuralNetwork.ipynb`**: A Jupyter Notebook demonstrating the use of the `NeuralNetwork` class with the `diabetes.csv` dataset. It includes the full training process, evaluation, and example predictions.
- **`README.md`**: This file, explaining the project and usage details.

## Usage
### Prerequisites
Ensure you have Python 3.x installed and the following Python libraries:
```bash
pip install numpy pandas matplotlib jupyter
```
## Running the Code
```bash
git clone https://github.com/HusseinSaleh2/Feed-Forward-Network.git
cd Feed-Forward-Network
