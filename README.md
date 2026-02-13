# 📊 Customer Segmentation & HR Analytics Dashboard

##  Project Overview
This project demonstrates data transformation, customer segmentation (RFM analysis), 
and dashboard creation using Power BI and structured datasets.

The objective is to analyze customer behavior and employee attrition trends 
to support business decision-making.

---

#  Project 1: Customer Segmentation (RFM Analysis)

##  Dataset
- rfm_segments.csv
- segment_actions.txt

##  Objective
Segment customers based on:
- Recency (R)
- Frequency (F)
- Monetary Value (M)

##  Process

### 1️ Data Preparation
- Imported RFM dataset into Power BI
- Verified data types (Numeric for R, F, M)
- Removed duplicates (if any)

### 2️ RFM Segmentation
Customers were categorized into segments:

- Champions
- Loyal Customers
- Potential Loyalist
- At Risk
- Hibernating

### 3️ Business Actions Defined

**Champions**
- Loyalty rewards
- Exclusive offers
- Early access to products

**Loyal Customers**
- Upsell premium products
- Encourage referrals
- Personalized recommendations

**Potential Loyalist**
- Offer discounts
- Engagement emails
- Subscription promotions

**At Risk**
- Win-back campaigns
- Feedback surveys
- Special discounts

**Hibernating**
- Reactivation emails
- Seasonal promotions
- Highlight trending products

---

# Project 2: HR Analytics – Employee Attrition

##  Dataset
IBM HR Analytics Employee Attrition Dataset  
Rows: 1470  
Columns: 35 (original)

##  Data Transformation (Power Query)

- Removed constant columns (EmployeeCount, Over18, StandardHours)
- Fixed data types (Age, MonthlyIncome, etc.)
- Created conditional columns:
  - AgeGroup (Under 25, 25–35, 36–45, 46+)
  - SalaryBand (Low, Medium, High, Very High)
  - AttritionFlag (1 = Yes, 0 = No)
- Cleaned minor blank values

##  Key Insights

- Highest attrition observed in Sales department
- Employees aged 25–35 show higher attrition
- OverTime employees have increased attrition risk

---

#  Tools Used

- Power BI Desktop
- Power Query
- Microsoft Excel (for validation)

---

#  Files Included

- rfm_segments.csv
- segment_actions.txt
- HR_Analytics.csv
- dashboard_export.pdf
- transformation_notes.txt

---

#  Key Skills Demonstrated

- Data Cleaning & Transformation
- RFM Segmentation
- Conditional Column Creation
- Business Recommendation Mapping
- Dashboard Development
- Insight Generation

---

#  Business Impact

- Identifies high-value customers for retention
- Recommends targeted marketing strategies
- Detects employee attrition risk patterns
- Supports data-driven HR & Marketing decisions

---

## 👨‍💻 Author
Pratheep Roz  
Data Analyst Intern  
