# Loan-Application-Predictor
<img width="300" height="168" alt="image" src="https://github.com/user-attachments/assets/abcc1376-ab51-47fa-ad18-2b8a10aaccc1" />

📌 Project Overview

The Loan Application Predictor project focuses on building a machine learning–based loan approval prediction system to identify whether a loan applicant is high-risk or low-risk. Multiple supervised classification algorithms are implemented and evaluated to improve decision-making efficiency for financial institutions.

The project emphasizes data preprocessing, handling class imbalance, feature encoding, model training, and performance evaluation.


📌 Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn


📊 Dataset Description

- Total records: 252,000
- Total features: 13
- Target variable: Risk_Flag
- 0 → Low risk
- 1 → High risk
- Features
  - Id – Unique identifier
  - Income – Applicant income
  - Age – Applicant age
  - Experience – Professional experience
  - Married/Single – Marital status
  - House_Ownership – Owns a house or not
  - Car_Ownership – Owns a car or not
  - Profession – Applicant profession
  - CITY – City of residence
  - STATE – State of residence
  - CURRENT_JOB_YRS – Years in current job
  - CURRENT_HOUSE_YRS – Years at current residence
  - Risk_Flag – Loan risk indicator

⚙️ Data Preprocessing & Feature Engineering

- Label Encoding
  - Applied to Married/Single and Car_Ownership
- One-Hot Encoding
  - Applied to House_Ownership
- High Cardinality Encoding
  - Count Encoding used for Profession, CITY, and STATE
- Class Imbalance Handling
  - Severe imbalance addressed using Random UnderSampling

 📌 All models are treated as binary classification problems.

- Logistic Regression
- Gaussian Naive Bayes
- Decision Tree Classifier
- Random Forest Classifier

Each model was trained, tuned, and evaluated under both original and undersampled datasets.

📈 Model Performance Summary

<img width="902" height="386" alt="image" src="https://github.com/user-attachments/assets/0326ad87-876e-4d04-b771-6ad208564740" />

⚠️ Key Challenges

- Highly imbalanced dataset
- High dimensional categorical features
- Long training time for tree-based models
- Low recall for minority class (high-risk applicants)


