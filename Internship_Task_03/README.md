# Week 3 - Customer Churn Prediction

## Project Overview
Developed a Machine Learning classification system to predict customer churn using the Telco Customer Churn dataset.

## Dataset
- Total Records: 7,043
- Total Features: 20 (after removing customerID)
- Target Variable: Churn

## Machine Learning Models
1. Random Forest Classifier
2. XGBoost Classifier

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

## Model Performance

| Metric | Random Forest | XGBoost |
|---|---:|---:|
| Accuracy | 78.42% | 75.73% |
| ROC-AUC | 0.8220 | 0.8443 |
| Churn Recall | 48% | 79% |
| Churn F1-score | 54% | 63% |

## Key Findings
- Month-to-month contract is the most important feature.
- Customers with shorter tenure show higher churn.
- XGBoost achieved better churn recall and ROC-AUC.

## Conclusion
This project demonstrates how Machine Learning can help businesses identify customers who are likely to leave and improve customer retention strategies.