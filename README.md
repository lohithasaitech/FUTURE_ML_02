## Support Ticket Classification and Priority Prediction using NLP

## Project Overview

This project uses Natural Language Processing (NLP) and Machine Learning to automatically classify customer support tickets and predict their priority levels.

The system analyzes ticket descriptions, categorizes them into ticket types, and predicts whether a ticket should be assigned High, Medium, or Low priority. This helps support teams reduce manual effort and improve response efficiency.

---

## Objectives

- Automatically classify support tickets into categories.
- Predict ticket priority levels.
- Reduce manual ticket sorting effort.
- Improve support team productivity.

---

## Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-Learn
- TF-IDF Vectorization
- Bag of Words (Count Vectorizer)
- Logistic Regression
- Matplotlib
- Google Colab

---

## Dataset

Customer Support Ticket Dataset (Kaggle)

The dataset contains customer support ticket information including:

- Ticket Description
- Ticket Type
- Ticket Priority
- Customer Information
- Resolution Details

---

## Project Workflow

1. Data Loading

The dataset is loaded from a CSV file into a Pandas DataFrame.

2. Text Preprocessing

Text cleaning includes:

- Lowercasing
- Stopword Removal
- Punctuation Removal
- Special Character Removal

3. Feature Extraction

Two NLP feature extraction techniques were implemented:

TF-IDF Vectorization

Converts ticket descriptions into weighted numerical features.

Bag of Words

Converts text into word-frequency vectors.

4. Ticket Category Classification

A Logistic Regression model is trained using ticket descriptions to predict ticket categories such as:

- Technical Issue
- Billing Inquiry
- Product Inquiry
- Cancellation Request
- Refund Request

5. Priority Prediction

A separate Logistic Regression model predicts:

- High Priority
- Medium Priority
- Low Priority

based on ticket descriptions.

6. Model Evaluation

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

---

## Results

Ticket Category Classification

The model predicts the category of a customer support ticket using ticket description text.

Metrics Used:

- Accuracy
- Precision
- Recall
- F1-Score

## Priority Prediction

The model predicts the priority level of incoming support tickets.

## Metrics Used:

- Accuracy
- Precision
- Recall
- F1-Score

---

## Sample Prediction

Input

Customer cannot login and access account

Output

Category: Cancellation Request

Priority: High

---

## Business Impact

This solution can help organizations:

- Automate ticket routing
- Prioritize urgent customer issues
- Reduce manual support workload
- Improve response times
- Enhance customer satisfaction

---

## Future Improvements

- Use advanced NLP models such as BERT
- Hyperparameter tuning
- Larger and more diverse datasets
- Real-time ticket prediction API
- Deep Learning-based text classification

---

## Conclusion

This project demonstrates how Natural Language Processing can be applied to real-world customer support operations. By combining text preprocessing, feature extraction, classification, and priority prediction, the system helps streamline support workflows and improve operational efficiency.
