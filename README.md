# Data-Analysis-Project
This project involves the exploration and analysis of financial data related to stock prices. The analysis is conducted using Python programming language and various libraries such as NumPy, Pandas, Seaborn, and Matplotlib. The project aims to predict the next day's return for different tunisian companies based on historical stock data.

The project is divided into several sections:

## I- Data Visualization and Preparation
The initial steps involve loading the dataset, checking for missing values, and visualizing the distribution of the target variable ('next_day_ret'). Outliers are identified and removed to improve the target variable's distribution.

## II- Feature Engineering
The dataset undergoes feature engineering, including the handling of missing values and the creation of a new feature ('currReturn'). Additionally, a factor analysis (FA) is performed to reduce dimensionality and represent correlated variables by a smaller number of factors.

## III- Modeling with Factor Analysis (FA)
The project utilizes linear regression as the modeling technique, with factor analysis-derived features. The model is trained on the training set, and predictions are made for the test set.

## IV- Modeling with Principal Component Analysis (PCA)
Similar to the FA section, this part of the project involves modeling using linear regression but with features derived from principal component analysis (PCA).

## V- Time Splitting
The dataset is split by time to ensure that the model does not use future information in the test data to predict returns for a specific day. Dummy variables are created for the 'company' feature to allow the model to identify each company independently.


Throughout the project, data visualization, preprocessing, and feature engineering techniques are applied to improve the model's performance. The primary focus is on predicting stock returns and understanding the relationship between different financial features.
