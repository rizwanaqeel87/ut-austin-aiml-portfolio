# PersonalLoan — Customer Loan Acceptance Prediction (Classification)

## 📌 Business Objective

The goal of this project is to predict whether an existing banking customer will accept a personal loan offer.

This helps the bank:

- Target high-probability customers
- Improve campaign conversion rate
- Reduce marketing costs
- Increase revenue from loan products

---

## 📊 Dataset Overview

The dataset includes customer-level attributes such as:

- Age
- Income
- Education
- Credit card usage
- Securities account
- Online banking usage
- Family size
- Experience

**Target Variable:**  
- Personal Loan (0 = No, 1 = Yes)

---

## 🛠 Tools & Technologies

- Python  
- Pandas / NumPy  
- Scikit-learn  
- Matplotlib / Seaborn  
- Logistic Regression  
- Random Forest  
- Gradient Boosting  

---

## 🔍 Methodology

1. Data Cleaning & Preprocessing  
2. Exploratory Data Analysis  
3. Feature Engineering  
4. Model Training:
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - Boosting models  
5. Model Evaluation using:
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - ROC-AUC

---

## 📈 Results

Ensemble models significantly improved predictive performance compared to baseline models.

Model evaluation focused on **precision-recall trade-off**, since false positives (targeting wrong customers) increase marketing cost.

---

## 🔑 Key Insights

- Income level strongly influences loan acceptance.
- Customers with higher education levels show higher probability of accepting loans.
- Existing product engagement (e.g., credit card usage) increases likelihood of conversion.

---

## 💡 Business Recommendations

### ✅ Target High-Probability Segments
Focus campaigns on customers with predicted probability above a defined threshold.

---

### ✅ Personalized Marketing
Design differentiated campaigns based on income and engagement level.

---

### ✅ Optimize Campaign Budget
Reduce outreach to low-probability customers to lower cost per acquisition.

---

## 📁 Repository Structure

