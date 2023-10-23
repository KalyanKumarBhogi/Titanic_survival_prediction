# Titanic_survival_prediction
The aim is to make predictions on the survival outcome of passengers. Since this is a binary classification, logistic regression can be used to build the model.

Data Source: Kaggle.com (https://www.kaggle.com/c/titanic/data)

Python Libraries used
NumPy
Pandas
Matplotib
Seaborn
from sklearn.model_selection import train_test_split
from sklearn import metrics
Pre-processing operations

Checking for missing values in the dataset
Dropping unnecessary columns
Creating a categorical variable for traveling alone
Label Encoding

Exploratory Data Analysis
Dataset shape
Dataset info
Dataset description
Analysis of all the features in the dataset
Model Building: Logistic Regression

Model Evaluation
Confusion matrix
Classification report
