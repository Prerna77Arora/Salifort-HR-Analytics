# 🏢 Salifort Motors: Employee Attrition Analysis

## 📖 Project Overview
I completed an **employee attrition prediction project** for **Salifort Motors**, a mid-sized automotive company.  
The goal was to **analyze employee data** and **predict which employees are at risk of leaving the company**.  

By identifying key drivers of turnover, Salifort Motors can **improve retention strategies**, **reduce hiring costs**, and **enhance employee satisfaction**.

---

## 🏢 Background
**Client:** Salifort Motors (A Fictional Company)  
- Mid-sized automotive manufacturing company  
- Facing increasing employee turnover, affecting productivity and costs  

**Business Challenge:**  
High attrition leads to:  
- Increased recruitment and training costs  
- Knowledge loss and reduced operational efficiency  

**Objective:**  
Use **machine learning** to predict **which employees are likely to leave**, and provide **insights for HR** to improve retention.

---

## 🎯 Project Goals
1. **Exploratory Data Analysis (EDA):**  
   - Understand the distribution of employee attributes  
   - Compare characteristics of employees who stayed vs. left  

2. **Feature Engineering & Preprocessing:**  
   - Handle missing values and categorical variables  
   - Encode and scale features for modeling  

3. **Machine Learning Modeling:**  
   - Build classification models including **Decision Trees** and **Random Forests**  
   - Tune hyperparameters using **RandomizedSearchCV**  
   - Evaluate models with **Accuracy, Precision, Recall, F1-score, and ROC-AUC**  

4. **Insights & Recommendations:**  
   - Identify top factors contributing to attrition  
   - Recommend HR strategies for retention  

---

## 📂 Project Structure
```plaintext
├── Salifort_Motors.ipynb    # Main Jupyter Notebook with EDA, ML, and results
├── data/
│   └── employee_data.csv    # Employee dataset (if included)
├── reports/
│   └── attrition_summary.pdf # Optional executive summary for stakeholders
└── README.md                # Project documentation (this file)
```

---

## 🛠 Tools & Skills
- **Python:** Pandas, NumPy, Matplotlib, Seaborn  
- **Machine Learning:** Scikit-learn (Decision Trees, Random Forests, Hyperparameter Tuning)  
- **Feature Engineering:** Handling categorical data, scaling, and outlier detection  
- **Classification Metrics:** Accuracy, Precision, Recall, F1-score, ROC-AUC  
- **Hyperparameter Tuning:** GridSearchCV & RandomizedSearchCV  

---

## 📈 Workflow (PACE Framework)
1. **Plan**  
   - Defined project goal: predict employees likely to leave  
   - Outlined workflow including EDA, preprocessing, and ML modeling  

2. **Analyze**  
   - Explored distributions of tenure, job roles, and satisfaction  
   - Identified correlations and outliers  

3. **Construct**  
   - Built **Decision Tree** and **Random Forest** classifiers  
   - Optimized models using **RandomizedSearchCV**  

4. **Execute**  
   - Evaluated models with multiple metrics  
   - Highlighted **key attrition drivers** and recommended HR actions  

---

## ✅ Key Takeaways
- **Tenure, overtime, and job satisfaction** are strong predictors of attrition  
- **Random Forest** achieved the best **ROC-AUC score**, suitable for classification tasks  
- Insights can **guide HR in targeted retention strategies** to reduce turnover  
- This project demonstrates **end-to-end ML workflow** from EDA to actionable recommendations  

---

## ⚠️ Disclaimer
All data, characters, and scenarios in this project are **fictitious**.  
The dataset is **intended for educational purposes** and does not represent actual employee records.
