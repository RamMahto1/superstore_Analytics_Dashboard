1.Project Title:
This project is an end-to-end Power BI business intelligence dashboard built using the Superstore dataset.

The goal is to analyze sales, profit, customer behavior, and identify key drivers of business performance 
including loss-making products and profit influencers.

2. Business Problem Statement:
The business wants to understand:

- What drives sales and profit performance?
- Which products and categories are causing losses?
- How do discounts affect profitability?
- What are the key factors influencing profit?
- How does performance change over time?

The objective is to convert raw transactional data into actionable insights for decision-making.

3. Tools & Technologies:
- Power BI Desktop
- DAX (Data Analysis Expressions)
- Power Query (Data Cleaning)
- SQL (Data extraction via MySQL connection)
- Python (Data integration / optional ETL)
- Superstore Dataset

4. Data Preparation:
- Cleaned missing and inconsistent values
- Created Date Table for time intelligence
- Built relationships between fact and dimension tables
- Created calculated columns (Year-Month sorting, etc.)
- Defined key measures using DAX

5. Key Measures (DAX)
- Total Sales
- Total Profit
- Profit Margin %
- Sales LY (Last Year)
- Profit LY
- YoY Growth %
- Loss Making Products Count

6. Dashboard Pages Structure:
Page 1: Executive Overview
- KPI Cards (Sales, Profit, Margin)
- High-level summary charts

Page 2: Sales & Profit Trend
- Time series analysis
- Monthly performance trends

Page 3: Customer & Segment Analysis
- Segment contribution
- Customer behavior insights

Page 4: Time Intelligence Analysis
- YoY comparison
- Growth trends

Page 5: Decomposition Tree (WHERE)
- Profit breakdown by Category → Product → Region
- Loss-making products analysis

Page 6: Key Influencers (WHY)
- Drivers of profit/loss
- Impact of Discount, Category, Segment
- Supporting visuals (scatter, category analysis)

7. Key Insights:
- Certain categories contribute significantly to overall losses
- High discounts are strongly correlated with lower profit
- A small set of products are responsible for most losses
- Profit varies significantly across segments and regions
- Time-based trends show seasonal variations in performance

8. Key Learnings:
- Built advanced DAX measures (time intelligence)
- Learned filter context and row context in Power BI
- Created interactive dashboards with slicers and visuals
- Used decomposition tree and key influencers for root cause analysis
- Understood business storytelling using data

9. Project Outcome:
This dashboard enables stakeholders to:

- Identify loss-making products
- Understand profit drivers
- Track business performance over time
- Make data-driven decisions to improve profitability

