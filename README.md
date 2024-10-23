# Lending Club Case Study
Outline
This project analyzes historical loan data from a finance company to identify key factors influencing loan default rates. The goal is to develop an efficient and accurate methodology to determine whether an applicant's loan should be approved or rejected based on the likelihood of repayment or default.



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)



## General Information
- Project Background
  The project focuses on a finance company offering loans to urban customers. The challenge lies in assessing loan applications accurately to minimize business losses from either approving high-risk applicants or rejecting suitable ones.

- Business Problem
  The project aims to solve the problem of predicting whether a loan applicant will repay their loan or default. Incorrect decisions could result in significant financial losses for the company.

- Dataset
  The dataset consists of customer loan data with 111 columns and 39,717 rows, provided by the finance company. Key variables include annual income, loan amount, employment length, credit history, and loan status.
---

### Conclusions
- **Longer loan terms and higher interest rates**: Loans with a 60-month term and higher interest rates are more likely to default.
- **Higher default rates for non-homeowners**: Loans taken by renters and loans for small businesses or debt consolidation are riskier.
- **Loan amounts between $5,000 and $10,000**: These loans have the highest charge-off rates, indicating increased default risk for mid-range loan amounts.
- **Verification status and loan grade**: Unverified applicants, especially those with grades B & C, are more prone to defaulting.
- **Revolving credit utilization**: Applicants with higher revolving credit utilization have higher default risks.
- **Seasonal default trends**: Default rates peak in May and December, suggesting seasonal factors may influence repayment ability.

---

### Technologies Used
- **Python** for data loading, cleaning, and analysis
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
- **Jupyter Notebook** for executing the analysis

---
## Acknowledgements

- This project was inspired by real world business problem of banks. 



## Contact
Created by [@jeet-Suthar] jitendra suthar (me) and [@saurabh02]shaurabh Jain. 

