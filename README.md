# Sentiment Analysis on IMDB Movie Reviews

This project performs **Sentiment Analysis** on the **IMDB Movie Reviews Dataset** using Natural Language Processing (NLP) techniques. The goal is to classify movie reviews as either **positive** or **negative** based on their text content.

---

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Steps](#steps)
4. [Results](#results)
5. [Requirements](#requirements)
6. [How to Run](#how-to-run)
7. [License](#license)

---

## Project Overview
Sentiment analysis is a common NLP task that involves classifying text into positive or negative sentiments. In this project, we:
- Preprocess the text data (cleaning, tokenization, stopword removal).
- Convert text into numerical features using **CountVectorizer**.
- Train a **Naive Bayes classifier** to predict sentiment.
- Evaluate the model using accuracy, confusion matrix, and classification report.

---

## Dataset
The dataset used in this project is the **IMDB Movie Reviews Dataset**, which contains 50,000 movie reviews labeled as either **positive** or **negative**.

- **Source:** [IMDB Dataset on Kaggle](https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
- **File:** `IMDB Dataset.csv`
- **Columns:**
  - `review`: Text of the movie review.
  - `sentiment`: Sentiment label (`positive` or `negative`).

---

## Steps
1. **Data Loading and Exploration:**
   - Load the dataset and explore its structure.
   - Check for missing values and class distribution.

2. **Text Preprocessing:**
   - Convert text to lowercase.
   - Remove punctuation, numbers, and stopwords.
   - Tokenize the text.

3. **Text Vectorization:**
   - Use **CountVectorizer** to convert text into numerical features.

4. **Model Training:**
   - Split the data into training and testing sets.
   - Train a **Naive Bayes classifier**.

5. **Model Evaluation:**
   - Evaluate the model using accuracy, confusion matrix, and classification report.

6. **Visualization:**
   - Plot the confusion matrix to visualize model performance.

---

## Results
- **Accuracy:** 85.5%
- **Precision (Positive):** 86%
- **Recall (Positive):** 85%
- **Confusion Matrix:**
