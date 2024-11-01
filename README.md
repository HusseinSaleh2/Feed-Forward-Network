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
1. **Clone the repository**
```bash
git clone https://github.com/HusseinSaleh2/Feed-Forward-Network.git
cd Feed-Forward-Network
```
2. **Open and Run the Jupyter Notebook**
```bash
jupyter notebook NeuralNetwork.ipynb
```

## Dataset
The dataset used in this project contains 768 samples, each representing a unique patient profile with 8 health-related features. These features include important medical metrics that help determine the likelihood of diabetes in patients. The classification target is binary: indicating whether the patient has diabetes (`1`) or does not (`0`).

### Features
The dataset comprises the following 8 factors:
1. **Pregnancies**: Number of times the patient has been pregnant.
2. **Glucose**: Plasma glucose concentration after a 2-hour oral glucose tolerance test.
3. **Blood Pressure**: Diastolic blood pressure (mm Hg).
4. **Skin Thickness**: Triceps skinfold thickness (mm).
5. **Insulin**: 2-hour serum insulin (mu U/ml).
6. **BMI (Body Mass Index)**: Weight in kg/(Height in m)^2.
7. **Diabetes Pedigree Function**: A function that scores the likelihood of diabetes based on family history.
8. **Age**: Age of the patient in years.

### Target Variable
- **Outcome**: The output is binary, where `0` represents a patient who does not have diabetes, and `1` represents a patient who does.

