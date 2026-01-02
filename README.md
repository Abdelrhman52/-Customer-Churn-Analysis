# 📉 Customer Churn Analysis Project

## 🏢 Industry
Telecommunications

---

## 📌 Project Overview
This project analyzes customer churn in the telecommunications industry using an end-to-end data analytics workflow.  
The objective is to identify the key drivers of customer churn, assess and improve data quality, explore customer behavior, and segment customers based on value and churn risk to support data-driven retention strategies.

A synthetic dataset was created to closely resemble real-world telecom data, including realistic data quality challenges such as missing values, outliers, inconsistent data types, and categorical inconsistencies.

---

## 🎯 Project Objectives
- Assess and improve data quality before analysis  
- Identify key factors contributing to customer churn  
- Analyze customer behavior and service usage patterns  
- Perform customer segmentation based on value and churn risk  
- Generate actionable insights for customer retention strategies  

---

## 🧪 Data Quality Assessment
A structured **Data Quality Assessment Framework** was implemented to evaluate the dataset prior to analysis.

### Quality Dimensions Analyzed
- **Completeness:** Missing values at column and dataset levels  
- **Data Type Consistency:** Incorrect or mixed data types  
- **Outlier Detection:** Extreme values using IQR-based methods  
- **Categorical Consistency:** Inconsistent labels and casing issues  

### Outcome
- Generated an overall **Data Quality Score**  
- Identified critical data issues affecting analysis reliability  
- Visualized data quality gaps using summary metrics  

---

## 🧹 Data Cleaning & Transformation
A modular data cleaning pipeline was developed to resolve identified data issues.

### Key Cleaning Steps
- Converted incorrect data types to appropriate formats  
- Handled missing values using mean and mode imputation  
- Treated outliers using percentile-based capping (winsorization)  
- Standardized categorical values (e.g., gender normalization)  
- Created new engineered features:
  - Tenure segments  
  - Age groups  
  - Monthly charge segments  

### Result
- Improved data consistency and completeness  
- Enhanced dataset readiness for analysis  
- Added meaningful features for deeper insights  

---

## 📊 Exploratory Data Analysis (EDA)
Exploratory analysis was conducted using visual and statistical techniques to understand churn behavior.

### Key Analyses
- Customer demographic distributions  
- Tenure and monthly charge distributions  
- Overall churn rate analysis  
- Churn by contract type, tenure, and services  
- Correlation analysis of numerical variables  

### Key Insights
- Customers with shorter tenure showed higher churn rates  
- Contract type had a strong impact on churn behavior  
- Monthly charges and tenure were key churn indicators  
- Value-added services reduced churn probability  

---

## 🔍 Customer Segmentation
Customers were segmented based on **value** and **churn risk** to support strategic decision-making.

### Segmentation Metrics
- **Customer Value Score:** Tenure, monthly charges, contract type  
- **Churn Risk Score:** Contract type, tenure segment, security services  

### Customer Segments
- **Champions:** High value, low churn risk  
- **At-Risk High Value:** High value, high churn risk  
- **Low Value Loyal:** Low value, low churn risk  
- **Critical:** Low value, high churn risk  

### Business Impact
- Enabled targeted retention and loyalty campaigns  
- Identified high-value customers requiring immediate intervention  
- Supported personalized marketing and service optimization  

---

## 🛠️ Tools & Technologies
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Data Quality Assessment Techniques  
- Feature Engineering  

---

## 💡 Business Value
This project demonstrates a complete analytics lifecycle—from raw data quality assessment to actionable customer segmentation.  
The insights enable telecom companies to proactively reduce churn, increase customer lifetime value, and design effective retention strategies.

---

## 📁 Project Structure

