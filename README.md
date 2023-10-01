# Predicting and Analysis of Credit-Card-Defaulters-In-Taiwan

# Summary:
This project aims to predict credit card defaulters in Taiwan based on customers' historical data. It utilizes a Kaggle dataset with a substantial amount of information, which has been dimensionally reduced through Principal Component Analysis (PCA) to facilitate efficient computation in Google Colab. The project employs six supervised machine learning techniques for analysis and prediction.

# Data Description:
The dataset includes various features such as ID, credit limit, gender, education level, marital status, age, and repayment history for six months. Additionally, it contains bill amounts and payment amounts for the same period, along with the target variable indicating whether a customer will default next month.

# Methodology:

Importing libraries and dependencies.
Data visualization and analysis.
Exploring correlations among dataset features.
Data cleaning and preprocessing.
Scaling numerical attributes.
Applying machine learning algorithms for classification.
Employing Grid-Search Cross-Validation to enhance accuracy.
Evaluating model performance.

# Machine Learning Techniques used:
SVM
Decision Tree
Random Forest
Logistic Regression
K nearest neighbours
Ensemble classifier using decision trees


# Conclusion:
The analysis results in the following prediction accuracies for customer default:

## Logistic Regression: 82.5%
## Stochastic Gradient Descent: 83.33%
## Support Vector Machine: 80.83%
## K-Nearest Neighbors: 80.83%
## Decision Tree: 82.83%
## Random Forest: 81%
## XGBOOST: 82.16%

The most influential predictors of default are the repayment status in previous months (PAY_X), credit limit (LIMIT_BAL), and previous payment amounts (PAY_AMTX). Notably, Stochastic Gradient Descent and Decision Tree methods outperform others in predicting defaults.
