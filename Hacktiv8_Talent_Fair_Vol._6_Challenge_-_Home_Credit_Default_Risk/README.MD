# Hacktiv8_Talent_Fair_Vol._6_Challenge
This repository is about analysis and model building including data preprocessing, model definition and evaluation using machine learning methods related to Home Credit Default Risk Project

# Introduction
- Name: Ryan Risyadul Maruf
- Class: FTDS-RMT-Batch 019
- Dataset: `https://www.kaggle.com/competitions/home-credit-default-risk`
- Objective: Identify clients capable of repayment to prevent unnecessary rejections and to offer loans tailored with appropriate principals, maturities, and repayment calendars with Machine Learning methods.
- Project Title : Hacktiv8_Talent_Fair_Vol._6_Challenge_-_Home_Credit_Default_Risk.ipynb
- Project Description:

Many people struggle to get loans due to insufficient or non-existent credit histories. And, unfortunately, this population is often taken advantage of by untrustworthy lenders.
Home Credit strives to broaden financial inclusion for the unbanked population by providing a positive and safe borrowing experience. In order to make sure this underserved population has a positive loan experience, Home Credit makes use of a variety of alternative data--including telco and transactional information--to predict their clients' repayment abilities.
While Home Credit is currently using various statistical and machine learning methods to make these predictions, they're challenging Kagglers to help them unlock the full potential of their data. Doing so will ensure that clients capable of repayment are not rejected and that loans are given with a principal, maturity, and repayment calendar that will empower their clients to be successful.

Conclusion:
Based on the EDA findings and the model evaluation, here are some suggestions:
1. Pay attention to loan types: Cash loans have shown a higher repayment rate compared to revolving loans. It would be beneficial to focus more on cash loans and assess the risk associated with revolving loans.
2. Gender and unknown gender category: Male borrowers have a slightly higher repayment rate, while borrowers with unknown gender have a 0.0% repayment rate. Further investigation is needed to understand the reasons behind the unknown gender category and how it affects loan repayment. Collecting more information or finding alternative ways to handle missing gender data may be necessary.
3. Consider car and real estate ownership: Borrowers without car and real estate ownership have shown slightly higher repayment rates. These factors could be indicative of stability and financial responsibility. Incorporating car and real estate ownership as features in the models may improve their performance.
4. Analyze income types: Income types, such as individuals on maternity leave having high repayment rates, while businessmen and students having 0.0% repayment rates, provide valuable insights. Explore the underlying factors that contribute to these patterns and consider creating specific categories or features based on income types.
5. Education levels and family statuses: Lower education levels have shown higher repayment rates, while certain family statuses exhibit different loan repayment rates. Review the potential reasons behind these observations and consider how education and family status can be used as predictors in the models.
6. Occupation types: Different occupation types have varying loan repayment rates. Investigate further to understand the specific characteristics and behaviors associated with each occupation type. This information can be valuable in refining the risk assessment process.
7. Explore organizational types: Loan repayment rates vary across organizational types. Obtain additional details about the organizational types to identify any patterns or correlations that can be incorporated into the models.

In summary, the combination of EDA findings and model evaluation provides valuable insights for improving risk assessment and decision-making in the lending industry. By considering the identified factors and suggestions, lenders can make more informed decisions and enhance their loan approval processes to mitigate risks.
