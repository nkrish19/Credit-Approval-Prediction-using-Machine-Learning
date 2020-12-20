# Credit-Approval-Prediction-using-Machine-Learning
Using various Machine Learning techniques to classify applicants into two categories: Those who are eligible for credit, and those who are not.
We have written the program for all the models along with the graphs in MLProject.ipynb

Dataset folder contains all the datasets that were used for our project: 1) application_record.csv, 2) credit_record.csv. 

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
