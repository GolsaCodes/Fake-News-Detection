# Fake News Detection using Logistic Regression

A machine learning project for detecting whether a news article is **fake or real** using **Logistic Regression** and text-based features.

## Project Overview

The goal of this project is to build a binary text classification model that identifies fake news articles based on their textual content.

The project covers the complete machine learning workflow, including:

* Data cleaning and preprocessing
* Text feature extraction using TF-IDF
* Train/test splitting
* Logistic Regression model development
* Model evaluation using classification metrics

## Dataset

The project uses the **Fake News Detection Dataset (6000 News Articles)** from Kaggle.

**Dataset:** [Fake News Detection Dataset – Kaggle](https://www.kaggle.com/datasets/mobeenfatimah/fake-news-detection-dataset-6000-news-articles)

## Technologies & Libraries

* Python
* Pandas
* NumPy
* Scikit-learn

## Methodology

### 1. Data Preprocessing

The dataset was cleaned and prepared for text classification. This included handling the text data and preparing the input features and target labels.

### 2. Feature Extraction

**TF-IDF (Term Frequency–Inverse Document Frequency)** was used to convert the news text into numerical feature vectors suitable for machine learning.

### 3. Model

A **Logistic Regression** classifier was trained to distinguish between fake and real news articles.

### 4. Evaluation

The model was evaluated using:

* Accuracy
* Precision
* Recall
* F1
* Confusion Matrix

##  Results

The Logistic Regression model achieved an **accuracy of 97%** on the test set.
The confusion matrix, precision, and recall were also used to analyze the model's classification performance.
