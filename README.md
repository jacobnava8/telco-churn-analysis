# 📈 Telco Customer Churn Analysis

## 📌 Overview
This project analyzes a **telecom customer dataset (7,000+ records)** to predict churn and identify drivers of customer retention.  
Machine learning models including **Logistic Regression** and **Decision Trees** were applied to forecast churn, with business-focused threshold tuning to balance false positives and false negatives.

---

## 📂 Project Structure
📂 telco-churn-analysis
├── analysis.ipynb # Jupyter Notebook with full EDA + modeling
├── report.pdf # Final written analysis and recommendations
├── requirements.txt # Python dependencies
└── README.md

---

## 🚀 How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/JacobNava/telco-churn-analysis
   cd telco-churn-analysis
     ```
2. Install dependencies:

  ```bash

pip install -r requirements.txt
  ```

3. Open the notebook:

  ```bash

jupyter notebook analysis.ipynb
  ```

## 🛠️ Tech Stack
Python: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
  ```
Jupyter Notebook
  ```

Machine Learning: Logistic Regression, Decision Trees, Cross-Validation

Visualization: Correlation heatmaps, bar charts, pie charts

## 📊 Results
Achieved ~79% model accuracy
Final Report


Identified Month-to-Month contracts as the biggest churn driver (88% of churners)

Cost-sensitive threshold tuning reduced overall business loss by prioritizing high-risk churners

Recommended loyalty programs and contract incentives for retention
