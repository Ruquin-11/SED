# SED
Spam Email Detection using Logistic Regression and TF-IDF Vectorizer
# Spam Email Detector - Terminal Application

This is a simple terminal-based **Spam Email Detection** project built using Python, **Logistic Regression**, and **TF-IDF Vectorizer** from scikit-learn. It classifies email messages as **Spam** or **Ham** (Not Spam) using machine learning techniques.

## ✅ Features

- Preprocesses and vectorizes email text using TF-IDF
- Trains a Logistic Regression classifier
- Predicts in real-time from terminal input
- Accuracy: ~98.3% (Training), ~95.1% (Testing)

## 🧠 Technologies Used

- Python 3.x
- pandas
- scikit-learn
- numpy

## 📁 Dataset

Dataset used: [Kaggle - SMS Spam Collection](https://www.kaggle.com/datasets/venky73/spam-mails-datasett)

Make sure your dataset file is named **`spam_ham_dataset.csv`** and contains at least:
- `text` column: the message content
- `label_num` column: `1` for spam, `0` for ham

## 🛠️ How to Run

### 1. Install required packages:
```bash
pip install pandas numpy scikit-learn
