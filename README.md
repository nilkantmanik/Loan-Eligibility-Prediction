
We will be using Python for this along with the below listed libraries.
Specifications
Python
pandas
seaborn
sklearn

For this problem, we have three CSV files: train, test and sample submission.
Train file will be used for training the model, i.e. our model will learn from this file. It contains all the independent variables and the target variable.
Test file contains all the independent variables, but not the target variable. We will apply the model to predict the target variable for the test data.
Sample submission file contains the format in which we have to submit out predictions

We can see there are three formats of data types:
object,int64,float64.
We have 614 rows and 13 columns in the train dataset.
We have 367 rows and 12 columns in test dataset.



Feature Engineering-Based on the domain knowledge, we can come up with new features that might affect the target variable. We will create the following three new features:
Total Income
EMI
Balance Income


After creating new features, we can continue the model building process. We will build the following models in this section.
Logistic Regression
Decision Tree
Random Forest
XGBoost


We have stored our results  in the comma separated values 
Different .csv files have been created to store the results 
# Loan Eligibililty Prediction
