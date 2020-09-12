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

<img width="1680" alt="Screen Shot 2020-09-12 at 5 28 55 PM" src="https://user-images.githubusercontent.com/71173366/92993722-1813db80-f51e-11ea-8c9b-037c32e7e999.png">

# Dashboard

### I use Flask to create this dashboard. There are 5 pages:

# 1. Home

<img width="1664" alt="Screen Shot 2020-09-12 at 5 37 24 PM" src="https://user-images.githubusercontent.com/71173366/92993790-b2741f00-f51e-11ea-950b-87b88d909e02.png">

# 2. Dataset

<img width="1671" alt="Screen Shot 2020-09-12 at 5 39 53 PM" src="https://user-images.githubusercontent.com/71173366/92993832-0d0d7b00-f51f-11ea-84e9-4f5b7372a2a8.png">

# 3. Visualization

<img width="1646" alt="Screen Shot 2020-09-12 at 5 42 01 PM" src="https://user-images.githubusercontent.com/71173366/92993853-55c53400-f51f-11ea-9ca4-f26c79d6ac46.png">

# 4. Predict

<img width="1641" alt="Screen Shot 2020-09-12 at 5 43 55 PM" src="https://user-images.githubusercontent.com/71173366/92993871-93c25800-f51f-11ea-8c58-e6ee09d00bc7.png">

# 5. Result

<img width="1645" alt="Screen Shot 2020-09-12 at 5 45 15 PM" src="https://user-images.githubusercontent.com/71173366/92993896-c409f680-f51f-11ea-88ed-7f37a2404723.png">






