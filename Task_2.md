# Week 2: Real Estate Housing Price Prediction

## Project Overview
This project predicts California housing prices using Machine Learning regression algorithms.

## Dataset
California Housing Dataset

- Total Records: 20,640
- Total Columns: 10
- Target Variable: median_house_value

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Data Preprocessing
- Handled missing values using median imputation.
- Checked and removed duplicate records (none found).
- Applied One-Hot Encoding to ocean_proximity.
- Split the dataset into 80% training and 20% testing.
- Applied StandardScaler for feature scaling.

## Machine Learning Models
1. Linear Regression
2. Ridge Regression
3. Lasso Regression

## Model Evaluation

| Model | RMSE | MAE | R² Score |
|---|---:|---:|---:|
| Linear Regression | 70060.52 | 50670.74 | 0.6254 |
| Ridge Regression | 70057.43 | 50668.13 | 0.6255 |
| Lasso Regression | 69995.18 | 50612.80 | 0.6261 |

## Best Model
Lasso Regression achieved the best results.

- RMSE: 69995.18
- MAE: 50612.80
- R² Score: 0.6261

## Visualizations
- Actual vs Predicted House Prices
- Residual Distribution Plot

## Conclusion
The project successfully demonstrates housing price prediction using Linear, Ridge, and Lasso Regression. Lasso Regression achieved the best performance with an R² score of 0.6261.

This project provided practical experience in data preprocessing, regression algorithms, regularization, and model evaluation.