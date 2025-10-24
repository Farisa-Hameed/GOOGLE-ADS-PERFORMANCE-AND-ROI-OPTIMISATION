# GOOGLE-ADS-PERFORMANCE-AND-ROI-OPTIMISATION

### 🚀 Overview

This Power BI dashboard analyzes Google Ads campaign performance and ROI optimization using key marketing metrics. It visualizes ad engagement, conversion patterns, and cost efficiency across campaigns, devices, and time periods.

---

### 🧩 Dataset

**Table Name:** `GoogleAds`
**Columns Include:**
`Ad_ID, Campaign_Name, Clicks, Impressions, Cost, Leads, Conversions, Conversion Rate, Sale_Amount, Ad_Date, Location, Device, Keyword, CTR, CPC, CPA, ROI`

---

### 📈 Dashboard Visuals

| Visualization              | Title                                                                                     | Insight                                                                           |
| -------------------------- | ----------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------- |
| **KPI Cards**              | Total Revenue, Average CTR, Total Conversions, Average ROI, Total Impressions, Total Cost | Shows overall campaign performance metrics                                        |
| **Scatter Chart**          | Campaign Efficiency and ROI                                                               | Compares ROI against campaign cost and efficiency                                 |
| **Clustered Column Chart** | Ad Engagement Analysis                                                                    | Displays campaign-wise Clicks, Cost, and Conversions                              |
| **Line Chart**             | Performance Trend Over Time                                                               | Shows ROI and Clicks trend over the months                                        |
| **Donut Chart**            | Conversions Breakdown by Device                                                           | Shows conversion share across Mobile, Desktop, and Tablet                         |
| **Funnel Chart**           | Ad Performance Funnel                                                                     | Illustrates the journey from Impressions → Clicks → Leads → Conversions → Revenue |

---

### ⚙️ DAX Measures

* `CTR = DIVIDE(SUM(Clicks), SUM(Impressions))`
* `CPC = DIVIDE(SUM(Cost), SUM(Clicks))`
* `CPA = DIVIDE(SUM(Cost), SUM(Conversions))`
* `ROI = DIVIDE(SUM(Sale_Amount) - SUM(Cost), SUM(Cost))`

---

### 🧠 Tools Used

* Power BI Desktop
* DAX (Data Analysis Expressions)
* CSV Dataset

---

### 💼 Author

**👩‍💻 Farisa Hameed**
Data Analyst | Power BI | SQL | Python | Machine Learning
[LinkedIn Profile](#) • [GitHub Portfolio](#)
