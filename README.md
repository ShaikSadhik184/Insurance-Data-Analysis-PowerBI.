📊 Insurance Data Analysis Dashboard (Power BI)

❗ Problem Statement

Insurance companies face challenges such as:

📉 Difficulty in tracking claims across different policy types

👥 Limited visibility into customer demographics and policy trends

😀 Lack of actionable insights from customer feedback and satisfaction data

⏳ Manual reporting processes that delay data-driven decision-making

👉 To overcome these issues, this project presents a centralized Power BI dashboard that delivers real-time insights into claims performance, policy trends, demographics, and customer sentiment, helping insurers enhance operational efficiency and customer experience.

📌 Project Overview

This project delivers an interactive Power BI dashboard built to analyze insurance data and customer feedback. The dashboard uncovers insights into policy performance, claims trends, customer demographics, and sentiment analysis, enabling smarter business decisions.

🛠 Tech Stack

💻 Power BI Desktop → For dashboard development

🔄 Power Query → Data transformation & cleaning

🧮 DAX (Data Analysis Expressions) → KPIs & calculated measures

🗂 Data Modeling → Relationship building for efficient querying

📂 File Format → .pbix Power BI file

📂 Data Sources

📑 InsuranceData → Policy, claim, premium, and coverage details

🗒 Insurance_Customer_Feedback.xlsx → Customer feedback & sentiment analysis

Key Fields Used:
🆔 Customer ID | 📜 Policy Number | 💰 Claim Amount | 📌 Claim Status | 👤 Gender | 🎂 Age | 🌍 Region | ⭐ Feedback Score

📝 Steps Followed
🔹 Step 1: Data Collection

Collected insurance policy data (InsuranceData.csv) and customer feedback survey data (Insurance_Customer_Feedback.xlsx).

🔹 Step 2: Data Preparation

Imported datasets into Power BI.

Cleaned and transformed data using Power Query.

Standardized column names, handled null values, and formatted data types.

🔹 Step 3: Data Modeling

Built relationships between policy, claims, and feedback tables.

Designed a star schema model for performance efficiency.

🔹 Step 4: DAX Measures

Created calculated fields such as:

🧮 Total Premium Amount

💰 Total Claim Amount

📊 Claim Ratio

⭐ Average Feedback Score

🔹 Step 5: Dashboard Design

Developed three interactive pages:

📊 Insurance Overview → KPIs, claims by type, active/inactive policies

👥 Claims & Demographics → Detailed table with filters for traceability

😀 Customer Feedback → Sentiment scores, word cloud, and ratings

🔹 Step 6: Insights Extraction

Identified top-performing policy types

Compared claim distribution by age group & status

Analyzed customer feedback patterns and sentiment


## 📸 Dashboard Snapshots  

### 🟢 Page 1: Insurance Overview  
![Page 1 Overview](Dashboard_Snaps/Page1_Overview.png)  
[View Full Image](Dashboard_Snaps/Page1_Overview.png)  

### 🟡 Page 2: Claims & Demographic Insights  
![Page 2 Claims](Dashboard_Snaps/Page2_Claims.png)  
[View Full Image](Dashboard_Snaps/Page2_Claims.png)  

### 🔵 Page 3: Customer Feedback Analysis  
![Page 3 Feedback](Dashboard_Snaps/Page3_Feedback.png)  
[View Full Image](Dashboard_Snaps/Page3_Feedback.png)  

📑 Key Visuals
🟢 Page 1: Insurance Overview

📊 KPIs for Premium, Coverage, Claims

🧾 Claims by Policy Type

🔄 Active vs Inactive Policies

📉 Claim Status & Age Group

🟡 Page 2: Claims & Demographic Insights

🆔 Policy & Claim details

👤 Demographics (Age, Gender)

💰 Premiums & Claim Amounts

🔍 Data validation table

🔵 Page 3: Customer Feedback Analysis

☁️ Word Cloud of customer responses

😀 Sentiment score with customer-level feedback



