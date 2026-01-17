📊 Social Media Campaign Performance Tracker

🔍 Project Overview
This project analyzes Facebook advertising campaign performance using real-world style marketing data. The goal is to evaluate campaign effectiveness, audience engagement, and conversion quality through interactive dashboards and data-driven insights.
The dashboard helps answer key business questions such as:
• How well did the ad campaign perform?
• Which ads and audience segments performed best?
• Is higher ad spend leading to better conversions?
• How can future campaigns be optimized?

🧰 Tools & Technologies
Power BI – Dashboard creation & data visualization
Power Query – Data cleaning & transformation
DAX – KPI calculations (CTR, CPC, Conversion Rate)
Excel / CSV – Raw dataset
Dataset Source – Facebook Ads Performance Dataset (Kaggle)

📁 Dataset Description
The dataset contains Facebook ad performance metrics including:
• Campaign and Ad identifiers
• Impressions, Clicks, Spend
• Approved & Total Conversions
• Audience attributes (Age, Gender, Interest)
• Reporting dates

🧹 Data Cleaning & Preparation
Converted date fields from text to proper Date format
Removed invalid interest values
Converted identifier fields to Text to avoid aggregation issues
Retained zero values in clicks, spend, and conversions to reflect real campaign performance
Ensured correct data types for all metrics

📈 Key KPIs Created (DAX)
Total Impressions
Total Clicks
Total Spend
Click-Through Rate (CTR %)
Cost Per Click (CPC)
Conversion Rate

📊 Dashboard Structure
🔹 Page 1 – Campaign Performance Overview
KPI cards (Clicks, Spend, Impressions, CTR, CPC)
Clicks & Ad Spend trend over time
Top 10 ads by clicks
Click distribution by gender
🔹 Page 2 – Audience & Ad Performance Analysis
CTR (%) by age group
Top 10 interests by approved conversions
Ad Spend vs Approved Conversions (scatter plot)
Interactive filters (Campaign, Ad ID, Gender, Interest)
🔹 Page 3 – Insights & Optimization Recommendations
Key campaign insights
Actionable recommendations to improve performance and ROI

🧠 Key Insights
The 45–49 age group shows the highest CTR, indicating stronger engagement.
Certain interest groups generate higher approved conversions, showing better lead quality.
Higher ad spend does not always result in higher approved conversions.
Male users contribute the majority of clicks.
A small number of ads drive a large share of clicks and conversions.

🎯 Recommendations
Increase budget allocation to high-CTR age groups and high-approval interests.
Pause or redesign ads with high spend but low approved conversions.
Scale high-performing ads identified in the Top-10 analysis.
Perform A/B testing to improve CTR and conversion efficiency.
Refine audience targeting using high-CTR age groups combined with high-conversion interests.

📌 Key Skills Demonstrated
Marketing Analytics
Data Cleaning & Transformation
KPI & Metric Analysis
Data Visualization & Storytelling
Power BI Dashboard Design
Business Insight Generation

📷 Dashboard Preview
<img width="749" height="405" alt="image" src="https://github.com/user-attachments/assets/6a97a29f-fadd-4abf-93c2-cc4a4b882607" />
<img width="737" height="411" alt="image" src="https://github.com/user-attachments/assets/5e680472-90ca-48af-99bf-a5d41b509d48" />
<img width="852" height="461" alt="image" src="https://github.com/user-attachments/assets/586bd56a-633c-49a4-aaca-54d1baa69693" />

📄 How to Use
Download the .pbix file
Open in Power BI Desktop
Explore dashboards using slicers and filters
