# Loan-Approval-Predictioon-Model
Loan Approval Prediction Model Using Support Vector Machine 

🔍 Overview
This machine learning project predicts whether a loan application will be approved or not based on applicant details. The project leverages the Support Vector Machine (SVM) classification algorithm to make accurate predictions using a cleaned and feature-engineered dataset.

🎯 Objective
To build a robust classification model that automates the loan approval process and assists financial institutions in making faster and more accurate decisions.

🧠 Machine Learning Approach
Algorithm Used: Support Vector Machine (SVM)

Task Type: Binary Classification

Evaluation Metric: Accuracy Score

🛠️ Technologies & Tools
Python (Jupyter Notebook)

Libraries: pandas, numpy, matplotlib, seaborn, sklearn

IDE: Jupyter Notebook / Google Colab

📊 Dataset
Source: [Loan Prediction Dataset - open-source]

Features:

Gender, Married, Dependents, Education

ApplicantIncome, CoapplicantIncome, LoanAmount, Loan_Amount_Term

Credit_History, Property_Area

Target: Loan_Status (Y = Approved, N = Rejected)

🧼 Data Preprocessing
Handled missing values using imputation techniques

Applied label encoding to categorical features

Performed feature scaling for optimal SVM performance

📈 Model Building
Model: Support Vector Classifier (sklearn.svm.SVC)

Training/Test Split: 80/20

Results:

Training Accuracy: ~80.27%

Testing Accuracy: ~78.08%

📌 Key Insights
Credit history and applicant income were significant factors in approval decisions

Proper feature scaling and preprocessing were crucial for improving model accuracy

SVM performed well on this moderately imbalanced dataset
