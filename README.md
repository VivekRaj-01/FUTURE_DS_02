# FUTURE_DS_02
Task 2 – Social Media Marketing Analytics Dashboard (Power BI)

📌 Project Description

This project focuses on analyzing social media marketing performance using a structured dataset.
The goal is to measure engagement, evaluate marketing efficiency, and derive insights to help improve campaign performance.

All analysis and visualizations are performed using Power BI, following the guidelines of Task 2 in the internship program.

📂 Dataset Information

Source: ChatGPT-generated sample dataset

Rows: Multiple campaigns across platforms

Fields Include:

Clicks

Impressions

Revenue

Spend

CTR

ROI

Campaign names

Platforms

📊 Dashboard KPIs
KPI	Value
Total Clicks	50M
Total Impressions	870M
CTR	~5.7%
Total Revenue	$112.262M
Total Spend	$32.842M
ROI	~242%
🧮 DAX Measures Used
CTR (%) – Measure
CTR % =
DIVIDE(
    SUM(Sheet1[Clicks]),
    SUM(Sheet1[Impressions])
)

ROI (%) – Measure
ROI % =
VAR TotalRevenue = SUM(Sheet1[Revenue])
VAR TotalSpend = SUM(Sheet1[Spend])
RETURN
DIVIDE(TotalRevenue - TotalSpend, TotalSpend)

CTR Row-Level Column
CTR Row % =
DIVIDE(
    Sheet1[Clicks],
    Sheet1[Impressions]
)

📈 Dashboard Features

KPI Cards displaying Total Clicks, Impressions, CTR, Revenue, Spend & ROI

CTR Trend Line (using row-wise CTR values)

Revenue vs Spend Comparison

Platform-wise ROI Bar Chart

Campaign Performance Breakdown

🧠 Insights Extracted

CTR remains consistent across campaigns → strong audience engagement

ROI ~242% indicates excellent marketing efficiency

Some platforms outperform others in ROI → ideal for budget allocation

Higher CTR aligns with strong revenue performance

🗂 Files in This Repository

.pbix → Power BI Dashboard

.png → Dashboard Screenshot

README.md → Documentation

🔗 LinkedIn Submission Post

Here is my completion post for Task 2:
🔗 https://www.linkedin.com/posts/vivekraj-finance_powerbi-marketinganalytics-socialmediaanalytics-activity-7391751233583202304-Rdku

🛠 Tools Used

Microsoft Power BI

Microsoft Excel

DAX (Data Analysis Expressions)
📸 Dashboard Preview
![Dashboard Screenshot] <img width="1338" height="715" alt="social media campaign dashboard" src="https://github.com/user-attachments/assets/3ae5c03f-c6c5-4afe-a20b-9f8a6508625d" />
