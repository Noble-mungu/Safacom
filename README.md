## Loan Default Risk Analysis
 Introduction
This repository contains the analysis and findings of loan default risk for the largest online loan marketplace, which facilitates personal loans, business loans, and financing of medical procedures. The primary goal is to identify risky loan applicants to reduce credit loss. Credit loss occurs when borrowers default on their loans, leading to financial loss for the company.

## Objectives
* Identify Risky Applicants: The main objective is to identify loan applicants who are likely to default. Reducing loans to these applicants will minimize the company's credit loss.
* Understand Driving Factors: The analysis aims to understand the key variables that indicate a high likelihood of default. This understanding will help in better portfolio management and risk assessment.
## Business Context
* Potential Loss of Business: Not approving loans to applicants who are likely to repay results in a loss of potential business for the company.
* Financial Loss: Approving loans to applicants who are likely to default can lead to significant financial loss.
## Key Factors in Loan Default
Based on the supplied dataset, the following driving factors have been identified as strong indicators of loan default:

## Loan Term:

* Average interest rates for defaulted applications are high.
* 12.38% for 36 months term.
* 15.75% for 60 months term.
## Grade:

* Default rates are high among high-risk loan applicants.
* Thorough vetting of high-risk loan applications is crucial.
# Loan Amount:

*The defaulter rate increases with the requested loan amount.
## Annual Income:

* Applicants with low (≤ 45K USD) and medium (45K-90K USD) annual incomes have a higher share of defaulted loans.
## Employment Length:

* The maximum number of defaulters have either 10+ years of experience or 0 to 2 years of experience.
* This aspect should be considered when lending loans.
## Loan Purpose:

* The top two reasons for loans are debt consolidation and credit card usage.
* Applications for these purposes should be carefully assessed.
## Methodology
The analysis involves Exploratory Data Analysis (EDA) to identify patterns and relationships between different variables and the likelihood of loan default. Understanding the types of variables and their significance is critical to this process.

## Recommendations
* Vetting Process: Implement a more thorough vetting process for high-risk loan applicants, especially those with high requested loan amounts and low to medium annual incomes.
* Interest Rates: Consider the loan term and associated interest rates when assessing loan applications.
* Employment Length: Pay attention to applicants' employment length, particularly those with very high or very low years of experience.
* Loan Purpose: Give special consideration to applications for debt consolidation and credit card purposes.
