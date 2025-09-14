# 📈 Telco Customer Churn Analysis

## 📌 Overview
This project analyzes a **telecom customer dataset (7,043 records)** to predict churn and uncover the drivers of customer retention.  
Using **Logistic Regression** and **Decision Trees**, we evaluated customer attributes like contract type, tenure, internet service, and charges.  
The analysis provided both **predictive accuracy (80%)** and **business insights** to reduce churn through targeted interventions.  

---

## 📂 Project Structure
📂 telco-churn-analysis

├── analysis.ipynb # Jupyter Notebook with full EDA + modeling

├── report.pdf # Final written analysis and recommendations

├── powerpoint.ppt # Final written analysis and recommendations

├── requirements.txt # Python dependencies

└── README.md

---
---

## 🛠️ Tasks Performed
- Cleaned and prepared telecom dataset (**7,043 customer records**)  
- Created **correlation heatmaps** to identify strongest churn predictors  
- Conducted exploratory visualizations: pie charts, bar charts for contract types & churn rates  
- Trained and evaluated:
  - **Logistic Regression** with tuned thresholds (accuracy 80%, recall 70%, precision 60%)  
  - **Decision Tree model** identifying tenure, contract type, fiber optic service, and charges as key churn drivers  

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

Jupyter Notebook

Machine Learning: Logistic Regression, Decision Trees, Cross-Validation

Visualization: Correlation heatmaps, bar charts, pie charts

## 📊 Results

- Achieved **80% accuracy**, **70% recall**, and **60% precision** at threshold = 0.4  
- Found **contract type** as the strongest predictor of churn (**88.6% of churners** had month-to-month contracts)  
- Identified **tenure** (shorter = higher churn), **fiber optic customers**, and **monthly charges** as major churn factors  

### 💡 Business Recommendations
- Promote **1–2 year contracts** with incentives to stabilize customer base  
- Investigate **pricing/quality issues** for fiber optic service  
- Launch **loyalty programs** to reward renewals and long-term customers  
- Target **high-risk customers** flagged by the model for retention campaigns  
