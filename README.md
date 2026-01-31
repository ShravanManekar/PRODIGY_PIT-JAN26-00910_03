# 📊 Decision Tree Classifier – Bank Marketing Dataset (Task 3)

## 🧠 Overview
This project is part of **Task 4 of the Internship Program**.  
The goal is to build a **Decision Tree Classifier** that predicts whether a customer will purchase a product or service based on demographic and behavioral data.

The dataset used is the **Bank Marketing Dataset** from the **UCI Machine Learning Repository**, which contains data from direct marketing campaigns of a Portuguese bank.

---

## 🎯 Objective
- Predict customer purchase behavior (`yes` / `no`)
- Understand key factors influencing customer decisions
- Build a machine learning classification model
- Evaluate model performance using standard metrics

---

## 📂 Dataset Details
- **Source:** UCI Machine Learning Repository
- **Dataset Name:** Bank Marketing Dataset
- **Total Records:** 41,188
- **Target Variable:** `y`
  - `yes` → Customer subscribed
  - `no` → Customer did not subscribe

### 🔑 Features Include:
- Age, job, marital status, education
- Contact type, campaign duration
- Number of contacts performed
- Previous campaign outcomes
- Economic indicators

---

## ⚙️ Technologies Used
- **Python**
- **Pandas & NumPy**
- **Scikit-learn**
- **Matplotlib**
- **Jupyter Notebook**

---

## 🛠️ Methodology

### 1️⃣ Data Preprocessing
- Loaded dataset from CSV file
- Checked for missing values
- Converted categorical variables using **Label Encoding**

### 2️⃣ Feature Selection
- Independent variables: Customer demographics and campaign details
- Dependent variable: `y` (purchase decision)

### 3️⃣ Model Training
- Algorithm: **Decision Tree Classifier**
- Criterion: Gini Index
- Max Depth: 5 (to prevent overfitting)
- Train-Test Split: 80% training, 20% testing

### 4️⃣ Model Evaluation
- Accuracy Score
- Confusion Matrix
- Classification Report

---

## 📊 Results

- **Accuracy:** ~91%
- The model performs well in identifying non-buyers
- Moderate performance in predicting buyers due to class imbalance

### Confusion Matrix Insight:
- High true negatives (customers who did not purchase)
- Reasonable true positives (customers who purchased)

---

## 📈 Feature Importance
The Decision Tree model provides insights into the most influential features affecting customer purchase decisions, helping businesses focus on high-impact variables.

---

## 🚀 Conclusion
This project demonstrates how machine learning can be applied to real-world marketing data to predict customer behavior. The Decision Tree model provides good accuracy and interpretability, making it suitable for business decision-making and marketing strategy optimization.

---

## 🔮 Future Improvements
- Handle class imbalance using SMOTE
- Try advanced models like Random Forest or XGBoost
- Hyperparameter tuning using GridSearchCV
- Deploy model using Flask or Streamlit

---

## 📌 Internship Task
**Task Number:** 3 
**Domain:** Data Science / Machine Learning  
**Internship Project:** Customer Purchase Prediction
