# 📊 Credit Risk Prediction using Logistic Regression

## 🎯 Objective
The goal of this project is to predict whether a borrower will default on a loan using financial and behavioral data. This helps financial institutions reduce risk and make better lending decisions.

---

## 📁 Dataset
The dataset contains borrower information such as:

- Income
- Loan amount
- Interest rate
- Employment length
- Loan-to-income ratio
- Credit history

### 🎯 Target Variable
- `loan_status`
  - 0 → No default
  - 1 → Default

---

## 🧠 Project Workflow

1. Data Cleaning  
   - Handled missing values  
   - Fixed unrealistic values (employment length)  
   - Removed invalid records  

2. Feature Engineering  
   - Encoded categorical variables  
   - Converted data into numeric format  

3. Model Training  
   - Logistic Regression model  
   - Train-test split (80/20)  

4. Model Evaluation  
   - Accuracy score  
   - Confusion matrix  
   - Classification report  

5. Probability Prediction  
   - Used `predict_proba()` to estimate default risk  

6. Threshold Tuning  
   - Adjusted decision threshold to balance risk and approvals  

---

## 🤖 Model Used
**Logistic Regression**

### Why Logistic Regression?
- Easy to interpret  
- Provides probability outputs  
- Commonly used in credit risk analysis  

---

## 📊 Results
- Model predicts probability of default  
- Identifies high-risk borrowers  
- Threshold tuning improves decision-making  

---

## 💼 Key Insights

- Lower income → higher default risk  
- Higher loan-to-income ratio → more financial stress  
- Higher interest rate → riskier borrowers  
- Past default history → strong risk indicator  
- Stable employment → lower risk  

---

## ⚠️ Risk Interpretation

- **False Negative**  
  Risky borrower predicted as safe → financial loss  

- **False Positive**  
  Safe borrower rejected → lost opportunity  

---

## 🎯 Conclusion

This project demonstrates how machine learning can be used for credit risk prediction.

- Built a Logistic Regression model  
- Predicted default probability  
- Applied threshold tuning for better control  

This approach supports better lending decisions and risk management.

---

## 🚀 Future Improvements

- Use advanced models (Random Forest, XGBoost)  
- Add ROC-AUC evaluation  
- Deploy as a web application  

---

## 🛠️ Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- Google Colab  

---

## 👤 Author
Your Name
