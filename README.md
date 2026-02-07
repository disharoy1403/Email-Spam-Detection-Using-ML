# 📧 SMS Spam Classifier using Naive Bayes & NLP

This project builds a **Spam Detection System** for SMS / email messages using **Natural Language Processing (NLP)** and a **Multinomial Naive Bayes** classifier with Scikit-Learn.  
The model predicts whether a message is **Spam (1)** or **Not Spam / Ham (0)**.

---

## 🚀 Project Overview

Spam messages are a major problem in digital communication. This project applies classic NLP + Machine Learning techniques to automatically detect spam messages based on text content.

We use:
- `CountVectorizer` for text feature extraction  
- `MultinomialNB` for classification  
- `Pipeline` for clean preprocessing + modeling

---

## 🧠 Model Pipeline

Raw Text  →  CountVectorizer  →  Multinomial Naive Bayes  →  Spam / Ham

---

## 📂 Dataset

The dataset (`spam.csv`) contains two main columns:

| Column   | Description              |
|----------|--------------------------|
| Category | spam / ham (label)       |
| Message  | SMS / Email text content |

---

## 🛠 Tech Stack

- Python  
- Pandas  
- Scikit-Learn  
- Jupyter / Google Colab  

---

## 👩‍💻 Author

Disha Roy
