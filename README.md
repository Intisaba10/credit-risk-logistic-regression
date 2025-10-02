# Credit Risk Prediction with Logistic Regression

This project uses the **UCI Credit Card Default dataset** to predict whether a customer will default on their payment in the next month. The model is built using **Logistic Regression**, with an emphasis on interpretability and practical application in financial risk management.

---

## 📌 Project Overview
Credit risk assessment is a critical task in finance. This project demonstrates how a simple yet powerful algorithm like Logistic Regression can be used to predict default risk, while maintaining transparency for decision-making.

---

## 📊 Dataset
- **Source:** UCI Machine Learning Repository – Credit Card Default Dataset  
- **Size:** 30,000 records  
- **Target Variable:** `default.payment.next.month` (binary: 0 = no default, 1 = default)  
- **Features:** Demographic information, bill statements, payment history, and credit limits  

---

## ⚙️ Methodology
1. **Data Preprocessing**  
   - Handling missing values  
   - Feature scaling using StandardScaler  
   - Train-test split  

2. **Model Building**  
   - Logistic Regression with class balancing (`class_weight='balanced'`)  
   - Hyperparameter tuning  

3. **Evaluation Metrics**  
   - Accuracy, Precision, Recall, F1-score  
   - Confusion Matrix  
   - ROC Curve and AUC Score  

---

## 📈 Results
- Payment history was found to be the strongest predictor of default.  
- Logistic Regression achieved a solid ROC-AUC score, highlighting its ability to distinguish between defaulters and non-defaulters.  
- While simple, the model provided high interpretability, making it useful for financial applications.  

---

## 💡 Key Takeaways
- Proper **data preprocessing and scaling** are essential for reliable predictions.  
- Logistic Regression balances **performance with interpretability**, which is critical in financial domains.  
- This project highlights how traditional machine learning models can complement modern AI methods in credit risk assessment.  

---

## 🚀 Future Work
- Compare Logistic Regression with advanced models (Random Forest, XGBoost, Neural Networks).  
- Apply feature selection for model optimization.  
- Explore fairness and bias mitigation in credit risk modeling.  

---

## 🛠️ Technologies Used
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
