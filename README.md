# Loan-Interest-Rate-Prediction

## Data Source:
- Data souce: academic (from professor)
- Dimension: 400,000 rows，32 columns
- Details: features related to borrower traits, loan terms, borrower account cash flows and situations （ex. borrower id, loan id, loan amount, loan grade, number of payments, borrower job title, reason for loan, borrower annual income, borrower total credit revolving balance)


## Objective
1. Deal with the many missing datas in this dataset
2. Build machine learning models to predict the interest rate assigned to a loan

## Tools used:
- EDA, Modeling: Python Jupyter Notebook

## Files explained (The original dataset is not put here since it is too large):
- **Loan_Interest_Rate_Prediction_Assignment.ipynb**: the notebook that contains all codes written for this project
- **Metadata.csv**: the file that explains the meaning of each column in the dataset

## Result:
▪ Imputed missing values, one-hot/label encoded different categorical variables and deleted highly correlated features
▪ Applied and compared 5 ML algorithms(Decision Tree, Random Forest, Linear Regression, Gradient Boosting)
▪ Achieved RMSE score of 0.02 (initial RMSE: 3.0+) by reducing the 30 features (100+features after encoding) to only 2 important features after feature analysis and choosing Linear Regression after model comparison 
