# Customer Churn Prediction

A small machine learning project that predicts whether a telecom customer is likely to leave the service.

## What I worked on

- Loaded and checked customer data
- Looked at missing values and churn distribution
- Removed the customer ID from the model features
- Filled missing values using a preprocessing pipeline
- Converted categorical columns with One-Hot Encoding
- Scaled numerical features
- Trained Logistic Regression and Random Forest models
- Compared the models using Accuracy and ROC-AUC
- Checked the Random Forest confusion matrix
- Used predicted probabilities to estimate churn risk for an individual customer

## Dataset

The dataset contains 1,200 customer records with fields such as age, tenure, phone service, internet service, contract type, monthly charges, total charges, and churn status.

`Churn` is the target column:
- `No` = customer stayed
- `Yes` = customer left

## Tools

- Python
- pandas
- NumPy
- matplotlib
- scikit-learn
- Jupyter Notebook

## Files

- `Customer_Churn_Analysis_Custom.csv` — dataset used in the notebook
- `Customer_Churn_Project_Custom.ipynb` — complete analysis and model training

## How to run

1. Keep the notebook and CSV in the same folder.
2. Open the notebook in Jupyter or Google Colab.
3. Run the cells from top to bottom.

## Note

The dataset is a customized practice dataset created for this project, so the notebook can be reproduced without downloading the original Kaggle file.
