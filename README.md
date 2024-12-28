# Sonar-Rock-vs-Mine-Classification-using-Logistic-Regression-
This project demonstrates the classification of sonar signals to distinguish between rocks and mines using logistic regression. It is a practical implementation of a machine learning algorithm to solve a binary classification problem.

Project Overview
Sonar data contains frequency and amplitude information of reflected signals that bounce off objects underwater. The goal of this project is to classify these signals into two categories:

Rocks (R)
Mines (M)
The dataset used contains 208 samples with 60 features each, representing sonar readings.

Key Features
Data Preprocessing: The dataset is cleaned and prepared for training, with the features and target variable properly separated.
Stratified Train-Test Split: Ensures class balance in both training and testing datasets.
Model Training: Logistic regression is used as the classification model.
Model Evaluation: Evaluated on training and test data with accuracy scores.
Results
Training Accuracy: ~83.42%
Test Accuracy: ~76.19%

Tools and Libraries Used
Programming Language: Python
Libraries:
Pandas
NumPy
Scikit-learn (for Logistic Regression and model evaluation)

Insights and Learnings
Logistic regression can effectively solve binary classification problems with numerical features.
Proper data preprocessing, such as splitting and reshaping input data, is crucial for model accuracy.
Achieving high accuracy depends on the quality of the data and hyperparameter tuning.
