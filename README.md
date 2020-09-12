# TELCO CUSTOMER CHURN PREDICTION

## Final Project Job Connector Data Science Bandung Purwadhika, Ragil Tri Junizar

Dataset taken from kaggle : https://www.kaggle.com/blastchar/telco-customer-churn

The raw data contains 7043 rows (customers) and 21 columns (features).

The “Churn” column is our target

## Problem : 

1. Predict customer churn subsequent period of time:
to optimize the program that will be given to customers to prevent Customer Churn and
Minimize operational costs and increase marketing efficiency

2. what contribute to the highest customer churn rate

3. what services we can improve to prevent customer churn.

4. Helps decision making not only for marketers, but also Operational

### In this project, there are 3 steps that I did:

Data Cleaning (Delete Useless Columns and Handle Missing Value by replacing with 0 )

Exploratory Data Analysis and Visualization 

Modelling Machine Learning Algorithm to Make Classification that can predict which customers will churn

# Machine Learning Modelling

After missing value then I have to select which columns to become a features in machine learning model using some statistical method, that is Chi-Squared testing.

These are the steps to produce Machine Learning Model that I use,

Trying 6 Model for test : Logistic Regression, Decision Tree, Random Forest Clasifier, XGBoosting, Gradient Boosting, and 
k-nearest neighbors with : 

Scaling Data
Cross Validation to avoid overfitting model
Selecting Best Model based on Evaluation Metric Score
Modelling with All feature, Feature Selection, Scalling, Default Parameter
HyperParameter Tuning with Random Search CV and GridSearchCV Methods
Evaluation Model

Based on those steps, I use Decision Tree Classifier after Feature Selection, Scalling, HyperParameter tuning Data train 80 Test 20 for classification model to predict ewhich customers will churn or no Churn.


