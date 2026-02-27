# Fake News Detection (TF-IDF + ML)

## Overview
Text classification project to predict whether a news article is FAKE or REAL.

## Methods
- Text cleaning with regex
- TF-IDF (unigrams + bigrams)
- Models: Logistic Regression, Multinomial Naive Bayes
- Evaluation: accuracy + precision/recall/F1 + confusion matrix
- Model interpretation: top weighted terms for each class

## Results
Logistic Regression achieved ~99% accuracy on a held-out test split (80/20, stratified, random_state=42). Naive Bayes achieved ~95%.

## How to run
This project was developed in Google Colab.
1. Open the notebook/script in Colab
2. Upload `Fake.csv` and `True.csv` when prompted (Kaggle Fake/Real News dataset)
