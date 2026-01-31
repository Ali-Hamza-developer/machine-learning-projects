![Fake News Detection](https://img.shields.io/badge/Fake%20News-Detection-red?style=for-the-badge)

## 📌 Project Overview
This project builds and evaluates supervised machine learning models to classify news articles as **Fake (0)** or **Real (1)** based on textual content.  
The goal is to help reduce the spread of misinformation using NLP techniques.

## 🔍 Problem Type
- Learning Type: Supervised Learning  
- Task: Binary Text Classification  
- Target Variable: `class`  
  - `0` → Fake News  
  - `1` → Real News  

## 📂 Dataset
- **Fake.csv** – Fake news articles  
- **True.csv** – Real news articles  
- Total Records: ~44,000  
- Features:
  - `title` – News headline  
  - `text` – Full article content  
  - `class` – Target label  

> Dataset source: Kaggle / Online News Repositories

## ⚙️ Workflow
- Data loading and labeling
- Dataset merging and shuffling
- Text cleaning and preprocessing
- TF-IDF feature extraction
- Train–test split (75% / 25%)
- Model training and evaluation

## 🤖 Models Used
- Logistic Regression  
- Decision Tree  
- Random Forest  
- Gradient Boosting Classifier  

## 📊 Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  

## 🚀 Prediction
The trained model accepts **raw news text** and predicts whether the news is:
- **FAKE NEWS**
- **REAL NEWS**

## 🧠 Technologies
![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat-square&logo=python)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Supervised-green?style=flat-square)
![NLP](https://img.shields.io/badge/NLP-TF--IDF-orange?style=flat-square)
![Scikit Learn](https://img.shields.io/badge/scikit--learn-ML-yellow?style=flat-square&logo=scikitlearn)


![Fake News Detection](Fake%20News%20Detection.svg)



![Status](https://img.shields.io/badge/Status-Completed-success?style=flat-square)
![Model](https://img.shields.io/badge/Task-Binary%20Classification-purple?style=flat-square)

