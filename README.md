# ai-job-salary-analysis-ml
Machine Learning project analyzing 50,000 AI job listings to predict salary drivers.
Added project overview, dataset description, EDA insights, model comparison results, key findings, tech stack, and instructions to run the project.
# AI Job Market Salary Intelligence & Prediction

Analyzed 50,000 AI job listings to identify key salary drivers and built regression models to predict compensation.

---

## 📌 Project Overview
This project explores salary trends in the AI job market using structured job listing data.  
The objective was to identify key compensation drivers and compare machine learning models for salary prediction.

---

## 📊 Dataset Description
- 50,000 AI/ML job listings  
- 14 structured features  
- Features include:
  - experience_level
  - company_size
  - employment_type
  - remote_ratio
  - salary_in_usd
- Clean dataset with no missing values

---

## 🔍 Exploratory Data Analysis (EDA) Insights
- Salary increases significantly with experience level
- Entry → Mid increase ≈ +$40K
- Mid → Senior increase ≈ +$50K
- Geographic and company size differences were minimal
- Strong linear salary structure observed

---

## 🤖 Model Comparison

| Model | R² Score | MAE |
|-------|----------|------|
| Linear Regression | 0.987 | $3,521 |
| Random Forest | 0.985 | $3,735 |

---

## 🧠 Key Finding
Experience-based features account for ~99% of salary prediction power.

---

## 🛠 Tech Stack
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---
## 📊 Salary Distribution
![Salary Distribution](images/salary_distribution.png)

## 📈 Experience vs Salary
![Experience vs Salary](images/experience_vs_salary.png)

## 🌲 Feature Importance
![Feature Importance](images/feature_importance.png)

## ▶️ How to Run the Project

1. Clone the repository:https://github.com/Priyasha1507/ai-job-salary-analysis-ml

