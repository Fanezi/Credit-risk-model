# Credit Risk Modelling (Probability of Default) 

## Overview
This project builds a Probability of Default (PD) model to support credit risk assessment for loan applicants. The model estimates the likelihood that a customer will default on their loan obligations.

## Business Problem
Banks must manage the trade-off between approving profitable customers and limiting credit losses. Accurately identifying high-risk customers enables better loan approval and risk management decisions.

## Dataset
UCI Credit Card Default Dataset.

## Approach
- Exploratory Data Analysis (EDA)
- Feature engineering focused on repayment behaviour
- Logistic Regression model
- Model evaluation using ROC-AUC and confusion matrix

## Key Findings
- Repayment behaviour variables are the strongest predictors of default
- Customers with recent payment delays show higher default risk
- Credit limits and demographics provide supporting context

## Business Value
The model supports risk-based decision making by allowing banks to adjust approval thresholds based on their risk appetite.

## Tools Used
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
