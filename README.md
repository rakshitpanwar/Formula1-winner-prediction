# 🏎️ Formula 1 Win Probability Predictor

> Predict the winning probability of any F1 driver for a specific **Grand Prix & Season** using historical race and qualifying data.

---

## 🚀 Project Overview

This project uses **Machine Learning (XGBoost – Tuned with GridSearchCV)** to predict the probability of a driver winning a particular race based on:

- Qualifying position
- Grid position
- Race track (Grand Prix)
- Season (Year)
- Historical performance

---

## 🧠 Models & Techniques Used

| Step | Method |
|------|--------|
| Data Preprocessing | Merge + Feature Engineering |
| Models Tried | Logistic Regression, Random Forest, XGBoost |
| Best Model | ✅ XGBoost with Hyperparameter Tuning |
| Evaluation | Accuracy, F1 Score, ROC-AUC, Confusion Matrix |
| Final Output | Win probability based on user input |

---

## ⭐ Key Features

✅ Predict **win probability** for a driver in a particular race & year  
✅ User can input driver last name, race name, and year  
✅ Automatically fetches grid & qualifying position from dataset  
✅ No warnings, clean & optimized prediction pipeline  
✅ Supports unseen race/driver scenarios safely  

---

## 📂 Dataset Used

| File | Description |
|------|-------------|
| `drivers.csv` | Driver info |
| `races.csv` | Race + year data |
| `results.csv` | Race results + grid positions |
| `qualifying.csv` | Qualifying positions |

Dataset Source: Kaggle – Formula 1 World Championship Data 1950-2024

---

## 🔗 Kaggle Notebook (Project Code)

👉 https://www.kaggle.com/code/rakshitpanwar18/f1-rakshit

---

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Scikit-Learn
- XGBoost
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 🏁 Sample Output
🏎️ Driver: Lewis Hamilton
📍 Race: Abu Dhabi Grand Prix (2021)
🚦 Grid Position: 1
🎯 Win Probability: 87.32%








