---

# Detecting Phishing Emails with Machine Learning

This project aims to develop and evaluate machine learning models for detecting phishing emails. Using a dataset of over 18,000 labeled email samples, we explore different classification techniques to identify malicious email content and improve cybersecurity defenses.
---

## 🧠 Problem Statement

Phishing remains one of the most prevalent cybersecurity threats, involving deceptive emails designed to trick users into revealing sensitive information. Detecting phishing emails reliably is essential to protecting users and systems from malicious attacks.

---

## 📊 Dataset

- **Size**: 18,650 emails
- **Classes**: 
  - Safe Email: 11,322 (60.7%)
  - Phishing Email: 7,328 (39.3%)
- **Features**:
  - Raw email text
  - Binary classification label
  - Index column (ignored in analysis)
- The dataset captures recent phishing trends, such as URL obfuscation and urgent tone.

---

## 🔧 Methodology

1. **Data Preprocessing**:
   - Text cleaning and normalization
   - Tokenization and vectorization (TF-IDF)
   - Handling class imbalance

2. **Modeling Approaches**:
   - Logistic Regression
   - Random Forest
   - Neural Networks

3. **Evaluation Metrics**:
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - ROC and Precision-Recall curves

---

The Random Forest model demonstrated the best performance in detecting phishing emails. The study highlights the importance of model selection and feature analysis for cybersecurity applications.

---
