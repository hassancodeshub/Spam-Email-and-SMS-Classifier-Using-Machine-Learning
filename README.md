# Spam Email and SMS Classifier Using Machine Learning

## Overview
This project uses machine learning and Natural Language Processing (NLP) techniques to classify text messages as spam or legitimate (ham).

## Objectives
- Identify unwanted spam messages automatically.
- Preprocess text data for machine learning.
- Train a classification model using Naive Bayes.
- Evaluate performance using standard classification metrics.

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- Scikit-learn
- Matplotlib

## Dataset
The project uses the UCI SMS Spam Collection dataset, containing labeled spam and legitimate messages.

Dataset: https://archive.ics.uci.edu/dataset/228/sms+spam+collection

## Algorithm
1. Load and clean the dataset.
2. Convert text into numerical features using TF-IDF.
3. Split the dataset into training and testing sets.
4. Train a Multinomial Naive Bayes classifier.
5. Evaluate predictions using accuracy, precision, recall, F1-score, and a confusion matrix.

## Installation
Install the required libraries:

```bash
pip install pandas scikit-learn matplotlib joblib
```

## How to Run
1. Open `01_spam_email_classifier.ipynb` in Jupyter Notebook.
2. Run each cell from top to bottom.
3. Allow the notebook to download the dataset.
4. Review the evaluation results and test custom messages.

## Expected Outcome
The trained model predicts whether a new text message is spam or legitimate.

## Limitations
The dataset primarily contains SMS messages. Performance on other types of emails or newer spam patterns may vary.

## Author
Add your name here.
