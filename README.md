# spam_detection
A simple machine learning project that classifies messages as Spam or Not Spam using TF-IDF and Naive Bayes.
---

## 🎯 Objective

To build a text classification model that can distinguish spam messages from legitimate (ham) ones using natural language processing and machine learning techniques.

---

## 📦 Tech Stack

- **Python**
- **Pandas**, **NumPy** – Data handling
- **NLTK** – Text preprocessing
- **Scikit-learn** – TF-IDF vectorization, model training, evaluation
- **Google Colab** – Development and testing environment

---

## 🗂 Dataset

- The dataset is a CSV file containing SMS messages labeled as `spam` or `ham`.
- Example:
label	text
ham	I'll call you later.
spam	Congratulations! You've won a prize!

---

## 🔍 Text Preprocessing Steps

- Lowercasing text
- Removing special characters
- Removing English stopwords using NLTK

---

## 🧠 Model Used

- **Multinomial Naive Bayes** – Suitable for discrete features like word counts or TF-IDF

---

## 📈 Evaluation

After training and testing, the model was evaluated using:

- **Accuracy Score**
- **Classification Report** (Precision, Recall, F1-score)

Example Output:
Accuracy: 0.98

    precision    recall  f1-score   support

       0       0.98      1.00      0.99       965
       1       0.96      0.86      0.91       150

accuracy                           0.98      1115
