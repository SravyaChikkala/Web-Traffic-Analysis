# Web-Traffic-Analysis
A complete data analytics project using Python (Pandas) and Power BI to analyze website traffic, conversion performance, and revenue trends.  This project helps understand which marketing channels perform best, how devices behave, and what days generate the most revenue.

web-traffic-analytics/
│
├── data/
│   └── web_traffic.csv
│
├── notebooks/
│   └── web_traffic_analysis.ipynb
│
├── visuals/
│   ├── revenue_by_source.png
│   ├── daily_sessions_trend.png
│   ├── daily_revenue_trend.png
│   ├── conversion_rate_by_source.png
│   ├── revenue_per_session_by_source.png
│   ├── device_performance.png
│   ├── sessions_pie_chart.png
│
├── dashboard/
│   └── web_traffic_dashboard.pbix
│
└── README.md

🎯 Objective

Analyze website performance to understand:

Which traffic sources bring the most sessions

Which channels generate the most revenue

Source-level conversion rates

Device performance (Mobile vs Desktop)

Daily & monthly traffic patterns

Revenue per session (quality of traffic)

🧰 Technologies Used

Python (Pandas, Matplotlib)

Jupyter / Google Colab

Power BI Desktop

Excel (for CSV preparation)

🧹 Data Cleaning & Preparation

Performed in Python:

Fixed data types (Date, numeric fields)

Cleaned invalid rows

Created new calculated fields:

ConversionRate = Transactions / Sessions

RevenuePerSession = Revenue / Sessions

Day = Day of Week

Month = YYYY-MM

Removed missing values

📈 Exploratory Data Analysis (Python)

Key analysis includes:

Total sessions, users, pageviews, revenue

Traffic by source (Organic, Paid, Social, Direct)

Revenue by source

Conversion rate by source

Device performance

Revenue by day of week

Daily sessions & revenue trends

Revenue per session

All plots are saved in visuals/.

📊 Power BI Dashboard

Interactive dashboard includes:

Revenue by Source (Bar Chart)

Daily Sessions Trend (Line Chart)

Daily Revenue Trend (Line Chart)

Conversion Rate by Source (Column Chart)

Revenue Per Session by Source (Column Chart)

Device Performance Overview

Sessions Distribution by Source (Pie Chart)

Slicers:

Source

Device

Day of Week

Dashboard file:
dashboard/web_traffic_dashboard.pbix

🔍 Key Insights

Organic traffic brings the highest number of sessions.

Paid traffic has the strongest revenue per session.

Mobile devices generate more sessions but slightly lower conversion.

Weekends show stronger conversion and revenue activity.

Direct traffic is the lowest performing channel overall.

Daily traffic trends reveal peak days that can be used for campaigns.

🧭 Business Recommendations

Increase budget for Paid campaigns (high-quality traffic).

Improve mobile UX to increase mobile conversions.

Use Organic + Paid mix for maximum growth.

Run promotional campaigns on weekends (higher revenue).

Reduce spend on Direct/Social until performance improves.

Focus on retention to increase Revenue Per Session.
