# 📧 Spam Email Classifier

## 🎯 Objective

To classify emails as **Spam or Not Spam (Ham)** using Machine Learning.

---

## ⚙️ Workflow

1. Load dataset (Spam/Ham emails)
2. Clean and preprocess text
3. Remove stopwords and punctuation
4. Convert text into numerical features using TF-IDF
5. Split dataset into training and testing sets
6. Train Naive Bayes classifier
7. Evaluate model performance
8. Save trained model for future predictions

---

## 🧠 Algorithms Used

* Multinomial Naive Bayes

---

## 📊 Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-score

---

## 📁 Project Structure

SpamEmailClassifier/

* spam_classifier.py
* model.pkl
* vectorizer.pkl
* requirements.txt
* README.md

---

## ▶️ How to Run

```bash
pip install -r requirements.txt
python spam_classifier.py
```

---

## 📌 Dataset

* Kaggle Spam Email Dataset
* UCI SMS Spam Collection Dataset

---

## 🚀 Output

* Model accuracy printed
* Classification report displayed
* Saved trained model (`model.pkl`)
