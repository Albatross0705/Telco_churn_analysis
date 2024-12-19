Summary

### **Data Preparation**
1. **Data Loading and Cleaning**:
   - The dataset was imported, and its structure (shape, columns, and data types) was explored.
   - **TotalCharges Column**:
     - Blank values in "TotalCharges" (likely due to new customers with no recorded charges) were replaced with `0` and converted to a numeric data type for further analysis.
   - **Duplicate Records**:
     - No duplicates were found in the "customerID" column, ensuring the data's integrity.
   - **SeniorCitizen Conversion**:
     - Converted 1/0 values in "SeniorCitizen" into "yes" and "no" for easier interpretation.

---

### **Churn Analysis**
1. **Overall Churn Rate**:
   - The dataset shows that **26.54% of customers have churned**, as visualized in a pie chart.
   - This indicates that nearly 1 in 4 customers is leaving, which is a significant proportion and needs attention.

2. **Gender-wise Churn**:
   - Churn rates are consistent across genders, indicating no gender-specific behavior influencing churn.

3. **Senior Citizen Analysis**:
   - Senior citizens show a higher likelihood of churn compared to non-senior citizens.
   - A **stacked bar plot** showed the distribution of churn among senior citizens, with percentages provided for clearer understanding.

---

### **Tenure and Churn**
- A histogram of tenure revealed the following trends:
  - Customers with **short tenures (1-2 months)** are more likely to churn.
  - Customers with **long tenures (multiple years)** tend to stay loyal.
  - This highlights that early customer retention efforts (e.g., improved onboarding, incentives for early renewals) could reduce churn rates significantly.

---

### **Contract Type Analysis**
- Customers with **month-to-month contracts** are much more likely to churn compared to those with **1-year** or **2-year contracts**.
- Insights:
  - Month-to-month contracts lack long-term commitment, increasing the risk of customers leaving.
  - Offering discounts or incentives for longer-term contracts could help reduce churn.

---

### **Service Usage Analysis**
The following observations were made for service usage and churn rates:

1. **PhoneService**:
   - Most customers use this service, but those with additional lines (MultipleLines) are more likely to churn.

2. **InternetService**:
   - Customers with **fiber optic internet** have a significantly higher churn rate than those using DSL or no internet.
   - This could indicate dissatisfaction with fiber optic service quality or pricing.

3. **Additional Services**:
   - Customers without **OnlineSecurity, OnlineBackup, DeviceProtection, or TechSupport** services are more likely to churn.
   - Insights:
     - These services may contribute to customer satisfaction and retention.
     - Promoting bundled packages or highlighting the value of these services might reduce churn.

4. **Streaming Services**:
   - Customers with **StreamingTV and StreamingMovies** show slightly higher churn rates, suggesting these may not be key differentiators for retention.

---

### **Payment Method Analysis**
- Payment methods have a noticeable impact on churn rates:
  - **Electronic Check** users churn significantly more than customers using credit cards, bank transfers, or mailed checks.
  - This may indicate that electronic check users face issues like transaction friction, hidden fees, or poor customer experience.
- Suggested Actions:
  - Improve the experience for electronic check users or encourage them to switch to other payment methods via discounts or promotions.

---

### **Key Takeaways and Recommendations**
1. **Target High-Churn Groups**:
   - Focus retention strategies on senior citizens, customers with month-to-month contracts, and electronic check users.
   - Proactively engage with new customers during their first few months to prevent churn.

2. **Promote Long-Term Contracts**:
   - Offer discounts or perks for customers who switch from month-to-month to longer-term contracts.

3. **Improve Fiber Optic Service**:
   - Investigate and address customer dissatisfaction with fiber optic internet to reduce churn in this segment.

4. **Encourage Service Add-ons**:
   - Customers lacking services like OnlineSecurity or TechSupport are more likely to churn. Promote these services with bundled packages or special offers.

5. **Enhance Payment Experience**:
   - Address issues with electronic check payments and incentivize customers to switch to more stable payment methods like credit cards or bank transfers.
