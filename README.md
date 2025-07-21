# Customer Support Ticket Classification & Analytics

This repository provides a complete workflow for **analyzing, preprocessing, and classifying customer support tickets** using Python and machine learning. It focuses on transforming raw support requests into actionable insights, with end-to-end code for data cleaning, feature engineering, visualization, and predictive modeling.

---

## Overview

The notebook guides you through handling customer support ticket data, cleaning textual and categorical information, extracting features, visualizing key attributes, and training models to predict both issue type and urgency level. It is suitable for data scientists, ML engineers, and business analysts looking to automate support ticket triage and reporting.

---

## Key Features

- **Data Import & Exploration**
  - Load Excel datasets, inspect missing values, and get a snapshot of raw tickets.
- **Text Preprocessing**
  - Clean text using tokenization, stopword removal, and lemmatization (NLTK, spaCy).
  - Handle missing values in text and categories robustly.
- **Feature Engineering**
  - Vectorize ticket text with TF-IDF.
  - Generate features: text length, sentiment score, urgency keyword detection.
  - Combine sparse and dense features for enhanced modeling.
- **Data Visualization**
  - Plot urgency distribution and other insights to understand data characteristics.
- **Modeling & Prediction**
  - Train machine learning models—Logistic Regression, SVM, Random Forest, Naive Bayes—for ticket classification.
  - Predict both issue type and urgency level.
- **Evaluation**
  - Report accuracy and detailed classification metrics for model assessment.

---

## Example Use Cases

- **Automated Ticket Triage**: Predict issue type and urgency to route tickets faster.
- **Operational Analytics**: Visualize trends in support requests and urgent cases.
- **Sentiment Tracking**: Monitor customer sentiment to flag dissatisfied users.

---

## Dependencies

- `pandas`, `numpy`
- `scikit-learn`
- `nltk`, `spacy`, `textblob`
- `matplotlib`
- `scipy`

Install them via:

