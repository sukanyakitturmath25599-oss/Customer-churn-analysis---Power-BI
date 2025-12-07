# Customer-churn-analysis---Power-BI

 ## 📊 Customer Churn Analysis in Power BI ##

This project focuses on analyzing customer churn using an interactive Power BI dashboard. The goal is to identify why customers leave, which segments are most at risk, and what business actions can reduce churn.
Using demographic, billing, and service-usage data, the dashboard highlights key churn patterns and provides insights for customer retention.

## 📁 Project Overview ##

- Total Customers: 7,043

- Churned Customers: 1,869

- Churn Rate: 26.54%

The analysis helps in understanding customer behavior based on factors such as gender, senior citizen status, contract type, payment method, tenure, and services used.

## 📊 Dashboard Insights ##
### 1️⃣ Churn by Gender ###

- Male and female customers churn at nearly the same rate.

- Gender alone is not a significant churn predictor.

### 2️⃣ Senior Citizens & Services ###

- Senior citizens have higher churn rates.

- Customers who availed fewer services (like security or tech support) are more likely to churn.

### 3️⃣ Tenure Analysis ###

- The highest churn occurs among customers with 0–12 months tenure.

- Long-term customers (50+ months) are the least likely to churn.

### 4️⃣ Partner & Dependents ###

- Customers without partners show significantly higher churn.

- Having a partner or dependents correlates with improved retention.

### 5️⃣ Payment Method & Contract Type ###

- Month-to-month customers show the highest churn.

- Electronic check users are the most churn-prone.

- Yearly/two-year contracts reduce churn significantly.

### 6️⃣ Total Services Availed ###

- Non-churned customers availed ~24K services, while churned customers availed only ~9K.

- Low engagement = high churn risk.

### 7️⃣ Revenue Impact ###

- Active customers’ total charges: 13.19M

- Churned customers’ total charges: 2.86M

- Significant revenue loss due to churn.

## 🛠️ Tools & Techniques Used ##
### 🔹 Power BI ###

- Power Query for data cleaning

- Data modeling (relationships, measures)

- DAX Measures

- Interactive Dashboards

- Slicers & drillthroughs

### 🔹 Key DAX Measures ###

- Churn Rate

- Churn Count

- Customer Count

- Tenure Segmenting

- Service Usage Aggregations

## 📑 Dataset Features ##

The dataset includes:

- Demographics: CustomerID, gender, SeniorCitizen, Partner, Dependents

- Tenure: Total months with the company

- Services: PhoneService, MultipleLines, OnlineSecurity, OnlineBackup, DeviceProtection, TechSupport, StreamingTV, StreamingMovies

- Account Info: Contract type, PaperlessBilling, PaymentMethod

- Billing: MonthlyCharges, TotalCharges

- Target: Churn (Yes/No)

## 🎯 Business Outcomes ##

This analysis helps businesses:

- Identify high-risk customer segments

- Improve onboarding for new customers

- Provide targeted retention offers

- Encourage long-term contracts

- Enhance service bundles for greater engagement

- Reduce overall churn and increase revenue stability

## 📎 Files Included ##

- Customer_Churn_Dashboard.pbix – Power BI dashboard

- Dataset.csv – Customer churn dataset

- README.md – Project documentation

- Dashboard screenshots (PNG)

## 🚀 How to Use This Project ##

- Download the .pbix file

- Open it using Power BI Desktop

- Explore visuals, filters, and insights

- Modify or extend the analysis as needed

<img width="1301" height="737" alt="Screenshot 2025-12-07 132301" src="https://github.com/user-attachments/assets/40d91dde-9924-4e64-95df-c0e70be1945d" />


