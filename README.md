# 📘 Sentiment Analysis of IMDB Movie Reviews

*A Machine Learning project using Logistic Regression, SVM, and Naïve Bayes*

## 📌 Overview

This project performs **sentiment analysis** on the **IMDB Movie Reviews Dataset**, classifying reviews as **positive** or **negative** using traditional NLP techniques and machine learning models.

The workflow includes:

* Text preprocessing (HTML stripping, noise removal, stemming, stopword removal)
* Feature extraction using **Bag of Words (BoW)** and **TF-IDF**
* Model training with:

  * **Logistic Regression**
  * **Linear SVM (SGDClassifier)**
  * **Multinomial Naïve Bayes**
* Evaluation with accuracy, classification reports, and confusion matrices
* WordCloud visualizations for positive and negative reviews

---

## 📝 Credits

This project is based on the notebook by **Lakshmipathi N**:
👉 *“Sentiment Analysis of IMDB Movie Reviews”*
Source: **Kaggle Notebook**
[https://www.kaggle.com/code/lakshmi25npathi/sentiment-analysis-of-imdb-movie-reviews](https://www.kaggle.com/code/lakshmi25npathi/sentiment-analysis-of-imdb-movie-reviews)

Modifications have been made for understanding, adaptation, and GitHub presentation.

---

## 📂 Dataset

The project uses the **IMDB Dataset** (50,000 movie reviews).
The dataset is typically available on Kaggle:
`IMDB Dataset.csv`

---

## 🚀 Technologies & Libraries Used

### **Python Libraries**

* `numpy`, `pandas`
* `nltk`
* `sklearn`
* `matplotlib`, `seaborn`
* `wordcloud`
* `BeautifulSoup`
* `textblob`
* `spacy`

### **Machine Learning Models**

* Logistic Regression
* Support Vector Machine (SGDClassifier)
* Multinomial Naïve Bayes

### **Vectorizers**

* CountVectorizer (Bag of Words)
* TfidfVectorizer

---

## 📦 Project Structure

```
├── sentiment_analysis_imdb.py
├── IMDB_Dataset.csv
├── README.md
```

---

## 🧹 Preprocessing Steps

The text is cleaned using:

* Remove HTML tags
* Remove text inside square brackets
* Remove special characters
* Stemming (Porter Stemmer)
* Tokenization
* Stopword removal
* Normalization

These steps produce a cleaner corpus for modeling.

---

## 🧠 Machine Learning Models & Evaluation

### **Models Trained**

| Model                   | Features | Accuracy   |
| ----------------------- | -------- | ---------- |
| Logistic Regression     | BoW      | ~0.88–0.90 |
| Logistic Regression     | TF-IDF   | ~0.89–0.91 |
| Linear SVM              | BoW      | ~0.87–0.89 |
| Linear SVM              | TF-IDF   | ~0.88–0.90 |
| Multinomial Naïve Bayes | BoW      | ~0.81–0.83 |
| Multinomial Naïve Bayes | TF-IDF   | ~0.84–0.86 |

(*Actual values vary depending on dataset version and preprocessing.*)

Includes:

* **Classification Reports**
* **Confusion Matrices**
* **Prediction outputs**

---

## ☁ Word Cloud Visualizations

The notebook generates WordClouds for:

* Positive reviews
* Negative reviews

This helps visualize the frequent terms contributing to sentiment.

