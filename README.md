# 💓 Heart Disease Prediction using Machine Learning

A machine learning project to predict heart disease likelihood using patient 
health data — includes EDA, feature engineering, classification modeling, 
and evaluation.

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-orange)
![Accuracy](https://img.shields.io/badge/Accuracy-89.7%25-green)

---

## 📌 Overview

Predicts whether a patient has heart disease using health indicators from the 
UCI Heart Disease Dataset (303 records). Built to assist in early diagnosis 
through ML.

---

## 📊 Dataset

| Property | Detail |
|----------|--------|
| Source | UCI Heart Disease Dataset |
| Records | 303 |
| Target | `num` — 0 = No Disease, 1 = Disease |

---

## 🔍 EDA Highlights

- Gender & Chest Pain Type vs Heart Disease
- Age Distribution (Histogram + Boxplot)
- Correlation Heatmap
- ST Depression vs Target (Violin Plot)

---

## 🤖 Model

**Random Forest Classifier** (`n_estimators=100`)

| Metric | Score |
|--------|-------|
| Accuracy | **89.7%** |
| F1-Score | 0.90 |
| ROC-AUC | ✅ Evaluated |

---

## 🔦 Top Features

1. `cp` — Chest pain type
2. `thalach` — Max heart rate
3. `oldpeak` — ST depression
4. `ca` — Major vessels
5. `slope`

---

## 🛠 Tech Stack

`Python` `Pandas` `NumPy` `Scikit-learn` `Seaborn` `Matplotlib` `Joblib`

---

## ▶️ How to Run
```bash
git clone https://github.com/YasraNafees/Heart-_disease-Prediction-model.git
pip install -r requirements.txt
jupyter notebook Heart_Disease_Prediction.ipynb
```

---

## 📄 License
MIT License
