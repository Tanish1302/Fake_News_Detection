# 📰 Fake News Detection

A machine learning-based system that classifies news articles as real or fake using three popular classifiers: Logistic Regression, Naive Bayes, and Gradient Boosting. This project also includes a graphical user interface (GUI) to interactively test the models.

## 📑 Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Models](#models)
- [Installation](#installation)
- [Usage](#usage)
- [GUI](#gui)
- [Results](#results)
- [Folder Structure](#folder-structure)
- [Contributing](#contributing)
- [License](#license)
- [References](#references)

---

## 🧠 Overview

Fake news detection is a crucial task in today’s digital age, where misinformation spreads rapidly. This project implements and compares three machine learning models to detect fake news:
- **Logistic Regression**
- **Naive Bayes**
- **Gradient Boosting**

The best-performing model is integrated into a user-friendly GUI that predicts whether a given news article is real or fake.

---

## 📂 Dataset

The dataset used in this project consists of labeled news articles. Each entry contains:
- Title
- Text body
- Label (`real` or `fake`)

> You can explore public datasets like [Fake and Real News Dataset on Kaggle](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset) if you want to expand the scope.

---

## ⚙️ Models

All models are trained using the **TF-IDF vectorized text features**. The following models are implemented and stored as `.pkl` files:
- `LogisticRegression_model.pkl`
- `NaiveBayes_model.pkl`
- `GradientBoosting_model.pkl`

Evaluation metrics like accuracy, precision, recall, and F1-score are used to compare performance.

---

## 💻 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Tanish1302/Fake_News_Detection.git
   cd Fake_News_Detection
