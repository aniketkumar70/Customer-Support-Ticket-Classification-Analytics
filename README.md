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

---

## How to Use

1. **Clone the Repository**  
   `git clone <repo-url> && cd <repo-dir>`
2. **Open the Notebook**  
   Launch `main.ipynb` in Jupyter or Google Colab.
3. **Prepare Your Data**  
   Ensure your Excel file follows the required format (`ticket_id`, `ticket_text`, `issue_type`, `urgency_level`, `product`).
4. **Run the Workflow**  
   Execute each notebook step—data cleaning, preprocessing, modeling, and evaluation.
5. **Interpret Results**  
   Assess classification metrics and adjust the workflow for your support data.

---

## Customization

- **Add more features**: Integrate custom keywords, product-specific logic, or external data.
- **Tune models**: Experiment with different algorithms and hyperparameters.
- **Extend visualizations**: Build additional charts for deeper operational insights.

---

## Limitations

- Model assumes English-language inputs and predefined label sets.
- Initial file input expects a specific column structure—adapt code as needed for different schemas.
- Not optimized for real-time deployment (batch analytics focus).

---



