# 📊 Business Performance Dashboard — Power BI

## 📌 Project Objective

This Business Performance Dashboard was developed to transform transactional sales data into actionable business insights that support strategic decision-making.

The dashboard enables stakeholders to monitor overall business performance, evaluate product profitability, identify operational risks, and uncover the key drivers influencing revenue and profit growth.

Through interactive reporting, KPI monitoring, profitability analysis, trend evaluation, and scenario-based exploration, the solution provides a comprehensive view of business performance across products, categories, customer segments, and regions.

### Key Focus Areas
- Executive Performance Monitoring
- Product & Profitability Analysis
- Risk Identification & Assessment
- Business Driver Analysis
- KPI Reporting
- Interactive Filtering & Scenario Analysis
- Data Storytelling & Decision Support

---

## 🛠️ Tools & Technologies

- Power BI
- Power Query
- DAX

---

## 📂 Dataset Overview

The dataset contains transactional sales records including:

- Orders
- Products
- Categories & Subcategories
- Customer Segments
- Regions
- Sales, Profit & Quantity
- Order Dates

The data was transformed, modelled, and analysed to uncover trends, profitability patterns, performance drivers, and business risks.

---

# 📈 Executive Overview

## 📋 Dashboard View

![Executive Overview](screenshots/executive-overview/executive-overview.png)

### Overview
This page was designed to provide a high-level summary of overall business performance across sales, profitability, order activity, and product movement.

The goal is to help stakeholders quickly understand how the business is performing without needing to go through raw transactional data.

The dashboard combines KPI monitoring, trend analysis, category-level profitability comparison, product performance analysis, and interactive filtering to support executive decision-making.

---

## 📌 KPI Summary

| KPI | Value | What It Represents |
|---|---|---|
| **Total Sales** | $2.33M | Total revenue generated across all products, categories, and regions |
| **Total Profit** | $292.30K | Actual profit retained after operational and product-related costs |
| **Profit Margin** | 12.56% | Profit retained from every dollar of sales *(Total Profit ÷ Total Sales × 100)* |
| **Total Orders** | 5K | Total number of customer orders processed during the reporting period |
| **Total Quantity** | 39K | Total units sold across all product categories |

### Business Insight
The business generated **$2.33M** in total sales with strong order and product volume, indicating healthy market activity across the reporting period.

However, a **12.56% profit margin** against $2.33M in revenue suggests that while the business is profitable, there are still opportunities for:
- cost optimisation,
- pricing improvements,
- and operational efficiency enhancements.

Tracking profit alongside revenue helps stakeholders evaluate business sustainability rather than focusing on revenue growth alone.

---

## 📈 Business Performance Trend Analysis

![Business Performance Trend](screenshots/executive-overview/business-performance-trend.png)

### Purpose
This line chart tracks sales and profit performance over time to identify:
- growth trends,
- business fluctuations,
- seasonal movement,
- and operational performance patterns.

### Key Findings
The business demonstrates fluctuating but generally upward sales growth over the reporting period, with several strong sales spikes visible towards late 2025 and 2026.

Profit trends generally follow sales movement; however, profitability growth remains smaller relative to sales increases.

### Business Insight
Although revenue is increasing, profitability is not growing at the same pace.

This may indicate:
- rising operational costs,
- discount-heavy sales strategies,
- or low-margin product sales driving volume without proportional profit returns.

### Why This Visual Was Chosen
Line charts are highly effective for time-series analysis because they clearly display trends, fluctuations, peaks, and long-term business performance movement.

---

## 📊 Category Revenue & Profitability Analysis

![Category Revenue and Profitability](screenshots/executive-overview/category-profitability-analysis.png)

### Purpose
This visual compares category-level revenue against actual profitability to evaluate category performance efficiency.

### Key Findings

| Category | Total Sales | Total Profit | Observation |
|---|---|---|---|
| **Technology** | ~$840K | ~$147K | Highest revenue and strongest profitability |
| **Furniture** | ~$755K | ~$20K | Strong revenue but weak profitability |
| **Office Supplies** | ~$732K | ~$126K | Stable revenue with strong profit efficiency |

### Business Insight
Technology is the strongest-performing category overall, demonstrating both strong revenue generation and healthy profitability.

