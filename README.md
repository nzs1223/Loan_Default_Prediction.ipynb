# Loan Default Prediction

This project uses LendingClub loan data from 2007 to 2018 to predict the likelihood of loan default based on borrower financial features.

## 📊 Dataset

- Source: [LendingClub Accepted Loans (2007–2018Q4)](https://www.kaggle.com/datasets/wordsforthewise/lending-club)
- Used features:  
`loan_amnt`, `term`, `int_rate`, `grade`, `emp_length`, `home_ownership`, `annual_inc`, `purpose`, `dti`, `delinq_2yrs`, `revol_util`, `total_acc`, `application_type`

- Target variable:  
`loan_status` (`Fully Paid` = 0, `Charged Off` = 1)

## 🧪 Techniques Used

- Data Cleaning
- Handling Categorical Variables with `pd.get_dummies`
- Train/Test Split
- Random Forest Classifier
- Model Evaluation: Confusion Matrix, Classification Report, ROC AUC Score

## ✅ Results

- Classification Report:  
  > Precision/Recall ~0.84+ depending on split  
- ROC AUC Score: ~0.84–0.87

---

## ⚠️ Note
Dataset not included due to size. Please download it directly from Kaggle:
[LendingClub Accepted Loans Dataset](https://www.kaggle.com/datasets/wordsforthewise/lending-club)
