# Credit Risk Modeling: Predicting Loan Default Using LendingClub Data

This project analyzes LendingClub loan data to identify borrower characteristics associated with loan default and estimate the probability of default (PD) using logistic regression.

## Project Overview

The analysis includes:

- Data cleaning and preprocessing
- Exploratory analysisof borrower risk factors
- Logistic regression modeling
- Model evaluation using classification metrics
- Interpretation of Model Coefficients
- Estimation of predicted probabilities of default

## Key Findings

- Higher interest rates and higher debt-to-income ratios associated with increased default risk
- Higher FICO scores and borrower income correspond to lower default risk
- The model achieves appx. 80% classification accuracy, though class imbalance reduces the model's ability to detect some defaulted loans

## Predicted Probability of Default Distribution

![PD Distribution](pd_distribution.png)

## Tools Used

- Python
- Pandas
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook
