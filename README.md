# Business-Insights-360

## Project Overview:

AtliQ Hardware is a fast-growing global electronics company operating across **27** markets and serving **75+** customers worldwide. Its recent expansion into Latin America has led to heavy financial losses. To understand what went wrong and regain control, the company has decided to implement data analytics using Power BI for the first time, with the goal of surpassing competitors and making data-driven decisions. This project aims to answer stakeholders’ questions across all areas: **finance, sales, marketing, and supply chain**.

## Dataset Structure:

The data comes from a SQL database and some additional CSV files, structured using a **star schema** with multiple fact tables connected to shared dimension tables.

#### Fact Tables: 

- *fact_sales_monthly* – Contains monthly sales transactions, including sold quantity and related sales metrics
- *fact_forecast_monthly* – Contains monthly demand forecasts used to evaluate forecast accuracy and supply chain performance
- *fact_freight_cost* – Contains freight and logistics cost information
- *fact_gross_price* – Contains product-level gross pricing information
- *fact_manufacturing_cost* – Contains manufacturing cost information

#### Dimension Tables:
- *dim_customer* – Customer details such as customer name, market, and region
- *dim_product* – Product details including product, segment, division, and category information
- *dim_date* – Date-related attributes used for time-based analysis
- *dim_market* – Market, region, and related geographical information

#### Additional Data:

- *market_share* – Market share information for competitive analysis
- *targets* – Net Sales and gross margin targets for performance comparison
- *operational_expenses* – Ads, promotion, and other operational expenses data used for profitability analysis

## Key Insights and Recommendations:

The dashboard is built with 5 views that answer key business questions across finance, sales, marketing, and supply chain.

#### 1. Finance View:

*Displays revenue growth, profitability, gross margins, and a full glimpse of the P & L statement to track financial performance.*

Key Insights:

- Net sales grew by 43.9% to $10.63B since last year but still 43.6% less than the target; net profit remained negative at -$1.72B (-16.14%). Gross margin was 37.84%, while operating expenses reached $5.74B (approximately 54% of net sales), growing 48%, faster than sales.
- Only 50% of gross sales ($21.26B) translated into net sales. Pre-invoice and post-invoice deductions accounted for 23.7% and 26.3%, respectively.

Recommendations

- Control operating expense growth, particularly advertising and promotional spending, to optimize sales growth.
- Review discount approvals and renegotiate deduction terms to improve net sales.

![image](https://github.com/Sukhmani252/Business-Insights-360/blob/main/Screenshot%202026-10-23%20104237.png)

#### 2. Sales View:

![image](https://github.com/Sukhmani252/Business-Insights-360/blob/main/Screenshot%202026-10-23%20104445.png)

#### 3. Marketing View:

![image](https://github.com/Sukhmani252/Business-Insights-360/blob/main/Screenshot%202026-10-23%20104531.png)

#### 4. Supply Chain View:

![image](https://github.com/Sukhmani252/Business-Insights-360/blob/main/Screenshot%202026-10-23%20104609.png)

#### 5. Executive View:




## Technical Learnings:

- Preparation of questions that should be asked before starting the project
- Creating calculated columns
- Creating measures using DAX language
- Data modeling
- Using Bookmarks to switch between two visuals
- Page navigation with buttons
- Using the DIVIDE function to prevent zero division errors
- Creating a date table using the M language
- Generating dynamic titles based on the applied filters
- Using KPI indicators
- Conditional formatting the values in visuals using icons or background color
- Data validation techniques
- Report optimization using DAX Studio
- Publishing reports to Power BI service
- Setting up a personal gateway to set up the auto-refresh of data

## Soft Skills:

 - Refined understanding of multiple domains: finance, sales, marketing and supply chain
 - Designing user-centric dashboards with empathy in mind
 - Managing stakeholders' requirements