Furniture, despite generating strong sales, produced significantly lower profit — suggesting:
- high operational costs,
- discount pressure,
- or inefficient pricing structures.

Office Supplies demonstrates stronger profit efficiency relative to its revenue, making it a more sustainable category from a profitability standpoint.

### Why This Visual Was Chosen
A clustered bar chart allows stakeholders to directly compare revenue and profitability side-by-side across business categories, making performance gaps immediately visible.

---

## 🏆 Top 5 Performing Products Analysis

![Top Performing Products](screenshots/executive-overview/top5-performing-products.png)

### Purpose
This visual identifies the products contributing the highest profit to the business.

### Key Findings
The **Canon imageCLASS 2200 Advanced Copier** significantly outperformed all other products, generating approximately **$25.2K** in profit.

The remaining top-performing products contributed considerably smaller profit values by comparison.

### Business Insight
The business appears to rely heavily on a small number of high-performing products, creating potential concentration risk if demand patterns shift.

This analysis highlights opportunities to:
- prioritise high-margin products,
- strengthen marketing strategies around top-performing products,
- and investigate why other products underperform comparatively.

### Why This Visual Was Chosen
Horizontal bar charts are highly effective for ranked product comparisons because they improve readability while accommodating longer product names.

---

## 🎛️ Interactive Slicers & Filtering

The dashboard includes interactive slicers for:
- **Date filtering** — analyse performance across custom time periods
- **Region analysis** — isolate and compare regional business performance
- **Category drill-downs** — explore category-level trends in detail

These slicers allow users to dynamically explore business performance and conduct scenario-based analysis across different segments of the business.

---

## 📌 Scenario-Based Analysis — Filtered Dashboard View

![Scenario View](screenshots/executive-overview/scenario-view.png)

### Purpose
This filtered dashboard view demonstrates the interactivity of the dashboard by showing how business performance changes when specific filters are applied.

#### Filters Applied
- Date Range = February 23, 2023 — February 23, 2026
- Region = Central
- Category = Technology

### Key Findings

| KPI | Overall Business | Central — Technology | Change |
|---|---|---|---|
| **Total Sales** | $2.33M | $133.54K | Filtered segment |
| **Total Profit** | $292.30K | $26.05K | Filtered segment |
| **Profit Margin** | 12.56% | 19.50% | ▲ +6.94pp |
| **Total Orders** | 5K | 255 | Filtered segment |
| **Total Quantity** | 39K | 1K | Filtered segment |

### Business Insight
Although the filtered sales value is lower than the overall business total, the profit margin increased significantly from **12.56%** to **19.50%**.

This suggests that the Technology category within the Central region operates more efficiently and generates stronger profitability relative to the overall business average.

The filtered analysis also reveals that a smaller operational segment can still produce healthy margins, highlighting the importance of drill-down analysis in identifying profitable business areas.

### Trend Observation
The filtered business trend indicates fluctuating sales activity over time, with several strong spikes in revenue generation.

Profit trends generally follow sales movement, confirming a positive relationship between revenue growth and profitability within the selected segment.

### Product-Level Insight
Within the filtered Technology category, the **Canon imageCLASS 2200 Advanced Copier** remained the strongest-performing product, generating the highest profit contribution among the selected products.

This suggests that certain high-performing products continue to drive profitability even within narrowed business segments.

### Why This Matters
This scenario analysis demonstrates the dashboard's ability to support:
- interactive filtering,
- drill-down analysis,
- targeted business investigations,
- and dynamic decision-making.

It also validates that all slicers dynamically affect visuals across the full dashboard.

---

# 📦 Product Analysis

## 📋 Dashboard View

![Product Analysis Overview](screenshots/product-analysis/product-analysis-overview.png)

### Overview
While the Executive Overview focuses on overall business performance, the Product Analysis page examines performance at the product and subcategory level.

The objective is to identify which products and subcategories drive profitability, which ones underperform, and how product mix influences overall business results.

This page combines subcategory sales vs profit analysis, profit margin assessment by subcategory, product mix distribution, top-performing product identification, and scenario-based exploration to support product strategy and profitability optimisation.

---

## 📌 KPI Summary

