# Spam Message Classifier

A text classification model built with scikit-learn to detect spam SMS messages using Naive Bayes.

## Overview
This project classifies SMS text messages as **spam** or **ham** (not spam) by converting message text into numeric features and training a Multinomial Naive Bayes classifier on labeled data.

## Results
- Test accuracy: 99.19%

## Tech used
Python, scikit-learn, Pandas, Google Colab

## How it works
1. Loaded a labeled dataset of SMS messages (spam/ham)
2. Converted message text into numeric features using `CountVectorizer`
3. Trained a Multinomial Naive Bayes classifier
4. Evaluated performance on a held-out test set
