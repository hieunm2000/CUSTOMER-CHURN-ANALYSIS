
# [POWER BI] CUSTOMER-CHURN-ANALYSIS

## I. Introduction

### 1. Introduction to Dataset

- User churn refers to the phenomenon of customers or users of a product or service disengaging or ceasing to use it over time, which can be detrimental to the business.
- Understanding the reasons why users churn can help companies develop strategies to retain their customers and improve their overall product or service.
- The dataset includes a **dim table** containing information about users of a telecommunications network company, including fields of demographic information and information related to the **user's churn**.

### 2. Dataset Overview

- The dataset consists of only one table and the columns is:

  - Customer ID
  - Churn Label
  - Account Length (in months)
  - Local Calls
  - Local Mins
  - Intl Calls
  - Intl Mins
  - Intl Active
  - Extra International Charges
  - Customer Service Calls
  - Avg Monthly GB Download
  - Unlimited Data Plan
  - Extra Data Charges
  - State
  - Phone Number
  - Gender
  - Age
  - Under 30
  - Group
  - Number of Customers in Group
  - Device Protection & Online Backup
  - Contract Type
  - Payment Method
  - Monthly Charge
  - Total Charges
  - Churn Category
  - Churn Reason
  - Tenure Bin
  - Age Condition
  - Total Call
 
  
### 3. Project Objectives

  #### The Senior Manager seeks insights into the company's sales performance to:
  - Assess Business Performance: Evaluate revenue, profit, and return rates across different regions and product categories.
  - Identify Market Expansion Opportunities: Discover high-potential regions for future growth.
  - Determine Strategic Products: Identify top-performing products based on sales and profitability.
  - Analyze Product Returns: Understand reasons for returns and minimize their impact on business revenue.

## II. Design Thinking Method

**Here are the five steps of design thinking:**

### Step 1 - Empathize
  #### Goal: Understanding the needs and challenges of stakeholders is crucial. The primary users of this dashboard include:
  - **Business Analysts & Data Scientists:** Need insights into customer churn trends, factors influencing churn, and key demographics.
  - **Customer Support & Retention Teams:** Require actionable data to mitigate churn risks.
  - **Executives & Decision Makers:** Seek high-level overviews and key performance indicators (KPIs) for strategic decision-making.
    
### Step 2 - Define
  #### "How can we identify and analyze the key factors contributing to customer churn to enable proactive retention strategies?"

  - Key Questions to Address:
    - What are the main reasons customers churn?
    - What demographic or service factors contribute to churn?
    - How does payment method or contract type influence churn rate?
    - Can we predict potential churners based on historical data?
   
      
### Step 3 - Ideate

  - Possible solutions include:

      - Customer Segmentation: Categorizing users based on demographics, service type, and churn risk.

      - Churn Reason Analysis: Identifying top churn reasons like price dissatisfaction, competitor influence, and service quality.

      - Predictive Insights: Using trends from historical data to forecast potential churn risks.

      - Retention Strategy Recommendations: Providing actionable insights to reduce churn.

### Step 4 - Prototype
  #### Initial Dashboard Design:

  - Customer Overview

  - Customer Detail

  - Churn Reason

  #### Tools Used:
   - **Power BI** for data visualization.

### Step 5 - Review

- Review each part of the report

## III. Visualization

### 1. Customer Overview

![Screenshot 2025-02-13 163254](https://github.com/user-attachments/assets/890c853b-7610-4fd2-b335-0d20a3525f72)

### 2. Customer Detail

![Screenshot 2025-02-13 163323](https://github.com/user-attachments/assets/b433bde1-146d-45c7-8854-ad9963384e57)

### 3. Churn Reason

![Screenshot 2025-02-13 163329](https://github.com/user-attachments/assets/b1e70055-9198-4181-8af1-6d41e95ab9ac)



## IV. Insights

  - Demographic Impact: Older customers have a higher churn rate compared to younger users.

  - Service Usage Correlation: Customers using international services and data protection features are less likely to churn.

  - Payment Method Influence: Users paying via direct debit have a lower churn rate compared to those using paper checks or credit cards.

  - Contract Type Factor: Month-to-month contract holders exhibit significantly higher churn than long-term contract users.

  - Top Churn Reasons: The primary drivers of churn are competitor offerings, customer dissatisfaction, and pricing concerns.

## V. Recommendations

- Loyalty Programs: Offer discounts or benefits to long-term contract holders to improve retention.

- Proactive Support: Enhance customer service response for dissatisfaction-related churn.

- Competitor Benchmarking: Analyze competitor offerings to stay competitive in pricing and services.

- Personalized Retention Strategies: Identify high-risk churn segments and offer tailored retention incentives.

- Enhanced Payment Options: Encourage customers to use direct debit by offering minor incentives to lower churn risk.
