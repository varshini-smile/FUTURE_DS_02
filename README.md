# FUTURE_DS_02
AnalyzeD customer data to identify churn patterns, key retention drivers, and customer lifetime trends for a subscription-based business.

**Telco Customer Retention & Churn Analysis Dashboard**

**Project Overview**

This project focuses on analyzing customer retention and churn behavior using the Telco Customer Churn dataset. The objective was to identify why customers leave the platform, determine which customer segments are most likely to churn, understand customer lifetime patterns, and provide actionable recommendations to improve customer retention. Data cleaning was performed using Microsoft Excel, followed by dashboard development and analysis in Power BI. The final dashboard provides valuable insights into customer behavior and supports data-driven decision-making for customer retention strategies.


---

**Data Cleaning Process (Excel)**

The dataset was cleaned and prepared in Microsoft Excel before being imported into Power BI.

Checked for duplicate customer records using the Customer ID field.

No duplicate customer IDs were identified.

Identified blank values in the TotalCharges column.

Replaced missing TotalCharges values for customers with zero tenure.

Converted TotalCharges from text format to numeric format.

Verified data consistency and corrected data types where required.

Created additional analytical columns:

ChurnFlag

ActiveFlag

TenureGroup

RevenueSegment


Validated the dataset to ensure it was free from errors and ready for analysis.



---

**Tools Used**

Microsoft Excel – Data Cleaning and Preparation

Power BI Desktop – Data Analysis and Dashboard Development

GitHub – Project Documentation and Version Control



---

**Key Performance Indicators (KPIs)**

The dashboard includes the following KPIs:

Total Customers

Active Customers

Churned Customers

Churn Rate (%)

Average Customer Tenure


These KPIs provide a quick overview of customer retention performance and overall churn behavior.


---

**Dashboard Visuals**

KPI Cards

Total Customers

Active Customers

Churned Customers

Churn Rate (%)

Average Tenure


Churn Distribution

Donut Chart displaying retained versus churned customers.


Churn by Contract Type

Clustered Bar Chart comparing churn rates across different contract plans.


Churn by Internet Service

Bar Chart analyzing churn behavior across internet service categories.


Customer Lifetime Pattern

Column Chart showing churn distribution across tenure groups.


Payment Method Analysis

Bar Chart examining churn patterns across payment methods.


Interactive Filters

Gender

Contract Type

Internet Service

Payment Method



---

**Business Questions & Answers**

1. Why are customers leaving the platform?

The analysis indicates that customers are primarily leaving due to short-term contractual commitments, limited service engagement, and shorter customer lifetimes. Customers with Month-to-Month contracts show significantly higher churn rates compared to customers on long-term contracts. Additionally, customers without additional support services such as Tech Support and Online Security are more likely to discontinue their subscriptions.

2. Which customer segments are most likely to churn?

The highest churn rates are observed among:

Customers with Month-to-Month contracts

Customers with shorter tenure periods

Fiber Optic internet service users

Customers with higher monthly charges

Customers who do not utilize additional support or security services


These customer groups represent the highest-risk segments and should be prioritized in retention strategies.

3. How long do customers typically stay active?

Customer lifetime analysis shows that a significant proportion of churn occurs within the first 12 months of service. Customers who remain active beyond two years exhibit considerably stronger loyalty and lower churn rates. This suggests that the first year of the customer journey is the most critical period for retention efforts.

4. What actions can improve customer retention?

Several actions can improve customer retention:

Encourage customers to move from Month-to-Month plans to long-term contracts.

Strengthen onboarding and customer engagement during the first year of service.

Promote value-added services that increase customer satisfaction.

Develop targeted retention campaigns for high-risk customer segments.

Monitor customer behavior and proactively address churn indicators before customers leave the platform.



---

**Key Insights**

Month-to-Month contracts have the highest customer churn rates.

Most customer attrition occurs within the first year of service.

Customers with longer tenure periods demonstrate significantly higher retention.

Fiber Optic internet users show relatively higher churn behavior.

Long-term contracts contribute to stronger customer loyalty.

Customer engagement during the early stages of the subscription lifecycle plays a critical role in retention.



---

**Recommendations**

Improve Customer Onboarding

Implement stronger onboarding programs and customer support initiatives during the first twelve months of service to reduce early-stage churn.

Promote Long-Term Contracts

Offer discounts, loyalty rewards, and special incentives to encourage customers to choose annual or multi-year subscription plans.

Increase Customer Engagement

Provide personalized communication, service updates, and customer success initiatives to strengthen relationships and improve customer satisfaction.

Target High-Risk Customers

Develop retention campaigns focused on customers with short tenure, Month-to-Month contracts, and other high-risk characteristics identified during the analysis.

Monitor Churn Trends Continuously

Leverage dashboard insights to regularly track churn behavior and respond proactively to changing customer patterns.


---

**Conclusion**

This project successfully analyzed customer retention and churn behavior using the Telco Customer Churn dataset. Through data cleaning, visualization, and business analysis, the project identified key factors influencing customer attrition and highlighted opportunities for improving retention. The interactive Power BI dashboard provides meaningful insights that can support business decision-making and contribute to long-term customer loyalty.


---

**Dashboard Preview**

<img width="1289" height="846" alt="dashboard" src="https://github.com/user-attachments/assets/f15f7626-645d-4004-b179-577a514f4b94" />



---

**Task 2 Dataset collection**




---

**Project Outcome**

The project delivered a comprehensive customer retention and churn analysis solution using Excel and Power BI. The dashboard effectively highlights customer behavior patterns, churn trends, customer lifetime characteristics, and business opportunities for improving retention. The insights generated from this analysis can help organizations reduce customer attrition, improve customer satisfaction, and support data-driven strategic planning.
