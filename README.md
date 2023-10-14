## Predicting Sale Prices of Bulldozers using Machine Learning

### Problem definition
How well can we predict the future prices of bulldozers given their characteristics and previous prices.
### Goal is to find a machine learning model which minimized RMSLE
### Data
The data is downloaded from the Kaggle Bluebook for Bulldozers competition.
https://www.kaggle.com/c/bluebook-for-bulldozers/overview/description

The data for this competition is split into three parts:

>Train.csv is the training set, which contains data through the end of 2011.

>Valid.csv is the validation set, which contains data from January 1, 2012 - April 30, 2012 You make predictions on this set throughout the majority of the competition. Your score on this set is used to create the public leaderboard.

>Test.csv is the test set, which won't be released until the last week of the competition. It contains data from May 1, 2012 - November 2012. Your score on the test set determines your final rank for the competition.
### Evaluation
The evaluation metric for this competition is the RMSLE (root mean squared log error) between the actual and predicted auction prices.
### Features
Kaggle provides a dictionary detailing all the features.
