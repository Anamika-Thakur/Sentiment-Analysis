#  Sentiment Analysis
AI-Powered Movie Review Sentiment Classification using Natural Language Processing

Sentiment Analysis using SVM is a machine learning-based NLP system that predicts whether a movie review expresses Positive or Negative sentiment using textual patterns and linguistic behavior.

Instead of manually analyzing thousands of reviews, the system automatically understands review sentiment by transforming raw text into mathematical representations and classifying them using a Linear Support Vector Machine (SVM).

The project demonstrates how traditional Machine Learning techniques can achieve powerful Natural Language Processing performance without relying on deep learning or transformer models.

---

#  Project Goals

- Predict whether a movie review is Positive or Negative.
- Build a complete end-to-end NLP machine learning pipeline.
- Convert raw text into numerical representations using TF-IDF.
- Train a high-performance traditional ML sentiment classifier.
- Demonstrate text preprocessing and feature engineering techniques.
- Evaluate model performance on large-scale unseen review data.

---

#  Features Used

The model predicts sentiment using:

- Review Text
- Word Frequency
- Word Importance
- Bi-gram Context Patterns
- TF-IDF Weights

These features help the model understand sentiment-heavy textual patterns and contextual word relationships.

---

#  Techniques Applied

- Natural Language Processing (NLP)
- Text Preprocessing
- TF-IDF Vectorization
- N-Gram Feature Extraction
- Linear Support Vector Machine (LinearSVC)
- Binary Classification
- Train/Test Split
- Sparse Matrix Processing
- Classification Report Evaluation

---

#  How the System Works

The project follows a complete NLP machine learning pipeline:

```text
Raw Movie Reviews
        ↓
Text Cleaning & Preprocessing
        ↓
TF-IDF Feature Extraction
        ↓
N-Gram Vectorization
        ↓
Linear SVM Training
        ↓
Positive / Negative Prediction
        ↓
Real-Time Sentiment Analysis
```

---


# Dataset

Dataset Used:
- Large Movie Review Dataset : https://ai.stanford.edu/~amaas/data/sentiment/

---


# Model Performance

### Accuracy Score: 87.19%

## Classification Report

```text
                  precision    recall  f1-score   support

        Negative       0.87      0.88      0.87     12500
        Positive       0.88      0.86      0.87     12500
    
        accuracy                           0.87     25000
       macro avg       0.87      0.87      0.87     25000
    weighted avg       0.87      0.87      0.87     25000
```


