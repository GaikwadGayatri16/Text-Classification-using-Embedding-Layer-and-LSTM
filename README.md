# Practical 02 — Text Classification using Embedding Layer and LSTM

## Binary Sentiment Classification of IMDB Movie Reviews

---

## 1. Practical Overview

This practical implements a **binary text classification system using an Embedding layer and Long Short-Term Memory (LSTM) network**.

The objective is to classify movie reviews from the **IMDB Movie Reviews dataset** into two sentiment categories:

- **0 → Negative**
- **1 → Positive**

The implementation demonstrates the complete deep learning pipeline for text classification:

```text
IMDB Movie Reviews
        ↓
Integer Word Encoding
        ↓
Review Length Analysis
        ↓
Padding / Truncation
        ↓
Train–Validation Split
        ↓
Embedding Layer
        ↓
LSTM Layer
        ↓
Dropout
        ↓
Sigmoid Classification
        ↓
Model Evaluation
        ↓
Confidence & Error Analysis
        ↓
Interactive Sentiment Prediction
