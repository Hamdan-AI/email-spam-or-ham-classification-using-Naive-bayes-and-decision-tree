                                                  EMAIL SPAM OR HAM CLASSIFIER
OVERVIEW:

This repository contains a Python implementation of a machine learning model to classify emails as spam or ham (not spam). The model is built using various text processing and machine learning techniques to ensure high accuracy in distinguishing spam emails from legitimate ones.


FEATURES:
 
Data Preprocessing: Cleans and preprocesses the email content to make it suitable for model training.
   
Feature Engineering: Uses TF-IDF Vectorization to convert text data into numerical features.
   
Feature Selection: Applies the SelectKBest algorithm with the chi-squared statistic to select the most relevant features.
  

 MODEL TRAINING:

 Trains three different models:
                   Multinomial Naive Bayes,
                   Gaussian Naive Bayes and
                   Decision Tree (J48)


EVALUATION: 

Evaluates the performance of each model using accuracy, error rate, and classification metrics.

DEPENDENCIES/LIABRARIES:

numpy,
pandas,
scikit-learn,
nltk,
matplotlib
