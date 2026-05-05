#  Customer Churn Prediction using Machine Learning

##  Overview
Customer churn is a major challenge for businesses. This project aims to predict whether a customer will leave a service using machine learning techniques. The model helps businesses take proactive actions to retain customers and reduce revenue loss.

---

##  Objectives
- Predict customer churn using ML models  
- Analyze key factors affecting churn  
- Compare multiple models  
- Deploy model as a web application  

---

##  Dataset
- Source: Kaggle (Telco Customer Churn Dataset)  
- ~7000 customer records  
- Features include:
  - Demographics (gender, senior citizen, dependents)
  - Services (internet, phone, add-ons)
  - Billing (monthly charges, total charges)
  - Account info (tenure, contract type, payment method)

---

##  Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib / Seaborn  
- Streamlit  

---

##  Data Preprocessing
- Handled missing values  
- Converted `TotalCharges` to numeric  
- Removed irrelevant column (`customerID`)  
- Applied one-hot encoding  

---

##  Exploratory Data Analysis (EDA)
Key insights:
- Customers with low tenure are more likely to churn  
- High monthly charges increase churn probability  
- Month-to-month contracts have highest churn  
- Electronic check users show higher churn  

---

##  Models Used
- Logistic Regression  
- Decision Tree  
- Random Forest  

---

##  Model Evaluation

| Model | Accuracy | Recall |
|------|--------|--------|
| Logistic Regression | ~78% | 0.52 |
| Decision Tree | ~77% | **0.60** |
| Random Forest | ~77% | 0.44 |

- Decision Tree was selected as the final model.

---

##  Why Decision Tree?
Although accuracy was similar across models, Decision Tree achieved higher **recall**, which is more important for identifying churn customers.

---

##  Feature Importance
Top features influencing churn:
- Tenure  
- Monthly Charges  
- Contract Type  

---

##  Deployment
- Built using Streamlit  
- Deployed via ngrok for demo  

---

##  Key Insight
> Recall is more important than accuracy in churn prediction because missing churn customers leads to business loss.


---

##  Future Improvements
- Improve model performance  
- Add more features  
- Deploy on cloud platforms  
- Use advanced ML / Deep Learning  

---

##  Author
Akash  
B.Tech CSE (AI)
