# Fake News Detection using Logistic Regression

A machine learning project for detecting whether a news article is **fake or real** using **Logistic Regression** and text-based features.

## Repository Structure

```text
Fake-News-Detection/
├── logistic_regression.ipynb
├── news_dataset.csv
└── README.md
```

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

The Logistic Regression model was evaluated on the test set using the following metrics:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

#### Results
**Classification Report:**

| Class | Precision | Recall | F1-score | Support |
|:---:|:---:|:---:|:---:|:---:|
| 0 | 0.98 | 0.96 | 0.97 | 614 |
| 1 | 0.96 | 0.98 | 0.97 | 586 |
| **Macro Avg** | **0.97** | **0.97** | **0.97** | **1200** |
| **Weighted Avg** | **0.97** | **0.97** | **0.97** | **1200** |

**Overall Accuracy:** 0.9725

#### Confusion Matrix

| | Predicted 0 | Predicted 1 |
|:---:|:---:|:---:|
| **Actual 0** | 591 (TN) | 23 (FP) |
| **Actual 1** | 10 (FN) | 576 (TP) |

Overall, the results indicate that the Logistic Regression model achieves high accuracy and balanced performance across both classes.
