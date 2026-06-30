# House Price Prediction Model Comparison

## Project Overview

This project compares multiple machine learning models for predicting house prices using the California Housing Dataset from scikit-learn.

## Objective

The goal of this project is to:

* Apply feature scaling using StandardScaler.
* Train and compare multiple regression models.
* Evaluate model performance using RMSE and R² Score.
* Identify the best-performing model.

## Dataset

California Housing Dataset provided by scikit-learn.

## Models Used

1. Linear Regression
2. Ridge Regression
3. Decision Tree Regressor

## Performance Results

| Model                   | RMSE     | R² Score |
| ----------------------- | -------- | -------- |
| Linear Regression       | 0.745581 | 0.575788 |
| Ridge Regression        | 0.745554 | 0.575819 |
| Decision Tree Regressor | 0.724234 | 0.599732 |

## Best Model

Decision Tree Regressor achieved the best performance with:

* Lowest RMSE: 0.724234
* Highest R² Score: 0.599732

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

## Project Files

* Task2_feature_engineering_model_comparison.ipynb
* Task2_Report.pdf

## Conclusion

The project successfully demonstrates feature scaling, model training, model comparison, and performance evaluation on the California Housing Dataset. The Decision Tree Regressor provided the best predictive accuracy among the tested models.
