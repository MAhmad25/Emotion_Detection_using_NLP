# NLP Sentiment Analysis Project

## Project Overview

This project builds a text classification pipeline for emotion detection using NLP techniques. The workflow includes data loading, preprocessing, feature extraction, model training, and evaluation.

## What Was Done

- Loaded the dataset from `train.txt`.
- Cleaned and preprocessed text data.
- Converted emotion labels to numeric values.
- Vectorized text using Bag-of-Words and TF-IDF.
- Trained and evaluated multiple classification models.

## Data Files

- `train.txt`: Training dataset containing text and emotion labels.
- `test.txt`: Optional test data file for further evaluation.
- `val.txt`: Optional validation data file for model tuning.

## Preprocessing Steps

- Lowercased all text.
- Removed URLs.
- Removed digits.
- Removed emojis.
- Removed punctuation.
- Removed stop words.

## Models Evaluated

- Multinomial Naive Bayes
- Logistic Regression
- Support Vector Machine (SVM)

## Results

The models were evaluated using:

- Accuracy
- Precision
- Recall

## Summary Table

| Step           | Description                                                          |
| -------------- | -------------------------------------------------------------------- |
| Data Loading   | Read `train.txt` with text and emotion labels.                       |
| Label Encoding | Mapped emotion labels to integer values.                             |
| Text Cleaning  | Lowercase, remove URLs, digits, emojis, punctuation, and stop words. |
| Vectorization  | Converted text into numeric features using Bag-of-Words and TF-IDF.  |
| Model Training | Trained Naive Bayes, Logistic Regression, and SVM models.            |
| Evaluation     | Compared models using accuracy, precision, and recall.               |

## Notes

This project focuses on text preprocessing and classification for emotion detection. The notebook includes the full pipeline for preparing the data and evaluating models.
