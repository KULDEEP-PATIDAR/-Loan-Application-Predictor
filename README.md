# Loan-Application-Predictor
<img width="300" height="168" alt="image" src="https://github.com/user-attachments/assets/abcc1376-ab51-47fa-ad18-2b8a10aaccc1" />

📌 Project Overview

The Loan Application Predictor is an end-to-end Machine Learning project that predicts whether a loan application will be approved or rejected based on applicant demographic and financial details.
The project follows the complete Machine Learning Development Life Cycle (MLDLC) from data understanding to model saving and deployment readiness.

🎯 Objective

To build a reliable classification model that helps financial institutions:
Reduce manual loan approval effort.
Minimize risk by identifying eligible applicants.
Improve decision-making using data-driven insights.

📌 Tech Stack

Python,
Pandas, NumPy,
Scikit-learn,
XGBoost,
Matplotlib, Seaborn,
Joblib.

📊 Dataset

Source: Dphi Official Dataset.
Features: 13 variables including demographic, income, loan, and credit history details.
Target Variable: Loan_Status (0 = Rejected, 1 = Approved).

🔍 Exploratory Data Analysis (EDA)

Analyzed data distribution, missing values, and feature types.
Studied class balance of loan approval vs rejection.
Identified Credit_History, ApplicantIncome, and LoanAmount as strong predictors.
Visualized relationships using bar plots, histograms, and box plots.

🛠 Data Preprocessing

Removed irrelevant columns.
Handled missing values using statistical imputation.
Converted categorical variables into numerical form.
Treated outliers where necessary.

Models Trained & Evaluated

<img width="479" height="192" alt="image" src="https://github.com/user-attachments/assets/ce588d48-2687-4a3b-95ec-d3714f1fce1b" />

 📌 Final Model Selected: Logistic Regression

Highest F1-Score.
Best overall balance between precision and recall.

🧩 Pipeline & Best Practices

Implemented Scikit-learn Pipeline with ColumnTransformer.
Combined preprocessing and model into one single object.

💾 Model Saving

Final trained pipeline saved using joblib.
Ready for deployment without retraining.

