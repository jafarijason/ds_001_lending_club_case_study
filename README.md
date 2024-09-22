# Lending Club Case Study
> A comprehensive exploratory data analysis (EDA) of Lending Club loan data from 2007 to 2011 to identify key drivers behind loan defaults and provide actionable recommendations.


## Table of Contents
* [How to run](#how-to-run-project)
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Additional Resources](#additional-resources)


## How to run project
```
virtualenv venv
source venv/bin/activate
pip install -r requirements.txt
```

```
jupyter notebook \
    --notebook-dir="." \
    --ip=0.0.0.0 --port=3225
```

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This project performs an exploratory data analysis (EDA) on Lending Club loan data from 2007 to 2011.
- The goal is to analyze loan attributes and consumer data to identify key factors that influence loan default and to develop recommendations to minimize credit losses.
- **Business Problem**: Lending companies face a significant financial loss from borrowers who default. This analysis aims to discover patterns in the data that indicate a higher likelihood of default, allowing for better decision-making on loan approvals and conditions.
- **Dataset**: Loan data from Lending Club, including loan amounts, interest rates, borrower income, loan status (fully paid, charged off, etc.), and other relevant features.


## Conclusions
1. **Loan Amount**: Higher loan amounts are correlated with a greater likelihood of default. Borrowers with larger loan requests pose a higher risk.
2. **Interest Rate**: Higher interest rates correspond to a higher chance of default. Loans with higher rates may indicate higher-risk borrowers.
3. **Debt-to-Income Ratio (DTI)**: A higher DTI ratio is a key indicator of increased default risk, as borrowers with more debt relative to their income are more likely to default.
4. **Annual Income**: Borrowers with lower annual incomes tend to default more often. Higher-income individuals show better repayment rates.
5. **Verification Status**: Borrowers whose income was not verified have a higher risk of default. Verified income correlates with lower default rates.
6. **Home Ownership**: Renters have a higher default rate compared to homeowners or those with mortgages.
7. **Loan Grades**: Loans with lower grades (C, D, etc.) are more likely to default than loans with higher grades (A, B).

## Insights and Recommendations
Based on the analysis, the following recommendations can help Lending Club reduce the risk of defaults and improve profitability:
- **Stricter Loan Amount Criteria**: Introduce stricter evaluation or lower loan amounts for high-risk borrowers requesting larger loans.
- **Interest Rate Adjustment**: Rethink the interest rate policy. Higher rates are associated with higher default risk, so balancing rates with the borrower's risk profile is essential.
- **Cap DTI Ratio**: Introduce a maximum acceptable DTI ratio to reduce the number of risky borrowers being approved.
- **Mandatory Income Verification**: Enforce income verification as part of the loan approval process to lower the default rate.
- **Home Ownership Consideration**: Consider offering different loan packages or conditions based on home ownership status, as renters have a higher risk of default.
- **Grade-Based Restrictions**: Loans with lower grades should either have stricter lending conditions or be rejected to reduce the default risk.


## Technologies Used
- **Python**: Data analysis and visualization.
- **Pandas**: Data manipulation and cleaning.
- **Matplotlib & Seaborn**: Data visualization.
- **NumPy**: Numerical operations.
- **Jupyter Notebook**: Development environment for the project.



## Contact
Created by [@jafarijason](https://github.com/jafarijason) - feel free to reach out for collaboration or further inquiries.  
Connect with me on [LinkedIn](https://www.linkedin.com/in/jasonjafari/).


## Additional Resources
- [Project Presentation](https://github.com/jafarijason/ds_001_lending_club_case_study/blob/main/Presentation.pdf)
