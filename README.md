# Logistic Regression Comparison

This project demonstrates and compares four different logistic regression modeling strategies using a sample dataset. The comparison highlights the effects of **feature scaling** and **class balancing using SMOTE**.

## 🔍 Models Compared

1. **Basic Logistic Regression**  
   - No scaling  
   - No class balancing  

2. **Logistic Regression with Feature Scaling**  
   - StandardScaler applied  
   - No SMOTE  

3. **Logistic Regression with SMOTE**  
   - Class imbalance handled with SMOTE  
   - No feature scaling  

4. **Logistic Regression with SMOTE + Feature Scaling**  
   - Combines both SMOTE and StandardScaler  

---

## 📁 Files

- `Logistic_Regression.py` — The main Python script comparing the models
- `sample_logistic_data.csv` — Sample dataset used for binary classification
- `README.md` — Project description and usage instructions

---

## ⚙️ Requirements

Install dependencies using pip:

```bash
pip install pandas scikit-learn imbalanced-learn matplotlib
