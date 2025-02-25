# Bank Customer Churn Prediction

## Overview
This project analyzes customer churn in a banking dataset using Exploratory Data Analysis (EDA) and machine learning models. The goal is to predict whether a customer is likely to leave the bank based on various demographic and financial factors.

## Dataset
The dataset used for this project contains customer details, including age, gender, account balance, and other financial attributes, along with a target variable `churn` indicating whether the customer has left the bank.

## Features
- `age` - Age of the customer
- `gender` - Gender of the customer (encoded)
- `balance` - Account balance of the customer
- `credit_score` - Credit score of the customer
- `tenure` - Number of years the customer has been with the bank
- `num_of_products` - Number of products the customer has with the bank
- `estimated_salary` - Estimated salary of the customer
- `churn` - Target variable (1: churned, 0: not churned)

## Project Workflow

### 1. Exploratory Data Analysis (EDA)
- **Basic Data Overview**
  - Checking for missing values and duplicates
  - Summary statistics of the dataset
- **Visualizations**
  - Distribution of customer age
  - Churn rate by gender
  - Correlation heatmap of features

### 2. Data Preprocessing
- Encoding categorical variables (e.g., `gender`)
- Splitting dataset into training and testing sets
- Standardizing numerical features

### 3. Machine Learning Models
- **Logistic Regression**
- **Random Forest Classifier**
- **Gradient Boosting Classifier**
- Model performance evaluation using:
  - Accuracy
  - Precision
  - Recall
  - ROC-AUC Score
  - Confusion Matrix

### 4. Model Comparison
- Visualization of model accuracy using bar plots

## Installation and Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Bank-Customer-Churn-Prediction.git
   cd Bank-Customer-Churn-Prediction
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Python script:
   ```bash
   python churn_prediction.py
   ```

## Dependencies
- Python 3.x
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn

## Results
- The Gradient Boosting model achieved the highest accuracy compared to Logistic Regression and Random Forest.
- Age, account balance, and credit score were identified as important factors influencing churn.

## Future Improvements
- Feature engineering to improve model performance
- Hyperparameter tuning for better accuracy
- Deploying the model as a web application





