# Sentiment Analysis of Reviews

This project demonstrates **Sentiment Analysis** of customer reviews using Natural Language Processing (NLP) techniques and Machine Learning.  
It is implemented in a Jupyter Notebook with **Python**, **NLTK**, and **scikit-learn**.

---

## Project Overview

The notebook walks through the following steps:

1. **Data Preprocessing**
   - Text cleaning (removing punctuation, numbers, and special characters).
   - Tokenization of reviews.
   - Stopword removal using **NLTK**.
   - Lemmatization with **WordNetLemmatizer**.

2. **Feature Extraction**
   - Converting text data into numerical vectors using **TF-IDF (Term Frequency–Inverse Document Frequency)**.

3. **Model Training**
   - Splitting dataset into training and testing sets.
   - Training a **Logistic Regression** model for sentiment classification.

4. **Evaluation**
   - Measuring performance using:
     - Accuracy score
     - Classification report (precision, recall, f1-score)
     - Confusion matrix visualization

5. **Model Saving**
   - Using **pickle** to save the trained model for future predictions.

---

## Requirements

- Python 3.8+
- Dependencies are listed in [requirements.txt](requirements.txt)

### Install dependencies
```bash
pip install -r requirements.txt
