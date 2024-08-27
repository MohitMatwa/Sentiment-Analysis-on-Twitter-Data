# Tweet Sentiment Analysis

## Overview
This repository contains a project focused on performing sentiment analysis on tweets. The goal is to classify tweets into positive, negative, or neutral categories using machine learning models.

## Project Goal
The main objective of this project is to develop models that can accurately predict the sentiment of tweets. Sentiment analysis is a valuable tool in various domains, including social media monitoring, customer feedback analysis, and market research.

## How It Works
### 1. Data Preprocessing
- **Text Cleaning**: The tweets are cleaned by removing stopwords, special characters, and irrelevant content.
- **Tokenization**: The cleaned text is broken down into individual words (tokens).
- **Vectorization**: The text is converted into numerical features using the `CountVectorizer` method, which creates a matrix of token counts.

### 2. Model Training
Two machine learning models are used to classify the sentiment of tweets:
- **Naive Bayes (MultinomialNB)**: A probabilistic model commonly used for text classification tasks.
- **Support Vector Machine (SVM)**: A robust classifier that works well for both linear and non-linear data.

### 3. Model Evaluation
The performance of the models is evaluated using accuracy scores and confusion matrices. These metrics help in comparing the effectiveness of the Naive Bayes and SVM models in predicting the sentiment of tweets.

## Models Used
- **Naive Bayes (MultinomialNB)**: Trained on tokenized and vectorized tweet data.
- **Support Vector Machine (SVM)**: Trained using the same dataset for performance comparison.

## Results
The project includes an evaluation of the models based on their accuracy and confusion matrices. These results are used to determine the most effective model for sentiment analysis.

## Conclusion
This project demonstrates the process of building and evaluating machine learning models for sentiment analysis on tweets. By preprocessing the text data and training Naive Bayes and SVM models, we can classify tweets into positive, negative, or neutral sentiments with a accuracy of 0.85.
