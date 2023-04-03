# Course

CIND820 XJH - Big Data Analytics Project - W2023

## Author

Dorothy Lo

## Repository

The code for this project can be found at: https://github.com/dorothylo/CIND820.git

## Programming language 

Python

## Credit Card Approval Data Analysis


### Q1: What exploratory data analysis and preprocessing techniques are necessary to prepare the dataset for modeling?

To prepare the credit card approval dataset for modeling, the following exploratory data analysis and preprocessing techniques were applied:

    1. Used ProfileReport for EDA
    2. Visualized the customer status
    3. Created the dependent variable
    4. Merged the datasets
    5. Dealt with missing values
    6. Changed the days into years
    7. Adjusted datatypes
    8. Applied encoding for categorical features
    9. Dealt with imbalance dataset
    10. Stardarized data
    11. Identified and handle outliers

### Q2: Which features are influential predictors for classifying credit card approval data?

To determine the influential predictors for classifying credit card approval data, the following feature selection techniques were applied:
    
    1. Applied filter method by f-value using feature extraction
    2. Summarized score and selected features
    3. Applied wrapper method by Recursive Feature Elimination (RFE)
    4. Used the extra trees forest method for feature selection analysis

### Q3: How does Logistic Regression perform for credit card approval classification compared to other techniques in terms of effectiveness, efficiency, and stability?

To compare the performance of Logistic Regression with other techniques for credit card approval classification in terms of effectiveness, efficiency, and stability, the following steps were taken:

    1. Splitted dataset into train and test sets
    2. Built models: SVM, Random Forest, Logistic Regression, KNN, and Decision Tree
    3. Compared models using evaluation metrics: accuracy, precision, recall, f1, and auc
    4. Model tuning - Used RandomSearchCV and Repeated Stratified K-fold for best parameters 

