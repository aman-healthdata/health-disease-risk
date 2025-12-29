# Disease Risk Prediction Using Machine Learning

## Overview
This project predicts the risk of heart disease based on patient health features using a Logistic Regression model. 
It demonstrates practical health data science skills, including data cleaning, scaling, model training, evaluation, and visualization.

## Dataset
- Public Heart Disease dataset from UCI repository (curated version)  
- Features include: age, sex, chest pain type, resting blood pressure, cholesterol, max heart rate, etc.  
- Target: 1 = heart disease, 0 = no disease

## Methods
- Train/test split (80/20) with stratification  
- Feature scaling using StandardScaler  
- Logistic Regression model for binary classification  
- Evaluation metrics: Accuracy, Confusion Matrix, Precision, Recall, F1-score

## Results
- Model accuracy: ~[insert your accuracy here]  
- Confusion matrix and feature importance visualizations show model performance and key predictors

## Limitations
- Logistic Regression is a linear model; non-linear relationships are not captured  
- Dataset size is moderate; larger datasets may improve performance  
- Does not include interventions or lifestyle factors beyond the dataset features

## Tools
Python, pandas, scikit-learn, matplotlib, seaborn (Google Colab)

