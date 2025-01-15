House Price Prediction
This project aims to predict the final sales price of homes using linear regression. I leveraged a training dataset to develop a predictive model and employ cross-validation techniques to ensure robust out-of-sample performance. 

# Project Goal
The primary objective is to build a linear regression model that accurately predicts home prices. The goal is to achieve a minimum out-of-sample R² of 0.85 through cross-validation on the training data. Additionally, we aim for a Kaggle score of less than 0.15 (if applicable). 

# Dataset 
It's a publicly available dataset from kaggle.com and the link is provided below. 

https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data 
# Methodology
## Data Understanding and Cleaning : 
Began by thoroughly exploring the dataset, identifying missing values, outliers, and inconsistencies. Appropriate data cleaning and preprocessing techniques are applied. 
## Exploratory Data Analysis (EDA) : 
Performed EDA to gain insights into the data, identify relationships between variables, and formulate hypotheses. Visualizations and summary statistics are used extensively.
## Model Development : 
A linear regression model is trained on the prepared training data.
## Cross-Validation : 
K-fold cross-validation is used to estimate the out-of-sample performance of the model and to tune hyperparameters.
## Model Evaluation : 
The final model is evaluated using appropriate metrics, including R² and potentially RMSE or MAE. We aim for an out-of-sample R² of at least 0.85. If participating in a Kaggle competition, the Kaggle score is also tracked, aiming for a score below 0.15.
## Determined the main predictors for a house sale price and some of them include : 
overall condition, ground living area, parking lot etc. (more detailed decription on the rmd file) Achieved an R² score of 0.91 and Kaggle score 0.14.

# Future Work
Evaluate tree-based models like Random Forest or Gradient Boosting Machines (e.g., XGBoost, LightGBM) which can often capture non-linear relationships more effectively.