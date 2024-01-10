
# RETAIL SALES FORCASTING

# Introduction
This project focuses on retail sales forecasting using the Walmart dataset sourced from Kaggle. The goal is to leverage machine learning models to predict future sales, aiding in inventory management and business planning.

Dataset : [Kaggle](https://www.kaggle.com/datasets/aslanahmedov/walmart-sales-forecast)

# Features
- Time series forecasting
- Machine learning models
- Data preprocessing and feature engineering

# Prerequisites
Make sure you have the following dependencies installed:
- Python 3.x
- Jupyter Notebook (for running the notebooks) or use google colab

# Machine Learning Models
- Random Forest is an ensemble learning method that operates by constructing a multitude of decision trees during training and outputs the mean prediction of the individual trees for regression tasks. It is known for its high accuracy, robustness, and resistance to overfitting.
- XGBoost, short for eXtreme Gradient Boosting, is an efficient and scalable implementation of gradient boosting. It is designed for speed and performance and is often used in various machine learning competitions. XGBoost can handle missing data, regularization, and parallel computation, making it a powerful tool for predictive modeling.

# Results
The XGBoost model demonstrated outstanding performance in retail sales forecasting:

- R2 Score: 0.9393
The R2 score, also known as the coefficient of determination, measures the proportion of the response variable's variance captured by the model. A score close to 1 indicates a good fit.
Mean Squared Error (MSE): 31023846.63

- MSE measures the average squared difference between the predicted values and the actual values. A lower MSE indicates better model performance.

- Root Mean Squared Error (RMSE): 5569.91
RMSE is the square root of the MSE and represents the average magnitude of the prediction errors. Lower RMSE values indicate better predictive accuracy.

These results suggest that the XGBoost model is highly accurate in forecasting retail sales, capturing approximately 93.93% of the variance in the dataset. The low MSE and RMSE values further emphasize the model's precision in predicting sales values.

