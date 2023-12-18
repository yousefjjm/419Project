# 419Project
# NLP and Machine Learning Techniques in Python

## Introduction
This project explores various natural language processing (NLP) and machine learning techniques using Python. It focuses on implementing and comparing different NLP models and algorithms using the `sklearn` and other libraries, such as `Panda`, `PyTorch`, etc. Also, there is an attempt at an RNN network at the bottom.

## Installation
you can install Juypter Lab into your system, or you can simply use Google Collab (with Collab you do not have to manually install the libraries)

the libraries are:

nltk and its submodules (nltk.corpus, nltk.tokenize) - Natural Language Toolkit.
pandas - Data manipulation and analysis library.
re - Regular expression operations.
sklearn with specific submodules:
sklearn.ensemble
sklearn.linear_model
sklearn.metrics
sklearn.model_selection
sklearn.naive_bayes
sklearn.neighbors
sklearn.svm - These are various components of the scikit-learn library for machine learning.

time - Time access and conversions.
torch and torchtext.vocab - PyTorch and its vocabulary module, used in deep learning and NLP.

## Abstract
Efficient data preparation is crucial in machine learning applications, particularly in natural language processing (NLP). This project focuses on comprehensive data curation through lowercasing, punctuation removal, tokenization, and stop-word elimination to enhance the quality of reviews. The subsequent analysis delves into the implementation of Bag-of-Words, N-Grams, RNN, and TF-IDF as feature extraction methods, with a detailed code overview. The comparison reveals that TF-IDF and Bag-of-Words emerge as the most effective techniques based on accuracy and time. The study concludes with the remaining work outlined, emphasizing code implementation, validation, testing, result comparison, and the final report and presentation.

##Sample Results
I will be showcasing a sample result of Bag of Words:

Model: Logistic Regression
Elapsed Time: 6.15 seconds
BoW Accuracy: 0.88465
Classification Report:
               precision    recall  f1-score   support

    negative       0.89      0.88      0.88      9989
    positive       0.88      0.89      0.89     10011

    accuracy                           0.88     20000
   macro avg       0.88      0.88      0.88     20000
weighted avg       0.88      0.88      0.88     20000

--------------------------------------------------
Model: Naive Bayes
Elapsed Time: 0.06 seconds
BoW Accuracy: 0.86035
Classification Report:
               precision    recall  f1-score   support

    negative       0.85      0.87      0.86      9989
    positive       0.87      0.85      0.86     10011

    accuracy                           0.86     20000
   macro avg       0.86      0.86      0.86     20000
weighted avg       0.86      0.86      0.86     20000

--------------------------------------------------
Model: Random Forest
Elapsed Time: 135.98 seconds
BoW Accuracy: 0.8577
Classification Report:
               precision    recall  f1-score   support

    negative       0.86      0.86      0.86      9989
    positive       0.86      0.86      0.86     10011

    accuracy                           0.86     20000
   macro avg       0.86      0.86      0.86     20000
weighted avg       0.86      0.86      0.86     20000

--------------------------------------------------
Model: Ridge classifier
Elapsed Time: 38.18 seconds
BoW Accuracy: 0.8033
Classification Report:
               precision    recall  f1-score   support

    negative       0.81      0.80      0.80      9989
    positive       0.80      0.81      0.80     10011

    accuracy                           0.80     20000
   macro avg       0.80      0.80      0.80     20000
weighted avg       0.80      0.80      0.80     20000

--------------------------------------------------
Model: SGDClassifier
Elapsed Time: 0.35 seconds
BoW Accuracy: 0.8748
Classification Report:
               precision    recall  f1-score   support

    negative       0.88      0.87      0.87      9989
    positive       0.87      0.88      0.88     10011

    accuracy                           0.87     20000
   macro avg       0.87      0.87      0.87     20000
weighted avg       0.87      0.87      0.87     20000

--------------------------------------------------



