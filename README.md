# Fake News Prediction 📰
## Overview

Fake news has become a major concern in today’s digital age, spreading misinformation and influencing public opinion.
This project uses Machine Learning (Logistic Regression, Passive Aggressive Classifier, etc.) to classify news articles as Real or Fake based on their content.

Dataset

Source: [Fake News Dataset – Kaggle]

## Features:

Title of news

Author

Text (main body of the article)

Target Variable:

0 → Fake News

1 → Real News

## Workflow

Import libraries & load dataset

Data preprocessing

Handling null/missing values

Text cleaning & normalization

Convert text into numerical representation using TF-IDF Vectorizer

Train-test split

Train models (Logistic Regression, Passive Aggressive Classifier, etc.)

Evaluate model performance using accuracy, precision, recall, F1-score

Compare models and select the best one

## Tech Stack

Language: Python

Libraries:

numpy, pandas → data handling

scikit-learn → ML models, preprocessing, evaluation

nltk → natural language processing (tokenization, stopwords removal)

matplotlib, seaborn → visualization

## Results

Best performing model: Logistic Regression

Achieved accuracy: ~[fill with your model accuracy from notebook]


## Future Improvements

Try advanced NLP models like LSTM, GRU, or BERT

Improve preprocessing with lemmatization & advanced text cleaning

Deploy as a Streamlit/Flask web app for real-time detection

Integrate with a browser extension for real-world usage

## Acknowledgements

Dataset: Kaggle

Libraries: Scikit-learn, NLTK
