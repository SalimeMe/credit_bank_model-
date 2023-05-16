# Credit Bank Models
This repository contains models for determining credit eligibility using machine learning techniques. The models are implemented in Python and were developed using Google Colab.

Table of Contents
Introduction
Dependencies
Usage
Models
Evaluation
License
Introduction
The purpose of this project is to provide a machine learning solution for determining whether an individual is eligible for credit. The models are trained on a labeled dataset and can be used to predict the creditworthiness of new applicants based on their information.

Dependencies
To run the code in this repository, you need to have the following dependencies installed:

Python 3
pandas
numpy
matplotlib
seaborn
scikit-learn

# Models
The following models are implemented in this project:

Logistic Regression
K-Nearest Neighbors (KNN)
Decision Tree
These models are trained on a labeled dataset containing features such as age, income, credit score, etc. The models learn from this data and create a decision boundary to classify applicants into two categories: eligible or not eligible for credit.

# Evaluation
The models' performance is evaluated using accuracy as the metric. After training, the models are tested on a hold-out validation set to assess their accuracy in predicting credit eligibility. The accuracy score provides an indication of how well the models generalize to new, unseen data.
