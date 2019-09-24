WINE DATASET

This dataset is also available from the UCI machine learning repository, https://archive.ics.uci.edu/ml/datasets/wine+quality , I just shared it to github for convenience.

In this dataset we have to predict whether the quality of the Red Wine is good or bad using various parameters. It is said that the Wine is good when the quality of wine is more than 7.

Here the predictions are not probabilistic so, we are not using Logistic regression or Naive bayes.

I am not using KNN because the number of dataset is high and it takes less data for prediction.

It's better to use SVM or Random forest. But i am ignoring random forest because it takes more time to predict when compared with SVM. SVM works best when you have two categories, so i am using it here.

I am including a new column in dataset to get the rating of wine.0- means Bad wine, 1- means Good wine.


