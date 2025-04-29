# spam-sms-detector
Spam SMS detection using NLP and ML | GrowthLink Internship Task 4

# Spam SMS Detection

## 🔍 Objective
Develop a machine learning model to classify SMS messages as spam or ham (not spam), using text-based features and NLP techniques.

## 🧠 Models Used
- Multinomial Naive Bayes
- Logistic Regression
- Support Vector Machine (SVM)

## 📊 Evaluation Metrics
Used accuracy, precision, recall, and F1-score to evaluate model performance.

## ✅ Best Model
**Support Vector Machine (SVM)** gave the best results with highest accuracy and balanced performance.

## 🧹 Preprocessing Steps
- Lowercasing, punctuation removal
- Stopword removal and stemming
- TF-IDF vectorization

## 🗂 Dataset
Dataset includes labeled SMS messages (spam or ham). Publicly available, and loaded in CSV format.

## ▶️ How to Run
1. Upload `spam.csv` dataset to Colab or your local environment
2. Run all cells in the provided notebook `Spam_Detection.ipynb`
3. Trained model and vectorizer are saved as `.pkl` files for reuse

## 💼 Internship Submission Info
This project is submitted as part of the GrowthLink Machine Learning Internship Task 4: **Spam SMS Detection**.

---
