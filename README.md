## Support Ticket Classification and Priority Prediction using NLP

## Project Overview

This project uses Natural Language Processing (NLP) and Machine Learning techniques to automatically classify customer support tickets and predict their priority levels. The goal is to reduce manual effort in support operations and improve ticket routing efficiency.

## Objectives

- Categorize support tickets into different ticket types.
- Predict ticket priority levels (Critical, High, Medium, Low).
- Automate support ticket management.
- Improve operational efficiency through NLP.

## Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-Learn
- TF-IDF Vectorization
- Bag of Words
- Logistic Regression
- Matplotlib
- Google Colab

## Dataset

Customer Support Ticket Dataset

The dataset contains customer support ticket descriptions along with ticket categories and priority labels.

## Workflow

## 1. Data Loading

Loaded and explored the support ticket dataset.

## 2. Text Preprocessing

- Lowercasing
- Punctuation removal
- Stopword removal
- Text cleaning

## 3. Feature Extraction

- TF-IDF Vectorization
- Bag of Words Representation

## 4. Ticket Category Classification

Built a Logistic Regression model to classify support tickets into categories such as:

- Billing Inquiry
- Cancellation Request
- Product Inquiry
- Refund Request
- Technical Issue

## 5. Priority Prediction

Built a separate Logistic Regression model to predict ticket priority:

- Critical
- High
- Medium
- Low

## 6. Model Evaluation

Evaluated models using:

- Accuracy Score
- Precision
- Recall
- F1 Score
- Confusion Matrix

## Results

## Ticket Category Classification

- Accuracy: 19.83%

## Priority Prediction

- Accuracy: 26.98%

## Sample Prediction

Input:
Customer cannot login and access account

Output:

- Category: Cancellation Request
- Priority: High

## Business Impact

- Faster ticket routing
- Automated prioritization
- Reduced manual workload
- Improved customer support efficiency
- Better resource allocation

## Future Improvements

- Implement advanced NLP models such as BERT
- Hyperparameter tuning
- Better feature engineering
- Larger and more diverse datasets
- Deep Learning based text classification

## Conclusion

This project demonstrates how NLP and Machine Learning can be applied to automate support ticket management by classifying ticket categories and predicting priority levels. Such systems can help organizations streamline customer support operations and improve response efficiency.
