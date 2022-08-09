# Santander_Customer_Satisfaction

### Task - 
Binary classification task to identify unsatisfied customers for a business. 

### Dataset Description - 
Used the kaggle data 'santander_customer_satisfaction' for this project. The shape of original train data is 76020 rows and 370 masked predictors whereas the shape of original test data is 75818 rows and 370 masked columns. The "TARGET" column is the variable to predict. It equals 1 for unsatisfied customers and 0 for satisfied customers.
##### Link to the dataset - https://www.kaggle.com/c/santander-customer-satisfaction/data

### Summary – 
As part of the final project of the AI-1 course at Univ.AI, we trained and tuned models like 
<ul>
<li>KNN,
<li>Logistic Regression, 
<li>Random Forest and
<li>XGBoost <br>
to predict whether the customer is satisfied or unsatisfied.  <br>
Before modelling, we pre-processed the data, did feature selection using feature engine library in python and resampled the data using SMOTE as the target class was highly imbalanced.
