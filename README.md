# Shinkansen-Travel-Experience-Hackathon
Shinkansen Travel Experience Hackathon solutions and data handling

# Project Objective
The goal of this project is to find the best model to predict costumer satisfaction on the Shinkansen Bullet Train.

# Data
The problem consists of 2 separate datasets: Travel data & Survey data. Travel data has information related to passengers and attributes related to the Shinkansen train, in which they traveled. The survey data is aggregated data of surveys indicating the post-service experience. You are expected to treat both these datasets as raw data and perform any necessary data cleaning/validation steps as required.

The data has been split into two groups and provided in the Dataset folder. The folder contains both train and test data separately.

Train_Data
Test_Data

Target Variable: Overall_Experience (1 represents ‘satisfied’, and 0 represents ‘not satisfied’)

The training set can be used to build your machine-learning model. The training set has labels for the target column - Overall_Experience.

The testing set should be used to see how well your model performs on unseen data. For the test set, it is expected to predict the ‘Overall_Experience’ level for each participant.

# Evaluation Criteria:

The evaluation metric is simply the percentage of predictions made by the model that turned out to be correct. This is also called the accuracy of the model. It will be calculated as the total number of correct predictions (True Positives + True Negatives) divided by the total number of observations in the dataset.

# Output file
The output file is a CSV file with the predicted results for each model. The CVS contains ID numbers and a column with satisfaction prediction values (0 - Not satisfied / 1 - satisfied)

# User notes
Results shows XGboost to be the best model, yet accuracy could be improved with different data handling and hyperparameters. Running a grid search is reccomended fot each model.