| KPI | Value | What It Represents |
|---|---|---|
| **Total Sales** | $2.33M | Total revenue generated across all products, categories, and regions |
| **Total Profit** | $292.30K | Actual profit retained after operational and product-related costs |
| **Profit Margin** | 12.56% | Profit retained from every dollar of sales *(Total Profit ÷ Total Sales × 100)* |
| **Total Orders** | 5K | Total number of customer orders processed during the reporting period |

### Business Insight
These KPIs provide the overall business context for evaluating individual product and subcategory performance. The overall profit margin of **12.56%** serves as the benchmark against which product-level and subcategory-level profitability is assessed throughout this page.

---

## 📊 Subcategory Sales vs Profit Analysis

![Subcategory Sales vs Profit](screenshots/product-analysis/subcategory-sales-vs-profit.png)

### Purpose
This visual compares total sales against total profit at the subcategory level, making it easy to identify which subcategories generate strong revenue but weak profitability — and which ones are operating at a loss.

### Key Findings

#### 🟢 Strong Performers

| Subcategory | Total Sales | Total Profit | Observation |
|---|---|---|---|
| **Copiers** | $150.75K | $56.09K | Highest profit efficiency relative to sales |
| **Phones** | $331.84K | $45.05K | High revenue with healthy profit contribution |
| **Accessories** | $167.38K | $41.94K | Strong profit relative to sales volume |
| **Binders** | $207.35K | $31.43K | Consistent profit generation |

#### 🔴 Problem Areas

| Subcategory | Total Sales | Total Profit | Observation |
|---|---|---|---|
| **Tables** | $208.02K | -$17.75K | Generating a loss despite strong sales volume |
| **Bookcases** | $115.36K | -$3.63K | Loss-making subcategory |
| **Supplies** | $46.73K | -$1.17K | Low volume but still operating at a loss |
| **Machines** | $189.93K | $3.46K | Very weak profit despite high sales |

### Business Insight
The most important finding in this visual is that **Tables is actively losing money** — generating $208K in sales but producing a net loss of $17.75K. This means every Table sale is costing the business more than it earns.

Combined with Bookcases and Supplies also operating at a loss, the Furniture category is carrying significant profitability risk beneath its strong headline sales numbers.

Copiers stand out as the most efficient subcategory — generating $56K in profit from $150K in sales, a margin efficiency that significantly outperforms most other subcategories.

### Why This Visual Was Chosen
A clustered horizontal bar chart allows direct side-by-side comparison of sales and profit per subcategory, making profitability gaps and losses immediately visible without requiring calculation.

---

## 📉 Profit Margin by Subcategory

![Profit Margin by Subcategory](screenshots/product-analysis/profit-margin-by-subcategory.png)

### Purpose
This visual ranks all subcategories by profit margin percentage, using colour coding to instantly separate profitable subcategories (green) from loss-making ones (red).

### Key Findings

#### Highest Margin Subcategories

| Subcategory | Profit Margin | Observation |
|---|---|---|
| **Labels** | 43.9% | Highest margin in the entire business |
| **Paper** | 43.4% | Near-identical to Labels — extremely efficient |
| **Envelopes** | 42.3% | Consistently strong margin |
| **Copiers** | 37.2% | Strong margin despite higher price point products |

#### Loss-Making Subcategories

| Subcategory | Profit Margin | Observation |
|---|---|---|
| **Tables** | -8.5% | Largest loss-making subcategory |
| **Bookcases** | -3.1% | Negative margin across the reporting period |
| **Supplies** | -2.5% | Small volume but still loss-making |

### Business Insight
The margin chart reveals a striking contrast within the business. Labels, Paper, and Envelopes — relatively low-cost, high-volume Office Supplies subcategories — are operating at margins above 40%, making them among the most profitable products in the portfolio despite their modest price points.

Tables, by contrast, is the most damaging subcategory at -8.5% margin. The business is effectively subsidising Table sales. Stakeholders should investigate whether this is driven by excessive discounting, high shipping costs, or supplier pricing issues — and consider whether the Tables subcategory warrants a pricing strategy review.

### Why This Visual Was Chosen
A ranked bar chart with conditional colour coding (green for profit, red for loss) allows stakeholders to immediately identify margin leaders and problem areas without needing to read individual values.

---

## 🧩 Product Mix by Category

![Product Mix by Category](screenshots/product-analysis/product-mix-by-category.png)

