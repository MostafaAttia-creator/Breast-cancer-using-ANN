Breast Cancer Detection using ANN
Project Overview

This project implements an Artificial Neural Network (ANN) from scratch using NumPy to classify breast cancer tumors as:

Malignant (M)
Benign (B)

The model is trained on a real dataset and evaluated using accuracy.

Technologies Used
Python
NumPy
Pandas
Matplotlib
Scikit-learn
Model Architecture
Input Layer: Based on dataset features
Hidden Layer 1: 16 neurons (ReLU)
Hidden Layer 2: 8 neurons (ReLU)
Output Layer: 1 neuron (Sigmoid)
Workflow
Data Loading and Cleaning
Handling Missing Values
Encoding Target Labels
Train-Test Split
Feature Scaling (StandardScaler)
Building ANN from scratch
Training using Backpropagation
Evaluation using Accuracy
Results
Accuracy: XX%
Training loss plotted over epochs
Visualization
Training Loss Curve
Predictions vs True Labels
Prediction Distribution
How to Run

git clone https://github.com/MostafaAttia-creator/Breast-cancer-using-ANN.git
cd Breast-cancer-using-ANN
jupyter notebook

Then open:
CI_Project_ANN.ipynb

Key Features
ANN implemented from scratch (no deep learning frameworks)
Custom forward and backward propagation
Activation functions: ReLU, Sigmoid
Gradient clipping to stabilize training
Author

Mostafa Attia

Notes
This project is for educational purposes
Possible improvements:
Use CrossEntropy Loss
Add mini-batch training
Apply regularization techniques
