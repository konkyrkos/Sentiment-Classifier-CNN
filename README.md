# Sentiment-Classifier-RNN
This repository provides my solution for the 4th Assignment for the course of Text Analytics for the MSc in Data Science at Athens University of Economics and Business.

Practically it is the natural development of the Sentiment Classifier using MLPs project.
The change from last time is that this project uses bi-directional Recursive Neural Networks (RNNs) implemented in Keras, Tensorflow.

All hyper parameters are tuned on the development subset of the dataset.

More classifiers are used, in order to use them as baseline and comparison to the model created.

## Model Metrics

Precision, recall, F1 scores for each class and classifier, using a classification threshold t = 0.5 for each class, computed on the training, development, and test
subsets.

## Model Macro-Metrics

Macro-averaged precision, recall, F1 scores for each classifier, again using a classification threshold t = 0.5 for each class, computed on the training, development,
and test subsets.

## Statistical significance tests

Bootstrap statistical significance tests to check if the difference between the test macro-averaged F1 of the best (in terms of test macro-averaged F1) classifier and the
test macro-averaged F1 of each other classifier (or baseline) experimented with (p-value < 0.01).

## Precision-recall curves

Precision-recall curves curves using macro-averaged precision and recall, computed on the test subset.Corresponding AUC.

## Statistics - Preprocessing

Statistics about the datasets (e.g., average document length, number of training/dev/test documents, vocabulary size) and preprocessing on the dataset.
