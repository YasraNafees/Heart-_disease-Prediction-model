# 🫀 UCI Heart Disease Predictive Model

![Python](https://img.shields.io/badge/Python-3.10+-blue) ![Scikit-Learn](https://img.shields.io/badge/ScikitLearn-Enabled-orange) ![Accuracy](https://img.shields.io/badge/Accuracy-89.67%25-brightgreen) ![AUC](https://img.shields.io/badge/AUC-0.94-green) ![License](https://img.shields.io/badge/License-MIT-yellow)

### Random Forest Classifier | 920 UCI Records | 89.67% Accuracy

A machine learning model that predicts heart disease risk using clinical data from the UCI Heart Disease dataset. Built with Random Forest, achieving **89.67% accuracy** and **0.94 AUC score**.

---

## 📊 Model Performance

| Metric | Score |
|---|---|
| Accuracy | 89.67% |
| AUC-ROC | 0.94 |
| Precision (Disease) | 0.92 |
| Recall (Disease) | 0.90 |
| F1-Score (Disease) | 0.91 |

---

## ✨ Key Features

- **Random Forest Classifier:** 100 estimators, optimized for clinical tabular data.
- **Comprehensive EDA:** Gender analysis, chest pain type distribution, age distribution, correlation heatmap.
- **Missing Value Handling:** Strategic imputation — mean for continuous, mode for categorical, -1 for vessel count.
- **Feature Engineering:** One-hot encoding for multi-class categoricals, binary mapping for sex/fbs/exang.
- **Model Persistence:** Saved via `joblib` for production deployment.

---

## 🔍 Top Predictive Features

1. **thalch** — Maximum heart rate (strongest predictor)
2. **cp** — Chest pain type
3. **exang** — Exercise-induced angina
4. **ca** — Number of major vessels
5. **oldpeak** — ST depression (0.94 AUC contribution)

---

## 🛠️ Tech Stack

| Component | Tool |
|---|---|
| Language | Python 3.10+ |
| ML Framework | Scikit-Learn |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Model Export | Joblib |

---

## 📁 Dataset

- **Source:** UCI Heart Disease Dataset
- **Records:** 920 patients
- **Features:** 15 clinical attributes
- **Target:** Binary (0 = No Disease, 1 = Disease)
- **Missing Values:** Handled via mean/median/mode imputation

---

## 🚀 Quick Start

**1. Clone the repo:**
```bash
git clone https://github.com/YasraNafees/heart-disease-prediction.git
cd heart-disease-prediction
```

**2. Install dependencies:**
```bash
pip install -r requirements.txt
```

**3. Run the notebook:**
```bash
jupyter notebook heart_disease.ipynb
```

**4. Load saved model:**
```python
import joblib
model = joblib.load('heart_disease_model.joblib')
prediction = model.predict(your_data)
```

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first.
