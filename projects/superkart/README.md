# SuperKart Sales Forecasting — Demand Prediction Using Ensemble Learning

## 📌 Business Objective

SuperKart is a retail business aiming to forecast product sales to optimize inventory planning and reduce stockouts.

The goal of this project is to build a machine learning model that predicts sales quantity using historical transactional data, enabling:

- Better inventory management
- Improved demand planning
- Reduced overstock and lost sales

---

## 📊 Dataset Overview

The dataset contains transactional retail records including:

- Product attributes
- Store information
- Historical sales
- Pricing and promotions

Target Variable:
- Sales Quantity

---

## 🛠 Tools & Technologies

- Python  
- Pandas / NumPy  
- Scikit-learn  
- Matplotlib / Seaborn  
- Jupyter Notebook  
- Joblib (model persistence)

---

## 🔍 Methodology

1. Exploratory Data Analysis (EDA)
2. Feature Engineering
3. Train/Test Split
4. Model Training:
   - Linear Regression
   - Random Forest
   - Gradient Boosting
   - Bagging Regressor (Final Model)
5. Hyperparameter Tuning
6. Model Evaluation using RMSE

---

## 📈 Results

The tuned **Bagging Regressor** achieved the lowest RMSE compared to baseline models, demonstrating strong generalization performance for sales forecasting.

---

## 🔑 Key Insights

- Historical sales trends are the strongest predictors.
- Promotional pricing significantly impacts demand.
- Certain product categories show seasonal patterns.

---

## 💡 Business Recommendations

### ✅ Inventory Optimization
Use model forecasts to dynamically adjust stock levels per product.

---

### ✅ Promotion Planning
Leverage predictions to time promotions for maximum uplift.

---

### ✅ Category-Based Strategy
Apply category-level demand trends to optimize assortment planning.

---

## 📁 Repository Structure

