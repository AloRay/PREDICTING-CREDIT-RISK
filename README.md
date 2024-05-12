# Predicting Credit Risk

This is a machine learning model that attempts to predict whether a loan from LendingClub will become high risk or not using Logistic Regression and Random Forest classifiers.
LendingClub is a peer-to-peer lending services company that allows individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market. They offer their previous data through an API.
Logistic Regression model and Random Forest Classifier are used to create machine learning models to classify the risk level of given loans.


# Limitations
CSVs have been undersampled to give an even number of high risk and low risk loans. In the original dataset, only 2.2% of loans are categorized as high risk.


Converted categorical data to numeric
Created a training set from the 2019 loans using pd.get_dummies() to convert the categorical data to numeric columns. Created a testing set from the 2020 loans, also using pd.get_dummies().
Created a LogisticRegression and RandomForestClassifier model, fit it to the data, and printed the model's score.
Revisit the Preprocessing: Scale the data
Used StandardScaler to scale the training and testing sets.
Fit and score the LogisticRegression and RandomForestClassifier models on the scaled data.
