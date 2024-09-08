# Predicted-Attrition-for-Employees

## Project Overview

This project leverages machine learning techniques to predict employee attrition within a company. By analyzing features such as job role, distance from home, and salary, the model aims to provide actionable insights to HR departments to proactively address potential employee turnover. The model is developed using a Random Forest Classifier and includes a comprehensive data preprocessing pipeline.

## Features

- **Data Preprocessing**: Cleaning and transforming the dataset, including handling categorical variables and scaling numerical features.
- **Model Training**: Training a Random Forest Classifier to predict employee attrition.
- **Prediction**: Generating predictions for new employee data.
- **Visualization**: Presenting the prediction results using a bar plot for easy interpretation.

## Project Structure

- `WA_Fn-UseC_-HR-Employee-Attrition.csv`: Dataset used for model training and evaluation.
- `employee_attrition.py`: Main script for data preprocessing, model training, and predictions.
- `scaler.pkl`: Serialized MinMaxScaler object for feature scaling.
- `random_forest_model.pkl`: Serialized Random Forest model for prediction.
- `column_names.pkl`: Serialized list of column names used in the model.
- `README.md`: Documentation for the project.

## Installation

To set up the project environment, you need the following Python libraries. You can install them using pip:

```bash
pip install pandas scikit-learn joblib matplotlib seaborn


