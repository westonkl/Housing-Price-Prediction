# Housing Price Prediction: Project Overview
* Data preprocessing: took log of skewed numerics, created dummies for categoricals, and replaced null values with the mean of their respective column
*Predicted housing prices with ridge, lasso, and elastic regression models
*Found the most impactful coefficients(features) on predicting a house's price with lasso and elastic 
*Used xgboost to get a better score

#Resources Used
**Python Version:** 3.6
**Packages:** pandas, numpy, sklearn, matplotlib, scipy, xgboost

# Data Preprocessing:

* took log of skewed numerics
* created dummies for categoricals
* replaced null values with the mean of their respective column

# Model Building:

I tested 4 different modesls and evaluated them with root mean square error (RMSE). 

* **Ridge Regression** : 0.12733734668670765
* **Lasso Regression** : 0.1225673588504812
* **Elastic Regression** : 0.1237462980365083
* **Xgboost** : 0.12494475766362181
