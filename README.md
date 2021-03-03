# Salary Prediction

Kaggle has hosted an open data scientist competition in 2018 titled “2018 Kaggle ML & DS Survey Challenge.” The purpose of this challenge was to “tell a data story about a subset of the data science community represented in this survey, through a combination of both narrative text and data exploration.”

The dataset provided (mutiplechoiceResponses.csv) contains the survey results provided by Kaggle. The survey results from 23860 participants are shown in 395 columns, representing survey questions. Not all questions are answered by each participant, and responses contain various data types

  ## Steps followed
    1. Import required libraries and create a dataframe of the CSV file
    2. Identify feature and target variables, perform data cleaning by removing information that is not relevant to our study, implement feature engineering 
    3. Perform analysis on the cleaned data using correlation, trends, statistical mean, deviations etc. to derive insights
    4. Perform feature selection using tools like Lasso regularization, random forest classifier and select important features
    5. Train a multi-class logistic regression model with K fold cross validation, check for accuracy and perform hyperparameter tuning to improve the model accuracy
    6. Check for the model performance on the test data
