<p align="center">
  <img src="screenshots/dashboard-cover/banner.png" alt="Business Performance Dashboard Banner" width="100%"/>
</p>
📊 Business Performance Dashboard — Power BI
📌 Project Overview
This Business Performance Dashboard was developed to transform transactional sales data into actionable business insights that support strategic decision-making.
The dashboard enables stakeholders to monitor business performance, identify profitability risks, evaluate product performance, and uncover the key drivers influencing revenue and profit growth.

❓ Business Questions Answered
This dashboard was designed to answer:

Which categories generate the highest profit?
Which products and subcategories are driving losses?
How do discounts impact profitability?
Which customer segments contribute the most value?
Which regions generate the strongest profit performance?
Where are the most attractive growth opportunities?


📈 Executive Summary
Analysis of $2.33M in sales revealed that profitability challenges are driven less by revenue generation and more by discounting behaviour, product mix, and subcategory performance.
Key Findings

Technology generated the highest profit (~$147K)
Furniture produced strong sales but weak profitability
Tables generated a loss of ~$17.8K despite ~$208K in sales
Heavy discounting is strongly associated with loss-making transactions
Corporate Technology customers in the West region represent a high-value growth opportunity


📸 Dashboard Preview
Executive OverviewProduct AnalysisShow ImageShow Image
Risk AnalysisBusiness DriversShow ImageShow Image

📊 Dashboard Pages
Executive Overview
Provides a high-level view of sales, profit, profit margin, order activity, category performance, and business trends.
Product Analysis
Identifies top-performing products, profitability drivers, loss-making subcategories, and product mix distribution.
Risk Analysis
Examines discount-related risks, loss-making products, margin erosion, and profitability challenges.
Business Drivers Analysis
Explores customer segments, regional performance, shipping modes, and growth opportunities influencing business performance.

🛠️ Technical Implementation
Data Transformation

Power Query


DAX Measures
daxTotal Sales =
SUM(Orders[Sales])

Total Profit =
SUM(Orders[Profit])

Profit Margin =
DIVIDE([Total Profit], [Total Sales])

Loss Sales =
CALCULATE(
    [Total Sales],
    FILTER(Orders, Orders[Profit] < 0)
)

Average Discount =
AVERAGE(Orders[Discount])

📄 Detailed Business Analysis
A comprehensive report containing dashboard walkthroughs, visual-by-visual analysis, scenario-based exploration, strategic recommendations, and business insights is available here:
📄 Business Performance Analysis Report

🚀 Skills Demonstrated
Power BI


Power Query
DAX

Analytics

KPI Development
Profitability Analysis
Root Cause Analysis
Risk Assessment
Business Driver Analysis

Business Intelligence

Dashboard Design
Executive Reporting
Data Storytelling
Strategic Recommendations
Decision Support



"The goal is not to have more data. The goal is to have better decisions."
