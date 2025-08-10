
# Project Title - Customer Churn Analysis using SQL, Python and PowerBI

# Overview:
This project explores customer churn patterns in a telecom company using a combination of SQL, Python, and Power BI. The goal is to identify factors influencing churn and help businesses take data-driven actions to retain customers.

# Objectives:

1.Identify high-risk customer segments.

2.Analyze churn trends based on demographics, billing, contracts, and service usage.

3.Provide actionable insights to reduce churn.

# Tools Used:
1.SQL: Data extraction and cleaning

2.Python (Pandas, Matplotlib, Seaborn): EDA, Statistical summaries, feature exploration and visualization

3.Power BI: Dashboard development for stakeholder presentation and business insights

# Data Source & Size:
Telecom customer dataset with 7043 records and multiple features such as demographics, service usage, billing, and churn status.

# Key Insights & Visualizations:

A.Churn Overview

1.Total Customers: 7043

2.Churned Customers: 1869

3.Overall Churn Rate: 26.54%, indicating a relatively high loss of customers.

#  Main Highlights 

Seniors Are at Higher Risk:35.88% of seniors churn vs an overall churn rate of 24.38% → this segment needs targeted retention strategies (loyalty programs, senior-friendly plans).

Dependents Churn Less:Only 14.60% churn among dependents, meaning they are a relatively loyal group — possibly due to bundled family plans.

Partners Have Moderate Churn:Churn among customers with partners is 18.89%, lower than the overall churn rate — suggesting a stability factor.

Gender Does Not Significantly Influence Churn:Both male and female churn counts are almost equal (~1.8K each).

Contract Type Is a Major Churn Driver:Month-to-month contracts have extremely high churn (~69% of churners are on this plan).
Yearly and two-year contracts retain customers better — possibly due to lock-in benefits and discounted pricing.

Payment Method Strongly Influences Churn:Electronic checks have the highest churn rate, likely due to customers with lower commitment or higher dissatisfaction.
Auto-pay methods (credit card, bank transfer) have much lower churn — indicating convenience reduces attrition.

Tenure Has a Strong Negative Correlation with Churn:New customers (0–20 months) churn the most, with rates dropping sharply as tenure increases — suggesting early engagement is critical.

Service Attributes Affect Churn:Customers without Online Security or Tech Support churn more — likely due to perceived lack of value-added services.
StreamingTV and StreamingMovies users show higher churn — possibly due to content dissatisfaction or competition from OTT services.



# Impact:

The analysis provides data-driven direction for customer retention strategies and helps identify segments most at risk of churn. The interactive dashboard ensures stakeholders can slice and drill data by segment, tenure, payment mode, etc., making it a practical tool for business decisions.


