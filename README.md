# Supervised-Machine-Learning - Predicting Credit Risk

A machine learning model that attempts to predict whether a loan from LendingClub will become high risk or not using Logistic Regression and Random Forest classifiers.

# Background
LendingClub is a peer-to-peer lending services company that allows individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market. LendingClub offers their previous data through an API.

Created machine learning models to classify the risk level of given loans using Logistic Regression model and Random Forest Classifier.


Preprocessing: Convert categorical data to numeric
Created a training set from the 2019 loans using pd.get_dummies() to convert the categorical data to numeric columns. Created a testing set from the 2020 loans, also using pd.get_dummies().

Fit a LogisticRegression model and RandomForestClassifier model
Created a LogisticRegression and RandomForestClassifier model, fit it to the data, and printed the model's score.

Which model performed better? How does that compare to your prediction? Write down your results and thoughts.

Revisit the Preprocessing: Scale the data
Used StandardScaler to scale the training and testing sets.

Before re-fitting the LogisticRegression and RandomForestClassifier models on the scaled data, make another prediction about how you think scaling will affect the accuracy of the models. Write your predictions down and provide justification.

Fit and score the LogisticRegression and RandomForestClassifier models on the scaled data.

Data Source
LendingClub (2019-2020) Loan Stats. Retrieved from: https://resources.lendingclub.com/
