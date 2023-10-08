# Spam-mail-detection

This is a spam mail detection system implemented using Python and scikit-learn. It classifies emails as either "spam" or "ham" (non-spam) based on their content.

## Table of Contents

- [Project Overview]
- [Dataset]
- [Usage]
- [Machine Learning Models]
- [Evaluation]
- [ROC Curve]

  
## Project Overview

Spam mail is a common issue in email communication. This project aims to detect spam emails using machine learning techniques. It includes the following components:

- Data preprocessing
- TF-IDF feature extraction
- Multinomial Naive Bayes classification
- Logistic Regression classification
- Random Forest classification
- ROC curve analysis

## Dataset

The dataset used in this project contains a collection of emails with labels indicating whether each email is spam or not. The dataset has been preprocessed to remove duplicates and null values. This dataset has been collected from a reliable source called kaggle.

## Usage

1. Install the required dependencies: "pip install pandas numpy scikit-learn matplotlib"

2. Then use google colab to train and evaluate the spam mail detection system.

<font size="5">**Machine Learning Models**</font>

Multinomial Naive Bayes
Classification accuracy on the training data: 98.01%
Classification accuracy on the test data: 96.03%
Logistic Regression
Classification accuracy on the training data: 96.19%
Classification accuracy on the test data: 95.45%
Random Forest
Classification accuracy on the training data: 100%
Classification accuracy on the test data: 97.19%
Evaluation
Precision, recall, and F1-score metrics are reported for each classification model.
Confusion matrices are provided for both training and test data.
ROC curve analysis is conducted to evaluate model performance.
