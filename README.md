# Product_Rating_wish_products-

Data Set Description: The data is from Wish.com and the task is to predict the rating of the product based on the features. It is a supervised learning problem where we have a labelled data availabel to train our different models.

The data is imported from Google Drive using pandas library.
seaborn and matplotlib libraries are used to plot the data.
The first step of the task is to do perform the data exploration which includes checking any anamalies, get general idea about useful features and plotting distributions.
Data Cleaning/Preprocessing:

After the initial exploration analysis, the next step is to clean the data to make it ready for any type of model classification/prediction. The steps include removing NaN, deleting random data, normalizing, generalizing etc.
Model Building:

The next step is to build a model for our analysis and checking its accuracy and other metrices.
Models

Linear Regression: Initially I thought it to be a regression problem and did analysis using Linear Regression from scikit library.
Logistic Regression: After realizing it is more of a classification problem, I started with the basic logistic regression and changed parameters to get good f1-score.
SGD Classifier: Stochastic Gradient descent is a good classifier but it does not give good accuracy for the data set available.
Deep Neural Network: I tried building neural network with 2,3,4 hidden layers but didn't get enough accuracy to use it for classification.
Decisoion Tree: Decision Tree gave good f1 score and I tried enough parameter tuning to get a higher accuracy/f1-score.
Random Forest: After realising that decision tree are good classifier, I go with ensemble method mainly Random forest and find the best f1-score for the data available both for validation data-set and test data set available on Kaggle.
