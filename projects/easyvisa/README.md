# EasyVisa — Visa Approval Prediction (Classification)

## 📌 Business Objective
EasyVisa supports applicants and employers by streamlining the visa application process.  
The objective of this project is to build a predictive model that estimates whether a visa application will be **certified** or **denied**, helping:

- Prioritize high-probability applications
- Identify factors driving denials
- Reduce processing time and operational cost

---

## 📊 Dataset Overview
The dataset contains historical visa application records including applicant and job attributes.

**Target Variable:** Case Status (Certified / Denied)

Typical feature groups include:
- Employment / job attributes
- Wage-related fields
- Case processing attributes
- Work location / company indicators (if present)

---

## 🛠 Tools & Technologies
- Python
- Pandas / NumPy
- Scikit-learn
- Matplotlib / Seaborn
- (If used) XGBoost / LightGBM
- Jupyter Notebook

---

## 🔍 Methodology
1. Data Cleaning & Preprocessing  
2. Exploratory Data Analysis (EDA)  
3. Feature Engineering (encoding, scaling, handling imbalance if applicable)  
4. Model Training & Comparison  
   - Baseline classifier(s)
   - Tree/ensemble models
   - Tuned model selection  
5. Model Evaluation using classification metrics:
   - Accuracy
   - Precision / Recall
   - F1-score
   - Confusion Matrix

---

## 📈 Results
The final model achieved improved classification performance over baseline models and was evaluated using business-relevant metrics (especially recall/precision trade-offs).

---

## 🔑 Key Insights
- Certain job/wage/case attributes strongly influence approval probability.
- Model evaluation focused on balancing false approvals vs false denials based on business risk.

---

## 💡 Business Recommendations
- **Risk-based review:** Use predicted probability to route cases for manual review.
- **Applicant guidance:** Identify common denial drivers and proactively inform applicants/employers.
- **Operational efficiency:** Automate low-risk approvals and focus analysts on borderline cases.

---

## 📁 Repository Structure


