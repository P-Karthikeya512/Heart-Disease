# Heart Disease Prediction ML Project

## Overview
This project uses machine learning to predict the presence of heart disease based on medical data. It employs a Logistic Regression model built with scikit-learn, along with data preprocessing techniques like feature scaling using StandardScaler. The script loads a dataset (`heart.csv`), explores and preprocesses the data, splits it into training and testing sets, trains the model, and finally demonstrates a prediction on new input data.

## Features
- **Data Exploration:** Displays dataset head, tail, shape, and summary statistics.
- **Data Validation:** Checks for missing values and review data distribution.
- **Preprocessing:** Splits data into features and target, and scales features using StandardScaler.
- **Model Training:** Uses Logistic Regression (with an increased maximum iteration parameter) to train on the dataset.
- **Evaluation:** Reports accuracy on both training and test sets.
- **Prediction:** Demonstrates a prediction on a new sample input, ensuring consistent scaling.

## Requirements
- Python 3.x
- Numpy
- Pandas
- Scikit-learn

Install the dependencies via:
