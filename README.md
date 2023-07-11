# Superconductivity Prediction using Artificial Neural Networks
This repository contains a notebook which uses an Artificial Neural Network (ANN) to predict superconductivity, using the Keras API in TensorFlow. The project includes both an exploratory data analysis (EDA) and hyperparameter tuning.

## Dataset
The dataset used in this project comes from the UCI Machine Learning Repository, and can be found here.

## Project Structure
Exploratory Data Analysis: The notebook starts with a brief exploratory analysis of the dataset to understand the structure and characteristics of the data.

Data Preprocessing: The dataset is split into a training set and a testing set, with two thirds of the data used for training and one third for testing.

Modeling: An ANN model is constructed using the Keras API in TensorFlow. The model's architecture can vary depending on different hyperparameters, such as the number of hidden layers, number of neurons in each layer, and the regularization parameters for L1 and L2 norms.

Hyperparameter Tuning: A grid search is performed over a specified range of hyperparameters using Scikit-Learn's GridSearchCV. The combination of hyperparameters producing the best model according to the mean squared error (MSE) is identified.

Model Evaluation: The model's performance is evaluated based on the MSE of the model's predictions on the testing data.

Visualization: Various plots are provided to visually assess the model's performance and the importance of different features in the dataset.
