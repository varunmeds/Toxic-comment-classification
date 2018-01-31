# Toxic-comment-classification
Kaggle competition based on toxic comment classification

Problem as defined on Kaggle : 
------------------------------
You are provided with a large number of Wikipedia comments which have been labeled by human raters for toxic behavior. The types of toxicity are:

toxic
severe_toxic
obscene
threat
insult
identity_hate
You must create a model which predicts a probability of each type of toxicity for each comment.

File descriptions
train.csv - the training set, contains comments with their binary labels
test.csv - the test set, you must predict the toxicity probabilities for these comments. To deter hand labeling, the test set contains some comments which are not included in scoring.
sample_submission.csv - a sample submission file in the correct format

Notes on training data
-----------------------

1. Lots of misclassified text
2. Presence of random stop words, special characters, spaces, Dates, Numbers
3. Treat it as multiclass

Possible Methodology to follow
--------------------------------

1. Write a code to clean the data up. Should check for loss of any valuable data with regards to this. Identify the number of empty comments that have been classified as toxic or even classified in general.
2. Previous work experience on a similar problem used Multiclass SVM - Bag of words model.
3. Use of LDA. Research underway.


