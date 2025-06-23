# emotion_detection
# 🧠 Emotion Detection from Text

This project detects emotions (like joy, anger, sadness, etc.) from text messages using Natural Language Processing (NLP) techniques. It can serve as the foundation for emotion-aware chatbots, mental health tools, or educational feedback systems.

---

## 📌 Problem Statement

AI can be used in education and mental health by detecting student emotions from messages.

---

## 🎯 Objective

Classify emotions such as happy, sad, angry, etc., from text using machine learning and text sentiment analysis.

---

## 📂 Dataset

- **Source**: [Kaggle - Emotions Dataset for NLP](https://www.kaggle.com/datasets/praveengovi/emotions-dataset-for-nlp)
- **File Used**: `train.txt`
- Contains labeled text messages with one of several emotions like joy, sadness, anger, fear, love, surprise.

---

## 🧪 Model Pipeline

1. Load and preprocess the dataset  
2. Encode emotion labels  
3. Vectorize text using **TF-IDF**  
4. Train classifier (**Logistic Regression**)  
5. Evaluate using **precision**, **recall**, and **classification report**

---

## 🔧 Tech Stack

- Python 🐍  
- Pandas, NumPy  
- Scikit-learn  
- TF-IDF Vectorizer  
- Logistic Regression

---

## 🧾 How to Run

1. Clone the repository or download the `.ipynb` notebook
2. Install requirements:
   ```bash
   pip install pandas scikit-learn
