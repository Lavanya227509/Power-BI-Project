# Loan Approval Prediction – Power BI Dashboard

## 📊 Project Overview
This project analyzes a loan dataset containing **500 customer records** using **Microsoft Power BI**.  
The dashboard helps understand customer demographics, financial details, loan behavior, and loan approval status.

## 🎯 Objectives
- Analyze customer demographic details such as age, gender, city, education, and marital status  
- Examine annual income and employment type distribution  
- Analyze loan amount, loan term, and credit score  
- Identify the relationship between credit score and loan approval  
- Compare loan approval and rejection rates across customer groups  
- Build an interactive Power BI dashboard for loan analysis  

## 📁 Dataset
**File:** `loan_approval_dataset_500.csv`  
**Records:** 500  
**Columns:** 12  

### Columns
| Column | Type | Description |
|---|---|---|
| CustomerID | Numerical | Unique customer ID |
| Age | Numerical | Customer age |
| Gender | Categorical | Male / Female |
| City | Categorical | Customer city |
| Education | Categorical | Education qualification |
| MaritalStatus | Categorical | Marital status |
| EmploymentType | Categorical | Employment type |
| AnnualIncome | Numerical | Yearly income |
| LoanAmount | Numerical | Requested loan amount |
| CreditScore | Numerical | Credit score |
| LoanTermMonths | Numerical | Loan term in months |
| LoanStatus | Categorical | Approved / Rejected |

## 🛠 Tools Used
- Microsoft Power BI Desktop  
- Microsoft Excel / CSV  
- DAX Measures  

## 📈 Dashboard Pages
1. **Loan Overview** – Total customers, loan amount, credit score, approval rate  
2. **Customer Analysis** – Gender, city, education, income, employment  
3. **Credit & Risk Analysis** – Credit score, loan status, loan amount  

## 🧮 Key DAX Measures
```DAX
Total Customers = COUNT(loan_approval_dataset_500[CustomerID])
