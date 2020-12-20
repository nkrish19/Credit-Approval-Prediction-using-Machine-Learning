# Credit-Approval-Prediction-using-Machine-Learning
Problem statement, we decide whether or not to give the applicant loan/credit by classifying them into two classes; one that should be given the loan/credit and the other as a defaulter (who are not given a loan/credit). Build a machine learning model to predict and classify the applicant as one of the two categories.
We use past financial summary of the applicant and data submitted to predict the probability of future defaults and whether they are eligible for the same or not. We aim to minimize the number of loans given to high-risk applicants so that the bank can provide loans with minimal risk. 

We have written the program for all the models along with the graphs in MLProject.ipynb

Dataset: 

This contains all the datasets that were used for our project: 
1) application_record.csv 
2) credit_record.csv

To use the file, first, run all the import statements and then the data preprocessing
For our pre-processing, we are using standard scalar along with handling categorical data. 
Next pick any of the resampling techniques to initialize X_res, and Y_res.
Note: Weights is for no resampling
Next split the data into a training and testing set
Then choose a model and fit the training set over the model under the "Training the model" section
After that, run the "Performance" section to get the value of the model's various parameters.

Plots:
1) This folder contains ROC and correlation matrix for our best model Random Forest with random oversampling.
2) There are three tables for Nosampling, Oversampling, and undersampling. Each table has 4 columns the first column contains a different model under one pre-possessing technique( Nosampling, Oversampling, and undersampling), the Second column has precision for class 1, the third column has precision for class 0, and the final columns has the average/ mean precision.
3) Then there is a correlation matrix indicating the correlation between the features of the dataset.

Weights:

This folder has three sub-folders: Nosampling, Oversampling, and undersampling. 
Which further have weights of each classification algorithm used.
