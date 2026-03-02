# churn_Data
 Customer Churn Analysis: Turning Data into Retention Strategies 🚀
I recently completed a deep-dive analysis on customer churn for a telecom company. Here’s a structured breakdown of the project, key insights, and actionable recommendations.

**📋 Project Overview**
Analyzed customer churn behavior using a dataset containing demographic, account, and service information. The goal was to identify patterns and drivers behind customer attrition to help the business reduce churn and improve customer lifetime value.

**🎯 Project Objectives**
Identify key factors influencing churn
Quantify relationships between variables (tenure, charges, contract type, etc.)
Visualize churn patterns across customer segments
Deliver data-driven recommendations to reduce churn

**🧹 Data Cleaning & Highlights**
Handled missing values (e.g., total charges for new customers)
Encoded categorical variables (contract, payment method, internet service)
Removed outliers and verified data integrity
Created new features like tenure groups for better segmentation

**Highlights:**
Clean, structured dataset ready for EDA
Balanced representation across customer types

**🔍 Key Findings & Visualizations**
**1. Correlation Matrix**
Tenure vs. Total Charges: Strong positive correlation (0.83) – longer tenure = higher total revenue.
Tenure vs. Churn: Negative correlation (-0.35) – loyalty increases with time.
Monthly Charges vs. Churn: Mild positive correlation (0.19) – higher monthly bills slightly increase churn risk.
Total Charges vs. Churn: Negative correlation (-0.20) – customers who’ve paid more overall are less likely to leave.

**2. Box Plot Insights**
Churn vs. Monthly Charges: Churned customers tend to pay higher monthly charges.
Churn vs. Tenure: Churned customers have significantly shorter tenure – the first few months are critical.

**3. Categorical Breakdowns**
**Contract Type:**
Month-to-month: 2,150 non-churn / 1,650 churn (high risk)
One year: 1,300 / 200 (low risk)
Two year: 1,700 / 50 (very low risk)

**Internet Service:**
Fiber optic: 1,800 / 1,250 (high churn)
DSL: 1,900 / 450 (moderate)
No internet: 1,750 / 100 (very low churn)

**Payment Method:**
Electronic check: 1,250 / 1,100 (highest churn)
Mailed check: 1,250 / 400
Bank transfer (auto): 1,200 / 350
Credit card (auto): 1,150 / 300

**4. Tenure & Charge Distributions**
Early tenure groups (0–20 months) have higher customer counts and show more variability in charges – prime targets for retention efforts.

**🛠 Tools & Technologies Used:**
• Python (Pandas, NumPy)
• Data Visualization (Matplotlib, Seaborn)
• Data Preprocessing & Feature Engineering
• Exploratory Data Analysis (EDA)

## 🤝 Connect With Me
<p align="center">
  <a href="mailto:nadakhaledmahmoud412@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-Contact_Me-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>

  <a href="https://www.linkedin.com/in/nada-khaled-rashad/">
    <img src="https://img.shields.io/badge/LinkedIn-Lets_Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
</p>
