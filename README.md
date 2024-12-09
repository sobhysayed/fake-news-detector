# Fake News Detection 📰

This project implements a **Fake News Detection System** using machine learning algorithms to classify news articles as **Fake News** or **Not Fake News**.

---

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Dependencies](#dependencies)
- [Preprocessing Steps](#preprocessing-steps)
- [Models Used](#models-used)
- [Usage](#usage)
- [Results](#results)
- [Manual Testing](#manual-testing)
- [How to Run](#how-to-run)

---

## Overview 📌

The Fake News Detection System analyzes the text content of news articles to predict their authenticity using **machine learning algorithms** such as:
- Logistic Regression
- Decision Tree
- Gradient Boosting Classifier
- Random Forest

---

## Dataset 📊

The project uses two datasets:
- **`Fake.csv`**: Contains fake news articles.
- **`True.csv`**: Contains true news articles.

### Dataset Columns:
- `title`: Title of the news article.
- `text`: Main content of the article.
- `subject`: Topic of the news.
- `date`: Published date.

---

## Dependencies 🛠️

Install required libraries using the following command:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
