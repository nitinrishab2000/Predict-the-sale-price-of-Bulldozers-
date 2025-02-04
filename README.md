Predicting the Sale Price of Bulldozers using Machine Learning
In this notebook we are going through an example of machine learning project with the goal of predicting sale price of bulldozers

1. Problem Defination
The goal is to predict predict the sale price of bulldozers and we are given its characteristics and its price from the past

2. Data
The data is taken from the kaggle from Blue Book for Bulldozers Competition : https://www.kaggle.com/competitions/bluebook-for-bulldozers/overview

There are three main datasets:

Train.csv is the training set, which contains data through the end of 2011.
Valid.csv is the validation set, which contains data from January 1, 2012 - April 30, 2012 You make predictions on this set throughout the majority of the competition. Your score on this set is used to create the public leaderboard.
Test.csv is the test set, which won't be released until the last week of the competition. It contains data from May 1, 2012 - November 2012. Your score on the test set determines your final rank for the competition
3. Evaluation
The evaluation metric for this projected is the RMSLE (root mean squared log error) between the actual and predicted auction prices.

Note: The goal of most regression problem is to minimise the error . As in this case the goal of this problem is to minimise the root mean squared log error(RMSLE)

4. Features
We can see all the features of data from the Data Dictionary provided by kaggle.
