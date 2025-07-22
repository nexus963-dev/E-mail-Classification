# 📧 Email Spam Classification using Machine Learning

This project focuses on building a machine learning model to classify emails as **spam** or **ham** (not spam). The goal is to use traditional NLP and ML techniques to process raw text data and train a classifier capable of predicting whether a new message is spam.

---

## 🚀 Objective

To create a binary classification model that analyzes the content of an email and predicts whether it is **spam** or **ham** using classical machine learning techniques.

---

## 📊 Dataset

The dataset contains two columns:

- `label`: The target column indicating the class of the email — either `spam` or `ham`.
- `text`: The actual content of the email message.

Each row represents one email and its associated label.

---

## 🧹 Text Preprocessing

Before feeding the data into the model, a number of standard text preprocessing steps were applied:

1. **Lowercasing**: All characters were converted to lowercase.
2. **Punctuation Removal**: Special characters and punctuation were removed.
3. **Stopword Removal**: Common English stopwords (e.g., "the", "is", "in") were filtered out.
4. **Tokenization**: The text was split into individual words (tokens).
5. **Lemmatization/Stemming** *(if applied)*: Words were reduced to their base/root form.

---

## 🔠 Feature Extraction

The textual data was transformed into numerical format using:

- **TF-IDF Vectorization** *(or CountVectorizer)*: Converts text into a matrix of token counts or importance scores.

---

## 🧠 Model Training

A traditional supervised machine learning algorithm was used for classification, such as:

- **Multinomial Naive Bayes** *(commonly used for text classification)*
- **Logistic Regression**
- **Support Vector Machine (SVM)**

The model was trained on the vectorized text data with the binary target (`0` for ham, `1` for spam).

---

## 📈 Model Evaluation

The model was evaluated using:

- **Accuracy**
- **Confusion Matrix**
- **Precision, Recall, and F1 Score**
- **Classification Report**

These metrics help understand how well the model distinguishes between spam and ham messages.

---

## 📂 Project Structure

