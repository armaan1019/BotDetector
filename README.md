Bot Detector model

Technologies used:

1) Pandas
2) NumPy
3) matplotlib
4) sklearn

This application uses different technologies to examine data about twitter bots. The different steps of this application are:

1) Clean the data, by dropping columns
2) Create a plot comparing friends versus following counts of bots and nonbots
3) Examine profiles of nonbots by searching for certain bagwords which my indicate the user is a bot
4) Use DecisionTreeClassifier to use 30% of the data to train the model. Test the model on the rest of the data.
5) Perform LogisticRegression by feeding the training data to the model
6) The last part of the program creates two arrays X1s and X2s which are random numbers between 0 and 1. The output array is 1 if X1 + X2 is greater than 1, otherwise it's 0.
7) The dataset is used to train a decision tree classifier and a logistic regression models. Accuracy is computed and compared.

