# 📉 Customer Churn Prediction

> Predicting customer churn using Machine Learning on a Telecom dataset (100K+ rows)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189AB4?style=flat-square)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

---

## 📌 Problem Statement
Telecom companies lose revenue when customers switch providers (churn). This project builds an ML model to **predict which customers are likely to churn**, enabling proactive retention strategies.

## 🎯 Key Results
| Metric | Score |
|--------|-------|
| Accuracy | **89%** |
| ROC-AUC | **0.91** |
| False Positive Reduction | **~25%** |
| Features Engineered | **12** |

## 📁 Project Structure
```
customer-churn-prediction/
├── data/
│   └── churn_data.csv          # Dataset (synthetic / Kaggle Telco)
├── notebooks/
│   ├── 01_EDA.ipynb            # Exploratory Data Analysis
│   ├── 02_Feature_Eng.ipynb    # Feature Engineering
│   └── 03_Model_Training.ipynb # Model Training & Evaluation
├── src/
│   ├── preprocess.py
│   ├── train.py
│   └── evaluate.py
├── requirements.txt
└── README.md
```

## 🔍 Approach
1. **EDA** — Distribution plots, correlation heatmaps, churn rate analysis
2. **Data Cleaning** — Handle nulls, encode categoricals, scale features
3. **Feature Engineering** — Create 12 new features (tenure groups, charge ratios, etc.)
4. **Modelling** — Logistic Regression → Random Forest → XGBoost
5. **Evaluation** — Confusion matrix, ROC-AUC, F1-score, threshold tuning

## 🚀 How to Run
```bash
git clone https://github.com/VanilPatel/customer-churn-prediction
cd customer-churn-prediction
pip install -r requirements.txt
jupyter notebook notebooks/01_EDA.ipynb
```

## 🛠️ Tech Stack
- **Python** — Pandas, NumPy, Scikit-learn, XGBoost
- **Visualisation** — Matplotlib, Seaborn
- **Environment** — Jupyter Notebook, Google Colab

---
⭐ Star this repo if you found it helpful!
