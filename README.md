# AI Job Salary Classification

Binary classification model that predicts whether an AI job offer is high-salary, using Python and scikit-learn.

## Overview
- **Goal:** Predict whether an AI job offer is "High Salary" (above median) based on professional and company features
- **Dataset:** 15,000 records (job title, experience level, location, company size)
- **Target:** High Salary (binary: above/below median)

## Tools
Python, Pandas, NumPy, Matplotlib, Scikit-learn (Logistic Regression, KNN, Decision Tree, GridSearchCV), Jupyter Notebook

## Steps
1. Data cleaning and preprocessing
2. Exploratory data analysis
3. Model training and evaluation

## Results
- **Best model:** Logistic Regression with 92.3% accuracy
- Decision Tree: 89.9% accuracy
- K-Nearest Neighbors: 87.9% accuracy

## Files
- `AI_Job_Salary_Project.ipynb`:the full code and analysis
- `prompts_classification.pdf`: the prompts used in the project

## How to run

```
pip install pandas numpy matplotlib scikit-learn jupyter
jupyter notebook AI_Job_Salary_Project.ipynb
```
