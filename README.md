# Fake-News-Detection-Using-Machine-Learning
The dataset contains news articles labeled as real or fake. It includes fields like title, text, and label. This data helps train models to classify news authenticity and combat misinformation by detecting patterns typical of fake vs real news.

This dataset is designed for binary classification of news articles into two categories: real and fake. It consists of four columns: title, text, subject, and date, where each row represents a distinct news article. The text and title fields contain the main content and headline of the news, while the subject field categorizes the type (e.g., politics, world news), and the date field provides the publication date.

The primary use case of this dataset is in building machine learning models for fake news detection. By analyzing textual patterns, writing styles, and contextual information, models can be trained to distinguish between legitimate and deceptive news. This dataset is crucial in the current era of widespread misinformation, empowering AI to assist in content verification and digital literacy.



## Dataset Description
The dataset contains labeled news articles with the following features:

| Column   | Description |
|----------|-------------|
| `title`  | Headline of the news article |
| `text`   | Full content of the article |
| `label`  | Target variable: `0` = Fake, `1` = Real |

**Source**: Kaggle / Academic Research  
**Size**: ~6,000+ articles  
**Type**: Binary Classification

## Problem Statement
Build a supervised machine learning model that can detect fake news using text classification techniques such as **TF-IDF** vectorization and algorithms like **Logistic Regression**, **Naive Bayes**, or **Random Forest**.

## Models Used
- TF-IDF Vectorizer for text preprocessing
- Logistic Regression (Primary Model)

## Evaluation Metrics
- Accuracy
- Model Building