### Purpose
This visual shows how sales are distributed across subcategories within each category, revealing which subcategories dominate category revenue and where concentration risk may exist.

### Key Findings

| Category | Dominant Subcategory | Share | Observation |
|---|---|---|---|
| **Technology** | Storage | 40% | Single subcategory drives nearly half of Technology sales |
| **Technology** | Accessories | 20% | Second largest contributor |
| **Furniture** | Chairs | 44% | Chairs dominate Furniture sales |
| **Furniture** | Tables | 25% | Significant share despite being loss-making |
| **Office Supplies** | Paper | 31% | Largest Office Supplies contributor |
| **Office Supplies** | Binders | 28% | Strong second contributor |
| **Office Supplies** | Supplies | 1.17% | Minimal contribution and loss-making |

### Business Insight
The most concerning finding in this visual is that **Tables accounts for 25% of Furniture sales despite operating at a -8.5% profit margin**. This means a significant portion of Furniture revenue is coming from a subcategory that actively loses money — which directly explains why the Furniture category struggles with profitability despite strong headline sales.

Within Technology, the heavy concentration in Storage (40%) suggests potential dependency risk. If demand for Storage products declines, Technology revenue could be disproportionately affected.

Office Supplies shows the most balanced and healthy distribution, with multiple subcategories contributing meaningfully — reducing dependency on any single product line.

### Why This Visual Was Chosen
A 100% stacked bar chart is ideal for showing proportional contribution within categories, making subcategory dominance and concentration immediately visible across all three categories in a single view.

---

## 🏆 Top 10 Products by Profit

![Top 10 Products by Profit](screenshots/product-analysis/top-10-products-by-profit.png)

### Purpose
This visual identifies the ten individual products generating the highest profit contribution to the business.

### Key Findings

| Rank | Product | Total Profit |
|---|---|---|
| 1 | Canon imageCLASS 2200 Advanced Copier | $25.2K |
| 2 | Fellowes PB500 Electric Punch Plastic Comb Binding Machine | $7.8K |
| 3 | Hewlett Packard LaserJet 3310 Copier | $7.0K |
| 4 | Canon PC1060 Personal Laser Copier | $4.6K |
| 5 | HP Designjet T520 Inkjet Large Format Printer | $4.1K |
| 6 | Ativa V4110MDD Micro-Cut Shredder | $3.8K |
| 7 | 3D Systems Cube Printer, 2nd Generation, Magenta | $3.7K |
| 8 | Plantronics Savi W720 Multi-Device Wireless Headset | $3.7K |
| 9 | Ibico EPK-21 Electric Binding System | $3.3K |
| 10 | Zebra ZM400 Thermal Label Printer | $3.3K |

### Business Insight
The **Canon imageCLASS 2200 Advanced Copier** dominates the top 10, generating $25.2K in profit — more than three times the profit of the second-ranked product. This level of concentration around a single product creates dependency risk: if demand declines or supply is disrupted, profit performance would be materially impacted.

The majority of top-performing products fall within the **Technology category**, particularly printing and copying equipment — reinforcing the earlier finding that Technology is the strongest-performing category in the business.

The significant profit gap between rank 1 ($25.2K) and ranks 2–10 ($3.3K–$7.8K) suggests the business would benefit from identifying and scaling additional high-margin products to reduce reliance on a single top performer.

### Why This Visual Was Chosen
A horizontal bar chart ranked by total profit clearly communicates product performance hierarchy, making it easy for stakeholders to identify top contributors and assess concentration risk at a glance.

---

## 🎛️ Interactive Slicers & Filtering

The Product Analysis page includes interactive slicers for:
- **Date filtering** — analyse product performance across custom time periods
- **Category** — isolate performance within Technology, Furniture, or Office Supplies
- **Sub-Category** — drill into specific subcategory performance
- **Segment** — compare product performance across Consumer, Corporate, and Home Office segments

These slicers allow stakeholders to dynamically explore product-level performance and conduct targeted scenario analysis across different business segments.

---

## 📌 Scenario-Based Analysis

The following scenarios demonstrate how the dashboard responds to targeted filtering, revealing performance differences across customer segments within the Furniture category.

---

### Scenario 1 — Furniture | Consumer Segment

![Scenario 1 - Furniture Consumer](screenshots/product-analysis/scenario-furniture-consumer.png)

