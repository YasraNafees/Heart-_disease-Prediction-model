💓 Heart Disease Prediction using Machine Learning

A Data Science project to predict the likelihood of heart disease using patient health data. 
This project involves EDA, data visualization, feature engineering, 
classification modeling, and model evaluation using Python.

📁 Table of Contents
Project Overview


Dataset


Exploratory Data Analysis (EDA)

Data Preprocessing

Modeling

Evaluation Metrics

Feature Importance

Technologies Used

How to Run

Results

License

📌 Project Overview

This project predicts whether a patient has heart disease using various health indicators.
It aims to assist healthcare professionals in early diagnosis and decision-making through the power of Machine Learning.

📊 Dataset

Source: UCI Heart Disease Dataset

Total Records: 303

Target Variable: num (0 = no heart disease, 1 = heart disease)

🔍 Exploratory Data Analysis (EDA)

Visualizations created with Matplotlib and Seaborn:

Gender vs Heart Disease (Grouped Bar Chart)

Chest Pain Type vs Heart Disease

Age Distribution (Histogram, Boxplot)

Correlation Heatmap

Heart Rate (thalach) vs Heart Disease (Boxplot)

Resting BP (trestbps) vs Heart Disease

ST Depression (oldpeak) vs Target (Violin Plot)

🧹 Data Preprocessing
Handled categorical columns via One-Hot Encoding

Converted binary categorical variables to integers

Removed non-numeric columns

Split data into train/test sets

🤖 Modeling

RandomForestClassifier

n_estimators = 100, random_state = 42

Trained and evaluated using:

accuracy_score

classification_report

confusion_matrix

ROC-AUC Score

📈 Evaluation Metrics

text
Copy
Edit
Accuracy: 89.7%
Precision (Class 0): 0.86
Recall (Class 0): 0.89
Precision (Class 1): 0.92
Recall (Class 1): 0.90
F1-Score (Overall): 0.90
🔦 Feature Importance

Top features contributing to predictions:

cp (Chest pain type)

thalach (Maximum heart rate)

oldpeak (ST depression)

ca (Major vessels)

slope

Visualized using a horizontal bar plot.

🛠 Technologies Used

Python 3

Pandas

NumPy

Seaborn

Matplotlib

Scikit-learn

Joblib

▶️ How to Run
Clone the repo:

bash
Copy
Edit
git clone https://github.com/YOUR_USERNAME/heart-disease-prediction.git
Install required libraries:

bash
Copy
Edit
pip install -r requirements.txt
Run the notebook:

bash
Copy
Edit
jupyter notebook Heart_Disease_Prediction.ipynb
✅ Results
The model performed well on the test data with nearly 90% accuracy, 
making it a potential tool for early screening of heart-related issues.

📄 License
This project is open-source and available under the MIT License.

