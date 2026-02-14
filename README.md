# Predictive Modeling for Lending Club Loan Defaults
> A large online loan marketplace, facilitating personal loans, business loans,  wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Objective: Developed a predictive model to identify high-risk loan applicants for a large online marketplace, aiming to minimize financial loss from defaults while maximizing credit availability.
- The Business Problem: Loan providers face a "cost of misclassification." Denying a "good" applicant results in lost interest revenue, while approving a "bad" applicant results in a total loss of principal. This project uses Exploratory Data Analysis (EDA) to pinpoint the strongest drivers of default.
- Dataset: The data contains records of loans issued, including fields such as issue month and loan amounts. The primary analysis revolves around the total number of loans issued per month.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Key Insights & Conclusions
- Credit Grading: Analysis confirms that internal "Grades" and "Sub-grades" remain the most reliable indicators of risk, though high-interest rates often correlate with higher default rates regardless of grade.
- Debt-to-Income (DTI): Applicants with a DTI ratio above a specific threshold (e.g., 20%+) showed a statistically significant increase in "Charged Off" status.
- Employment Length: Interestingly, borrowers with 10+ years of employment history did not always show lower default rates compared to mid-career borrowers, suggesting income stability is more complex than mere tenure.
- Annual Income: Low-income brackets combined with high loan amounts (high loan-to-income ratio) are the primary drivers of loan default.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - version 3.12.4
- Pandas - for data manipulation and analysis
- Matplotlib - for generating visualizations such as bar charts

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by financial data analysis and aims to provide practical insights to stakeholders in the lending industry.
- Special thanks to upgrad for providing loan datasets that enabled this analysis.


## Contact
Created by [@Pritammaacha] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
