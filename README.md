
# Bank Customers Churn Analysis

This project analyzes customer churn within a dataset of 10,000 bank customers. The analysis focuses on identifying key factors such as age, tenure, salary, and membership activity that influence customer retention. Recommendations are provided to reduce churn and enhance loyalty.

![Dashboard](https://github.com/Olowookere-Abidemi/Bank-Customers-Churn-Analysis/blob/main/BANK%20CHURN%20DASHBOARD.png)

---

## **Data Overview**

- **Dataset Source:** [Kaggle](https://www.kaggle.com)
- **Dataset Size:** 10,000 rows × 13 columns
- **Key Attributes:**  
  - Customer demographics  
  - Account activity  
  - Financial details  
  - Churn behavior  

---

## **Data Preparation**

### **Data Profiling**
- Reviewed column attributes to identify patterns in customer churn.  
- Examined distributions of key variables such as age, tenure, and product usage.

### **Data Cleaning Steps**
1. **Renaming Columns:** Simplified column headers for better readability.  
2. **Binary Value Conversion:** Replaced binary values (1/0) in columns like `Exited`, `Active Member`, and `Has Credit Card` with "Yes" and "No."  
3. **Age Grouping:**  
   - Created an `Age Group` column by categorizing ages into ranges:  
     - 18–27, 28–37, 38–47, 48–57, 58–67, and 68+.  
   - Achieved using the `SWITCH(TRUE)` function in Power BI.  
4. **Estimated Salary Grouping:**  
   - Added a `Salary Group` column to classify customers into ranges:  
     - $0–$50,000, $50,000–$100,000, $100,000–$150,000, and $150,000–$200,000.  

---

## **Key Insights**

### **Customer Demographics**
- **Gender:**  
  - Male customers: 5,457  
  - Female customers: 4,543  
- **Geography:**  
  - France: 5,014 customers  
  - Germany: 2,509 customers (highest churn: 814)  
  - Spain: 2,477 customers  
- **Churn by Age Group:**  
  - Highest churn: 38–47 years (786 customers)  
  - Followed by: 48–57 years (583 customers)  
  - Lowest churn: Ages under 28 or over 68  
- **Churn by Tenure:**  
  - Customers with 1–5 years tenure churn more frequently.  
- **Churn by Salary Range:**  
  - Highest churn: $150,000–$200,000 range (527 customers)  
  - Lowest churn: $0–$50,000 range (489 customers)  

### **Engagement and Membership**
- **Products:**  
  - Customers with 1 product: Highest churn (1,409 churned)  
  - Customers with 2 products: Moderate churn (348 churned)  
  - Customers with 3+ products: Low churn rates  
- **Active Membership:**  
  - Non-active members: Higher churn rate (63.92%)  
  - Active members: Lower churn rate (36.08%)  
- **Overall Churn Rate:**  
  - 20.37% (2,037 churned out of 10,000 customers)  

---

## **Recommendations**

### **Retention Strategies**
1. **Age-Specific Programs:**  
   - Focus on high-churn groups (38–57 years).  
2. **Regional Engagement:**  
   - Address churn in Germany and France with region-specific retention initiatives.  
3. **Tenure-Based Loyalty Programs:**  
   - Implement loyalty rewards for customers in their first five years.

### **Financial Initiatives**
4. **Salary-Based Offers:**  
   - Develop tailored financial products for customers earning $150,000–$200,000.  

### **Product Diversification**
5. **Encourage Adoption of Additional Products:**  
   - Provide incentives for customers with 1–2 products to explore more offerings.

### **Membership Campaigns**
6. **Convert Non-Active Members to Active:**  
   - Launch engagement programs with exclusive benefits for non-active members.

### **Geographic Analysis**
7. **Region-Specific Research:**  
   - Investigate factors driving churn in Germany and France to inform localized strategies.


## **Conclusion**

This analysis highlights critical factors influencing churn, including age, tenure, salary, and product engagement. By leveraging the insights from the Power BI dashboard and implementing the recommended strategies, the bank can reduce churn, enhance customer retention, and foster long-term loyalty.

---
```
