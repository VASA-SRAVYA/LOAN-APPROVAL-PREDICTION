# 🏦 Loan Approval Prediction Web Application

A **real-world machine learning web application** built with Flask that predicts whether a loan will be approved based on user input. This app uses a trained machine learning model on a large synthetic dataset and features a neat and modern frontend.

---

## 🔍 Project Overview

This application:
- Predicts loan approval status using ML
- Takes 11 input fields (income, dependents, education, etc.)
- Is built using Flask (backend), HTML/CSS (frontend)
- Uses a trained model saved as `loan_model.pkl`
- Supports realistic data simulation with 1000+ records

---

## 🚀 Features

- Real-time prediction using a trained ML model
- Responsive and elegant UI
- Robust error handling (no crashes on invalid input)
- Organized Flask structure with templates and static files
- Modular code for easy enhancements

---

## 🧠 ML Model Info

- **Algorithm Used**: Logistic Regression
- **Dataset Size**: 1,000 records
- **Features**:
  - Gender, Married, Dependents, Education
  - Self_Employed, Income, LoanAmount, Loan_Amount_Term
  - Credit_History, Property_Area
 LoanApprovalApp/
│
├── app.py                  # 🎯 Main Flask application
├── loan_model.pkl          # 🤖 Trained machine learning model (Pickle format)
├── loan_data_large.csv     # 📊 Dataset with 1000+ realistic loan records
│
├── templates/              # 🎨 HTML templates
│   ├── index.html          # 👉 Loan prediction form page
│   └── home.html           # (Optional) Landing/intro page
│
├── static/                 # 💅 Static files (CSS, images, JS)
│   └── style.css           # 📁 Styling for the frontend UI
│
├── requirements.txt        # 📦 Python package dependencies
└── README.md               # 📘 Project overview and usage instructions

Screenshots
<img width="1895" height="958" alt="Screenshot 2025-07-18 143207" src="https://github.com/user-attachments/assets/14197159-5265-401c-8a61-7eb25c017ca1" />
<img width="1901" height="955" alt="Screenshot 2025-07-18 143239" src="https://github.com/user-attachments/assets/f21af1a4-53f9-40ff-91ed-8960d6d9f25e" />



