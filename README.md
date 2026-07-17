# Phishing Email Detection using Machine Learning

## Project Overview
Phishing emails are fraudulent messages designed to steal sensitive information such as usernames, passwords, and banking details. This project uses Machine Learning with Scikit-learn to classify emails as either **Phishing** or **Safe (Legitimate)** based on their textual content and URL-related features.

## Objectives
- Train a Machine Learning model using Scikit-learn.
- Extract email features using TF-IDF Vectorization.
- Detect phishing emails based on keywords and URLs.
- Display model accuracy.
- Generate a confusion matrix for evaluation.
- Predict whether a new email is phishing or safe.

## Features
- Email text preprocessing
- TF-IDF feature extraction
- URL detection
- Keyword analysis
- Multinomial Naive Bayes classifier
- Accuracy score
- Classification report
- Confusion matrix
- Predict custom email messages

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Dataset Format

The dataset should contain two columns:

| text | label |
|------|-------|
| Congratulations! Click here to claim your prize. | phishing |
| Meeting has been scheduled for tomorrow. | safe |

## Installation

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
