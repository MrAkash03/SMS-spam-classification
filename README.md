# 📩 SMS Spam Classification

A Machine Learning project to classify SMS messages as **Spam** or **Ham (Not Spam)** using **Natural Language Processing (NLP)** techniques.

---

## 🚀 Project Overview

This project builds a text classification model that automatically detects spam messages.  
It applies **text cleaning**, **feature extraction**, and **supervised learning** to predict whether an SMS is spam or not.

---

## 🧠 Key Features

- Preprocesses text data (cleaning, tokenization, stopword removal)
- Converts text into numerical features using TF-IDF or CountVectorizer
- Trains multiple ML models and compares performance
- Evaluates using accuracy, precision, recall, and F1-score
- Detects spam messages with high accuracy

---

## 📊 Dataset

The dataset used is the [SMS Spam Collection Dataset](https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection) from the UCI Machine Learning Repository.

| Label | Description | Count |
|-------|--------------|-------|
| Ham   | Normal message | 4827 |
| Spam  | Unwanted message | 747 |

---

## ⚙️ Tech Stack

- **Language:** Python  
- **Libraries:**
  - pandas, numpy – Data handling
  - matplotlib, seaborn – Visualization
  - scikit-learn – ML algorithms & metrics
  - nltk – NLP text preprocessing

---

## 🧩 Project Workflow

1. **Data Preprocessing**
   - Remove punctuation, special symbols, and stopwords
   - Convert text to lowercase
   - Apply stemming/lemmatization

2. **Feature Extraction**
   - Use TF-IDF or CountVectorizer to convert text into vectors

3. **Model Building**
   - Train models like Naive Bayes, Logistic Regression, and SVM

4. **Evaluation**
   - Calculate accuracy, precision, recall, and F1-score
   - Visualize confusion matrix for better understanding

---

## 📈 Results

- **Accuracy:** ~98%  
- **Model Used:** Multinomial Naive Bayes  
- The model effectively classifies spam messages with minimal false positives.

---

## 🧪 Example Predictions

| SMS Text | Prediction |
|-----------|-------------|
| "Congratulations! You've won a $500 gift card!" | Spam |
| "Are we meeting tomorrow at 10?" | Ham |

---

## 🖥️ How to Run

1. Clone the repository  
   ```bash
   git clone https://github.com/MrAkash03/SMS-spam-classification.git
   cd SMS-spam-classification
