# Fake-News-Detection-Using-ML

<div align="center">
  <h1>📰 Fake News Detection Using Machine Learning</h1>
  <p><strong>A project to classify real vs. fake news articles using supervised learning models.</strong></p>

  <p>
    <a href="https://github.com/Nameeth-Jalem/Fake-News-Detection-Using-ML/stargazers"><img src="https://img.shields.io/github/stars/Nameeth-Jalem/Fake-News-Detection-Using-ML?style=social" /></a>
    <a href="https://github.com/Nameeth-Jalem/Fake-News-Detection-Using-ML/network/members"><img src="https://img.shields.io/github/forks/Nameeth-Jalem/Fake-News-Detection-Using-ML?style=social" /></a>
    <a href="https://github.com/Nameeth-Jalem/Fake-News-Detection-Using-ML/issues"><img src="https://img.shields.io/github/issues/Nameeth-Jalem/Fake-News-Detection-Using-ML" /></a>
  </p>
</div>

---

## 🧠 Overview

Fake news spreads misinformation and can influence public opinion. In this project, we tackle this issue using machine learning by training models to distinguish between **real** and **fake** news articles.

The model is trained on two datasets: `Fake.csv` and `True.csv`, containing labeled news articles.

---

## 📁 Project Structure
Fake-News-Detection-Using-ML/ 
├── Fake.csv # Fake news dataset
├── True.csv # Real news dataset 
├── Fake_News_Detection_Using_Machine_Learning.ipynb # ML notebook └── README.md

---

## 📊 Datasets

- **Fake.csv** — Contains fabricated news articles
- **True.csv** — Contains verified, true news articles
- Both datasets include columns like `title`, `text`, and `subject`

---

## 🛠️ Techniques Used

- Natural Language Processing (NLP)
- Text Preprocessing
- TF-IDF Vectorization
- Model Training & Evaluation

---

## 🤖 Models Implemented

- ✅ Logistic Regression
- ✅ PassiveAggressive Classifier
- ✅ Naive Bayes (optional)

Each model is evaluated based on **accuracy, precision, recall,** and **F1 score.**

---

## 📈 Results

| Model                     | Accuracy     |
|--------------------------|--------------|
| Logistic Regression      | ~96%         |
| PassiveAggressive Class. | ~95%         |

> These models provide strong baseline performance in identifying fake news.

---

## 🚀 Run the Notebook

1. Clone the repo:
```bash
git clone https://github.com/Nameeth-Jalem/Fake-News-Detection-Using-ML.git
cd Fake-News-Detection-Using-ML

