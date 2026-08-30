# Sentiment-Analysis-Using-Python
# 🎬 Movie Sentiment Analysis using Machine Learning

A Machine Learning project that analyzes movie reviews and predicts whether the sentiment is **Positive** or **Negative**.

## 🚀 Project Overview

This project uses Natural Language Processing (NLP) and Machine Learning to perform sentiment analysis on movie reviews.

The model is trained using the **NLTK Movie Reviews dataset** and predicts the sentiment of custom movie review text.

## 🛠️ Technologies Used

- 🐍 Python
- 📊 Pandas
- 📚 NLTK
- 🤖 Scikit-learn
- 🔤 CountVectorizer
- 🧠 Multinomial Naive Bayes

## 📂 Dataset

The project uses the **NLTK Movie Reviews dataset**, which contains movie reviews categorized as:

- Positive
- Negative

## ⚙️ Project Workflow

1. Load the Movie Reviews dataset
2. Convert the dataset into a Pandas DataFrame
3. Convert text data into numerical features using CountVectorizer
4. Split the dataset into training and testing sets
5. Train the Multinomial Naive Bayes model
6. Evaluate the model using Accuracy Score
7. Generate a Classification Report
8. Predict sentiment for custom movie reviews

## 🤖 Machine Learning Model

The project uses:

### Multinomial Naive Bayes

Multinomial Naive Bayes is a popular machine learning algorithm used for text classification tasks such as:

- Sentiment Analysis
- Spam Detection
- Text Classification
- Document Classification

## 📊 Model Evaluation

The model is evaluated using:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Classification Report

## 🔮 Sample Predictions

The model can predict the sentiment of custom reviews.

Example:

```python
predict_sentiment("I absolutely loved this movie! It was fantastic.")