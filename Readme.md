# Loan Approval Prediction

This project is an end-to-end **Machine Learning application** that predicts whether a loan application will be **approved or rejected** using **Logistic Regression** and **Decision Tree** models.  
It covers the full ML lifecycle: **data preprocessing, model training, evaluation, deployment, and frontend integration**.

---

## 🚀 Live Application

- **Frontend (Netlify):**  
  👉 https://loan-approval-prediction-ml.netlify.app/

- **Backend API (Render):**  
  👉 https://loan-approval-prediction-xktt.onrender.com
  👉 Swagger UI: https://loan-approval-prediction-xktt.onrender.com/docs

---

## 📊 Dataset

**Source:** Kaggle – Loan Approval Classification Dataset  

The dataset contains personal, financial, and credit-related attributes used to predict loan approval.

### Target Variable
- `loan_status`
  - `1` → Approved
  - `0` → Rejected

### Features
- Demographic: age, gender, education
- Financial: income, loan amount, interest rate
- Credit-related: credit score, credit history length
- Loan details: loan intent, percent income
- Categorical & numerical features handled using pipelines

---

## 🧠 Machine Learning Models

Two models were trained and evaluated:

1. **Logistic Regression**
2. **Decision Tree Classifier**

### ML Pipeline
- Missing value handling
- Numerical feature scaling
- Categorical feature encoding (OneHotEncoder)
- Model training using `scikit-learn` pipelines
- Evaluation using accuracy & classification metrics
- Models exported using `joblib`

---

## 🛠️ Tech Stack

### Machine Learning
- Python
- pandas, numpy
- scikit-learn
- joblib
- matplotlib, seaborn (EDA & visualization)

### Backend
- FastAPI
- Uvicorn
- Render (deployment)

### Frontend
- HTML
- CSS
- JavaScript (Fetch API)
- Netlify (deployment)

---

## 📁 Project Structure

lloan-approval-ml-project/

├── notebook/

│   ├── loan_approval_training.ipynb    
│   └── loan_approval_dataset.csv       
├── backend/

│   ├── main.py                         
│   ├── logistic_regression_pipeline.pkl
│   ├── decision_tree_pipeline.pkl      
│   ├── requirements.txt                
│   └── README.md                       
├── frontend/

│   ├── index.html                      
│   ├── style.css                       
│   └── script.js                       
├── .gitignore                          
├── README.md                           