#### Filters Applied
- Date Range = April 3, 2023 — April 1, 2026
- Category = Furniture
- Segment = Consumer

#### KPI Results

| KPI | Value |
|---|---|
| **Total Sales** | $284.78K |
| **Total Profit** | $5.44K |
| **Profit Margin** | 1.91% |
| **Total Orders** | 642 |

#### Business Insight
The Consumer segment within Furniture generated $284.78K in sales but retained only $5.44K in profit — a margin of just 1.91%. This extremely thin margin suggests the Consumer segment is being heavily discounted, absorbing high shipping costs, or being driven by low-margin subcategories.

The subcategory breakdown reveals that **Tables (-10.0%) and Bookcases (-7.6%)** are the primary margin drags within this segment. Chairs and Furnishings remain positive at 16.3% and 8.3% respectively, indicating that the profitability problem is concentrated in specific subcategories rather than the entire Consumer segment.

---

### Scenario 2 — Furniture | Home Office Segment

![Scenario 2 - Furniture Home Office](screenshots/product-analysis/scenario-furniture-home-office.png)

#### Filters Applied
- Date Range = April 3, 2023 — April 1, 2026
- Category = Furniture
- Segment = Home Office

#### KPI Results

| KPI | Value |
|---|---|
| **Total Sales** | $80.65K |
| **Total Profit** | $3.10K |
| **Profit Margin** | 3.84% |
| **Total Orders** | 217 |

#### Business Insight
The Home Office segment within Furniture generated significantly lower revenue ($80.65K) compared to the Consumer segment, but achieved a higher profit margin at 3.84%. This suggests the Home Office segment operates more efficiently despite its smaller scale.

The subcategory breakdown shows **Tables (-7.2%)** remains loss-making in this segment as well, while Chairs (8.7%) and Furnishings (8.0%) perform more strongly here than in the Consumer segment. Bookcases also improved from -7.6% to 1.2% — suggesting the Home Office segment is less price-sensitive or discount-driven than the Consumer segment.

---

### Scenario Comparison — Consumer vs Home Office (Furniture)

| KPI | Consumer Segment | Home Office Segment | Difference |
|---|---|---|---|
| **Total Sales** | $284.78K | $80.65K | Consumer: 3.5× higher volume |
| **Total Profit** | $5.44K | $3.10K | Consumer: higher absolute profit |
| **Profit Margin** | 1.91% | 3.84% | Home Office: ▲ +1.93pp more efficient |
| **Total Orders** | 642 | 217 | Consumer: ~3× more orders |
| **Chairs Margin** | 8.3% | 8.7% | Broadly consistent across segments |
| **Tables Margin** | -10.0% | -7.2% | Home Office: less severe loss |
| **Bookcases Margin** | -7.6% | 1.2% | Home Office: significantly better |

### Combined Business Insight
The comparison reveals that while the Consumer segment generates far greater revenue and order volume, the Home Office segment is meaningfully more profitable on a margin basis. This pattern suggests that Consumer Furniture sales are being driven by higher discounting or a less profitable product mix — particularly in Tables and Bookcases.

The consistent underperformance of **Tables across both segments** confirms this is a structural profitability problem rather than a segment-specific issue. Regardless of who is buying, Tables is losing money.

A strategic recommendation would be to investigate the pricing and discount structure for Tables and Bookcases specifically within the Consumer segment, where the losses are most severe, while protecting the more efficient Home Office margin profile.

### Why This Analysis Matters
This scenario comparison demonstrates the dashboard's ability to:
- isolate segment-level performance,
- identify which customer segments drive margin efficiency vs volume,
- and support targeted pricing and product strategy decisions.

It also validates that all slicers dynamically update every visual across the page simultaneously.

---

## 🚀 Skills Demonstrated

- Data Cleaning & Transformation
- Data Modelling
- DAX Calculations
- KPI Reporting
- Subcategory & Product-Level Analysis
- Profit Margin Analysis
- Interactive Dashboard Design
- Business Performance Analysis
- Data Storytelling
- Scenario-Based Analysis
- Risk Identification
- Executive Reporting

---

## 🛠️ Tools Used

- Power BI
- Power Query
- DAX

---

> *"The goal is not to have more data. The goal is to have better decisions."*
