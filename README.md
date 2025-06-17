
# Spam Detection using Logistic Regression and Naïve Bayes

This project implements a spam detection pipeline using traditional machine learning techniques and NLP preprocessing.

## Features
- Data cleaning (regex, tokenization, lemmatization, stop-word removal)
- Feature extraction using TF-IDF (unigrams and bigrams)
- Classifiers: Multinomial Naïve Bayes, Logistic Regression
- Hyperparameter tuning with GridSearchCV
- Data augmentation via random deletion
- Evaluation using accuracy, precision, recall, F1-score, and confusion matrix

## Dataset
- 3619 labeled emails for training
- 1552 unlabeled emails for testing

## Results
- Logistic Regression achieved 98.6% accuracy on hold-out data
- After augmentation, model performance improved to 100% on hold-out

## How to Run
Open the `task_1_final.ipynb` notebook and run all cells in order. Make sure to have the required data files and packages (NLTK, scikit-learn, pandas, etc.).

## Requirements
```bash
pip install numpy pandas scikit-learn nltk matplotlib
```

## Author
[Your Name]
