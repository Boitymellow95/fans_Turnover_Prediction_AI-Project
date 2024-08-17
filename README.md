Employee Turnover Prediction Project
Description

This project involves analyzing a dataset from Big Company Inc., which is concerned about employee turnover, particularly among their data scientists. The goal is to predict whether a data scientist will remain with the company three months after filling out an employee satisfaction survey. By building a logistic regression model, we aim to identify the key factors that influence an employee's decision to stay or leave.
Dataset Overview

The dataset includes the following variables:

    Stay: Indicates whether the data scientist remained with the company three months after the survey (target variable).
    Pay: The employee's monthly salary in dollars.
    Estimated Happiness: A metric derived from a model that reviews both the employee's reported happiness and their comments on what they’d like to see changed.
    Performance: The result of the manager's performance review.

Project Objectives

The primary goal of this project is to build a logistic regression model to predict whether an employee will stay with the company based on the given features. The project is divided into the following tasks:
1. Data Exploration

    Conduct an initial exploration of the dataset.
    Analyze the distributions and relationships between the variables.
    Provide reasoning behind the exploration steps.
    Visualize the data using scatter plots, histograms, and correlation matrices to gain insights.

2. Variable Selection and Engineering

    Select relevant variables for the model.
    Discuss any feature engineering steps taken to create new variables that could improve the model's performance.
    Explain the rationale behind each iteration of variable selection and feature engineering.

3. Model Training and Validation

    Split the dataset into training, validation, and test sets.
    Fit a logistic regression model using the training set.
    Use the validation set to tune hyperparameters and features of the model.
    Calculate the final accuracy of the tuned model on the test set and provide the code used to achieve this.

4. Model Analysis

    Discuss the logistic regression model in the context of the problem.
    Analyze whether the model makes sense based on the selected variables and their coefficients.
    Provide insights into how well the model aligns with the initial hypotheses.

5. Data Intuition and Validation

    Compare the model results with the intuition gained from data exploration.
    Discuss whether the data matches the intuition and whether the scatter plots and other visualizations support the model's findings.

Installation

To run this project, you will need Python and the following libraries:

    NumPy
    Pandas
    Matplotlib
    Seaborn
    Scikit-learn
    Statsmodels

You can install the required libraries using pip:

bash

pip install numpy pandas matplotlib seaborn scikit-learn statsmodels

Usage

To run the analysis, follow these steps:

    Load and explore the dataset.
    Select and engineer relevant variables.
    Train the logistic regression model using the training set.
    Tune the model using the validation set.
    Test the final model and evaluate its performance.
    Analyze the results and discuss the findings.

Results

The results of the analysis will include:

    A detailed exploration of the dataset.
    The reasoning behind variable selection and feature engineering.
    The accuracy of the logistic regression model on the test set.
    Visualizations comparing the model's predictions with actual outcomes.
    A discussion on the alignment of the model with data intuition.

Conclusion

This project aims to identify key factors influencing employee turnover among data scientists at Big Company Inc. The logistic regression model will provide insights into which variables are most predictive of an employee's decision to stay or leave, and how well the model aligns with the initial exploration of the data.
License

This project is licensed under the MIT License - see the LICENSE file for details.
