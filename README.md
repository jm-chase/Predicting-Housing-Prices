# Predicting-Housing-Prices
Supervised Learning Project - Used various ML models to predict the sale price of home in the Ames, Iowa housing market.

# Data set
The data set is from a former Kaggle competition, challenging people to create the most accurate model possible predicting house sale prices 
from the test data set.  The training data set consisted of 1460 rows and 81 columns, with a variety of categorical and continuous data.  

# Processes / Techniques
The accompanying Jupyter notebook shows an annoted process from data exploration -> data cleaning -> feature engineering -> modeling.  Models
tested included: Random Forest Regressor, Gradient Boosting Regressor, Ridge Regression, and Lasso Regression.

A log transformation was applied to the outcome variable, SalePrice to get a normal distribution.  After we dropped some features because of collinearity,
and cleaned our null values we were ready to model.

# Summary
One-Hot Encoding worked best in the Random Forest Regressor model for this dataset.  Binary representations of the categorical variables and 
our other engineered features resulted in model that could explain 85.9% of data in our test data set.  

