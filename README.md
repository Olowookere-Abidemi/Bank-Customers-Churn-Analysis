# Bank-Customers-Churn-Analysis
This analysis explores customer churn in a bank's dataset of 10,000 customers, focusing on factors like age, tenure, salary, and membership activity. It identifies key trends in customer retention and provides recommendations to reduce churn and enhance loyalty.

![](https://github.com/Olowookere-Abidemi/Bank-Customers-Churn-Analysis/blob/main/BANK%20CHURN%20DASHBOARD.png)

_Data Source:_ The analysis used a dataset sourced from Kaggle. 

## Dataset Overview:

- 10,000 rows and 13 columns.
- Attributes covered customer demographics, account activity, financial information, and churn behavior.

## Data Preparation and Profiling

_Data Profiling:_

- Reviewed column attributes to understand customer patterns.
- Examined distributions of variables like age, tenure, and product use.

_Data Cleaning:_

- Renamed headers for clarity.
- Replaced binary values (1/0) with "Yes" and "No" in columns like "Exited," "Active Member," and "Has Credit Card."
- Used Power BI's Power Query to group customer age and estimated salary ranges and standardize labels (e.g., "Active/Non-Active").

## Data Analysis

_Age Grouping:_

- Created a new Age Group column by grouping customer ages into ranges using the SWITCH(TRUE) function:
- 18–27 years, 28–37 years, 38–47 years, 48–57 years, 58–67 years, and 68+ years.
- Allowed a clearer breakdown of churn rates across different age demographics.

_Estimated Salary Grouping:_

- Added an Estimated Salary Group column to classify customers into salary ranges:
- $0–$50,000, $50,000–$100,000, $100,000–$150,000, and $150,000–$200,000.
- Simplified analysis of salary-related trends in churn.

## Key Insights

_Customer Demographics:_

- _Gender:_ Male customers outnumber female customers (5,457 vs. 4,543).
- _Geography:_ France has the most customers (5,014), followed by Germany (2,509) and Spain (2,477). Germany has the highest churn rate (814 customers), followed closely by France (810).
- _Churn by Age Group:_ High churn in the 38–47 age group (786 customers), followed by 48–57 (583). Lower churn rates among customers younger than 28 or older than 68.
- _Churn by Tenure:_ Customers with 1–5 years tenure churn more frequently than those with longer tenures.
- _Churn by Estimated Salary:_ Most churn occurs in the $150,000–$200,000 range (527 customers), followed by $100,000–$150,000 (517). Lowest churn is seen in the $0–$50,000 range (489 customers).
- _Churn by Number of Products:_ Customers with 1 product have the highest churn (1,409 churned), followed by those with 2 products (348 churned). Customers with 3+ products show significantly lower churn rates.
- _Churn by Active Membership:_ Non-Active Members have a higher churn rate (63.92% or 1,302 churned). Active Members churn less (36.08% or 735 churned).
- _Overall Churn Rate:_ 20.37% churn rate: 2,037 out of 10,000 customers have exited.

## Recommendations

- _Retention Programs:_ Focus on high-churn age groups (38–57) and customers in Germany and France.
- _Tenure-Based Engagement:_ Implement loyalty programs targeting customers in their first five years of tenure.
- _Financial Strategy:_ Address churn in the $150,000–$200,000 salary range by offering tailored financial products.
- _Product Diversification:_ Encourage customers with 1–2 products to adopt additional services by offering incentives.
- _Active Membership Campaigns:_ Convert non-active members to active status with engagement programs and exclusive benefits.
- _Churn Analysis by Geography:_ Investigate region-specific factors contributing to churn in Germany and France.
- _Focus on Low-Churn Segments:_ Analyze practices among long-tenured and high-product users to replicate success across other segments.

## Conclusion

This analysis identifies critical factors driving churn, including demographics, tenure, and product engagement. The Power BI dashboard illustrates these findings and provides actionable insights to enhance customer retention strategies.
