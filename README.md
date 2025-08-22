# Loan Data Analysis

This project explores a **Loan Dataset** containing 20,000 loan applications with 36 features such as applicant demographics, financials, credit history, loan details, and approval status.  
The analysis is performed using **Pandas** to answer medium-to-hard level analytical questions.

---

## 📊 Dataset Overview

The dataset consists of **36 columns** capturing applicant details, financial metrics, and loan information.

### Column Descriptions

| Column Name                 | Description                              | Type (Categorical/Continuous) | Potential Use Case |
|-----------------------------|------------------------------------------|--------------------------------|--------------------|
| ApplicationDate             | Date of loan application                | Categorical (Date)             | Trend analysis, seasonality |
| Age                         | Age of applicant                        | Continuous                     | Age group risk profiling |
| AnnualIncome                | Annual income of applicant              | Continuous                     | Loan affordability |
| CreditScore                 | Credit score of applicant               | Continuous                     | Creditworthiness assessment |
| EmploymentStatus            | Employment type (Employed, Unemployed)  | Categorical                    | Loan eligibility check |
| EducationLevel              | Education qualification                 | Categorical                    | Risk analysis by education |
| Experience                  | Years of work experience                | Continuous                     | Stability measurement |
| LoanAmount                  | Loan amount requested                   | Continuous                     | Loan approval decisions |
| LoanDuration                | Duration of loan (months)               | Continuous                     | Risk & EMI calculation |
| MaritalStatus               | Marital status                          | Categorical                    | Household risk profiling |
| NumberOfDependents          | Number of dependents                    | Continuous (Discrete count)    | Financial burden analysis |
| HomeOwnershipStatus         | Home ownership type                     | Categorical                    | Asset-based risk measure |
| MonthlyDebtPayments         | Monthly debt obligations                | Continuous                     | Debt-to-income ratio |
| CreditCardUtilizationRate   | Credit card usage %                     | Continuous                     | Credit risk factor |
| NumberOfOpenCreditLines     | Active credit lines                     | Continuous (Discrete count)    | Credit exposure |
| NumberOfCreditInquiries     | Past credit inquiries                   | Continuous (Discrete count)    | Recent borrowing behavior |
| DebtToIncomeRatio           | Debt / Income ratio                     | Continuous                     | Risk scoring |
| BankruptcyHistory           | History of bankruptcies (0/1)           | Categorical (Binary)           | Default likelihood |
| LoanPurpose                 | Purpose of loan                         | Categorical                    | Risk by purpose |
| PreviousLoanDefaults        | Past defaults (0/1)                     | Categorical (Binary)           | Risk profiling |
| PaymentHistory              | Past payment behavior score             | Continuous                     | Credit risk measure |
| LengthOfCreditHistory       | Credit history length                   | Continuous                     | Reliability factor |
| SavingsAccountBalance       | Balance in savings account              | Continuous                     | Asset strength |
| CheckingAccountBalance      | Balance in checking account             | Continuous                     | Financial stability |
| TotalAssets                 | Total assets value                      | Continuous                     | Net worth analysis |
| TotalLiabilities            | Total liabilities value                 | Continuous                     | Debt exposure |
| MonthlyIncome               | Monthly income                          | Continuous                     | EMI affordability |
| UtilityBillsPaymentHistory  | Utility bills payment score             | Continuous                     | Payment discipline |
| JobTenure                   | Job tenure in years                     | Continuous                     | Employment stability |
| NetWorth                    | Net worth (Assets - Liabilities)        | Continuous                     | Financial health |
| BaseInterestRate            | Base interest rate assigned             | Continuous                     | Loan pricing |
| InterestRate                | Final interest rate applied             | Continuous                     | Risk-adjusted pricing |
| MonthlyLoanPayment          | Expected monthly loan installment       | Continuous                     | Repayment capacity |
| TotalDebtToIncomeRatio      | Extended debt to income ratio           | Continuous                     | Advanced risk profiling |
| LoanApproved                | Loan approval decision (0/1)            | Categorical (Binary)           | Target variable |
| RiskScore                   | Risk score assigned                     | Continuous                     | Loan risk modeling |

---

## 🔧 Tools Used

- **Python**
- **Pandas** for data manipulation
- **Matplotlib / Seaborn** (optional) for visualization
- **Jupyter Notebook / Colab** for analysis

---

## ❓ Pandas Analysis Questions

Here are 15 medium-to-hard level analysis questions implemented using Pandas:

1. What is the average loan amount for approved vs. not approved loans?  
2. Which employment status has the highest average annual income?  
3. Find the top 5 education levels by loan approval rate.  
4. Which marital status group has the highest risk score on average?  
5. Among applicants with previous loan defaults, what is their loan approval rate?  
6. Which loan purpose has the longest average loan duration?  
7. Find the correlation between credit score and risk score.  
8. Which age group (bins of 10 years) has the highest loan approval rate?  
9. Find the top 5 applicants with the highest net worth but rejected loans.  
10. For each home ownership status, what is the median debt-to-income ratio?  
11. Among applicants with bankruptcies, what is the average credit score?  
12. Find the month with the highest number of loan applications.  
13. Which combination of employment and education has the highest loan approval rate?  
14. What is the average interest rate difference between approved and not approved loans?  
15. Find the top 3 features most correlated with LoanApproved.  

---

## 🚀 Potential Use Cases

- Credit risk modeling  
- Loan approval prediction (classification models)  
- Customer segmentation based on financial stability  
- Default prediction and early warning systems  
- Interest rate optimization  
- Business insights for lending institutions  

---
