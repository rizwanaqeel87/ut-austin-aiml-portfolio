# ReneWind — Wind Turbine Failure Prediction (Predictive Maintenance)

## 📌 Business Objective

ReneWind operates wind turbines and aims to reduce unexpected equipment failures.

The objective of this project is to build a machine learning model that predicts turbine failures in advance, enabling:

- Preventive maintenance
- Reduced downtime
- Lower operational costs
- Improved energy output

This is a classic **predictive maintenance** use case.

---

## 📊 Dataset Overview

The dataset contains historical sensor readings and operational parameters from wind turbines.

**Target Variable:**  
- Failure Status (Binary Classification)

Features include multiple sensor measurements representing turbine health.

---

## 🛠 Tools & Technologies

- Python  
- Pandas / NumPy  
- Scikit-learn  
- Matplotlib / Seaborn  
- Ensemble models  
- Jupyter Notebook (exported to HTML)

---

## 🔍 Methodology

1. Data Cleaning & Preprocessing  
2. Exploratory Data Analysis (EDA)  
3. Feature Engineering  
4. Model Training:
   - Logistic Regression
   - Random Forest
   - Gradient Boosting
5. Hyperparameter Tuning  
6. Model Evaluation using:
   - F1-score
   - Recall
   - Confusion Matrix

---

## 📈 Results

Ensemble-based models significantly outperformed baseline classifiers, achieving strong F1 and recall scores, making them suitable for early failure detection.

---

## 🔑 Key Insights

- Certain sensor readings are strong indicators of impending failure.
- Recall was prioritized to minimize missed failures.
- Tree-based models captured nonlinear sensor relationships effectively.

---

## 💡 Business Recommendations

### ✅ Preventive Maintenance
Schedule maintenance proactively for turbines with high predicted failure probability.

---

### ✅ Downtime Reduction
Use model outputs to plan service windows and reduce unexpected outages.

---

### ✅ Cost Optimization
Focus technician resources on high-risk assets rather than reactive repairs.

---

## 📁 Repository Structure


