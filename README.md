# Customer Churn Prediction

## 📌 Project Overview

This project focuses on predicting **customer churn** in the telecom sector. Churn prediction is crucial for businesses to proactively identify customers likely to leave and implement retention strategies.

The notebook applies multiple machine learning algorithms, evaluates their performance, and compares results using key metrics.

---

## 📂 Data Sources

* **Dataset:** `Telco-Customer-Churn.csv`
* **Description:** A publicly available dataset containing customer demographics, account information, and service usage details.
* **Target Variable:** `Churn` (Yes/No)

---

## ⚙️ How It Works

1. **Data Preprocessing**

   * Handling categorical and numerical features
   * Encoding categorical variables
   * Scaling numerical features
   * Train-test split

2. **Model Training**

   * Logistic Regression
   * Random Forest
   * XGBoost
   * LightGBM

3. **Evaluation**

   * Metrics: Precision, Recall, F1 Score, ROC-AUC
   * Classification Reports
   * Confusion Matrices
   * Bar Chart comparison of model performance

---

## 📊 Model Performance

| Model              | Precision | Recall | F1 Score | ROC-AUC |
| ------------------ | --------- | ------ | -------- | ------- |
| LogisticRegression | 0.5060    | 0.7888 | 0.6165   | 0.8423  |
| RandomForest       | 0.6305    | 0.4973 | 0.5561   | 0.8246  |
| XGBoost            | 0.5361    | 0.6952 | 0.6054   | 0.8316  |
| LightGBM           | 0.5282    | 0.7513 | 0.6203   | 0.8329  |

🔹 Logistic Regression and LightGBM achieved the best balance between recall and ROC-AUC.
🔹 Random Forest showed high precision but lower recall.
🔹 Ensemble methods (XGBoost & LightGBM) outperformed traditional models in recall and overall ROC-AUC.

---

## 🚀 Future Improvements

* Hyperparameter tuning (GridSearchCV / RandomizedSearchCV) to further improve performance
* Feature engineering (interaction terms, domain-specific transformations)
* Addressing class imbalance using advanced resampling (SMOTE, ADASYN)
* Deploying the best-performing model as an API or web app (Flask/FastAPI + Streamlit/Gradio)

---

📬 Contact

For questions, suggestions, or collaborations, feel free to connect:
🔗 http://www.linkedin.com/in/shivek-gosain |
📧 gosain18s@gmail.com

✨ If you found this project useful, consider giving it a ⭐ on GitHub!

---
