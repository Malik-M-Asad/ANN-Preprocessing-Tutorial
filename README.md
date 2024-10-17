# ANN Preprocessing Tutorial
This repository contains a Jupyter Notebook demonstrating various preprocessing techniques on the Titanic dataset to prepare it for training an artificial neural network (ANN).
## Table of Contents
- [Introduction](#introduction)
- [Preprocessing Steps](#preprocessing-steps)
- [Conclusion](#conclusion)
## Introduction
Preprocessing is crucial for machine learning models, especially for neural networks. This notebook covers essential steps such as handling missing values, scaling numerical features, encoding categorical variables, and preparing data for PyTorch.
## Preprocessing Steps
1. **Loading the Dataset**
   - The Titanic dataset is loaded using pandas. 
2. **Handling Missing Values**
   - Missing values are filled with mean or mode as appropriate.
3. **Scaling Numerical Features**
   - Numerical features like Age and Fare are scaled to improve model performance.
4. **Encoding Categorical Variables**
   - Categorical variables are converted to numerical format using OneHotEncoder.
5. **Splitting the Dataset**
   - The dataset is split into training and testing sets.
6. **Converting Data to PyTorch Tensors**
   - The processed data is converted into tensors for training.
## Conclusion
Effective preprocessing is essential to ensure that data is ready for training artificial neural networks. This guide illustrates how to prepare data using common preprocessing techniques.
