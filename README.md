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

*Displays revenue growth, profitability, gross margins, and a full P & L statement to track financial performance.*

**Key Insights:**

- Net sales in 2025 grew by 43.9% to $10.63B since last year but were still 43.6% less than the target; net profit remained negative at -$1.72B (-16.14%). Gross margin was 37.84%, while operating expenses reached $5.74B (approximately 54% of net sales), growing 48%, faster than sales.
- Only 50% of gross sales ($21.26bn) became net sales ($10.63bn). Pre-invoice and post-invoice deductions accounted for 23.7% and 26.3%, leaving a 37.84% gross margin that can’t cover $5.74bn in operating expenses.
- September to December brings about 41% of annual net sales, peaking at $1.35bn in November, then drops 44% in January and stays low through June.

**Recommendations:**

- Control operating expense growth, particularly advertising and promotional spending, to optimize profits.
- Tighten discount approvals, renegotiate deduction terms, and reduce manufacturing and operating costs together to cover the $1.72bn loss.
- Align inventory, promotions, and budgets with the September to December peak, and run targeted campaigns during the January to June slowdown.

#### 2. Sales View:

*Displays customer and product performance to identify key revenue contributors and opportunities to improve profitability.*

**Key Insights:**

- Amazon (36.9%) and Sage (32.8%) recorded gross margins below the overall average of 37.84%, while AtliQ Exclusive achieved the highest margin at 46.2%.
- Amazon ($1.23B), AtliQ e-Store ($1.10B), and AtliQ Exclusive ($872M) were the top three customers by net sales.

**Recommendations:**

- Review pricing and commercial terms for low-margin key accounts while expanding higher-margin channels such as AtliQ Exclusive and e-Store.
- Strengthen relationships with major revenue-generating customers through dedicated account management.

#### 3. Marketing View:

*Displays product segment performance, sales contribution, gross margins, and net profitability across segments and regions.*

**Key Insights:**

- All product segments reported negative net margins (-14.6% to -16.4%), despite gross margins of approximately 38%. Notebooks and Peripherals contributed around 65% of sales and substantial losses of $651M and $467M, respectively.
- Storage recorded the highest gross margin (39.4%) and the least negative net margin (-14.6%), with sales of $167M.
- Every region except LATAM reported a net loss. APAC had the largest loss (-$972M) on 55% of net sales, North America had the weakest margin (-24.2%), and EU lost -12.0%. LATAM was the only profitable region ($98M profit, 33.07% net margin), though on a small base of $297M in sales (2.8% of total).

**Recommendations:**

- Investigate operating expenses allocated to Notebooks and Peripherals to identify opportunities to reduce losses.
- Review costs in APAC and North America to improve profitability, and identify practices from LATAM that could be replicated across other regions.

#### 4. Supply Chain View:

*Displays demand forecast accuracy, net forecast error, and customer- and product-level inventory risks to support better replenishment and stock availability decisions.*

**Key Insights:**

- Forecast accuracy improved to 80.89% (+3.8%), but net error worsened to -10.3%, indicating a persistent under-forecasting bias. Many customers and products were flagged for out-of-stock risk.
- Notebooks recorded the lowest forecast accuracy (76.26%) and the highest net error (-15.6%). Accuracy fell to approximately 71% in June, the weakest month.
- The highest-selling customers, Amazon, AtliQ e-Store, and AtliQ Exclusive, are also the most under-forecasted (-3.4M, -2.8M, and -2.0M units), making up about 30% of total net error and putting the largest share of revenue at risk.

**Recommendations:**

- Investigate the causes of under-forecasting and adjust forecasting methods to reduce systematic bias.
- Prioritize inventory planning for Notebooks, Accessories, and Peripherals, with adequate stock preparation ahead of the September–December peak season.

#### 5. Executive View:

*Displays key financial metrics, revenue contribution, top customers and products, market share, and sub-region performance for a high-level business overview.*

**Key Insights:**

- Net sales grew 43.9% to $10.63B, but net profit margin fell to -16.14% from +2.2% in 2019, despite stable gross margins of around 37–38%.
- India (-38.1%) and North America (-24.2%) have the weakest net margins, together contributing 47% of net sales. LATAM contributes only 2.8% of sales and has an approximately -33% net margin.
- AtliQ's market share grew from 5.9% in 2022 to 7.7% in 2025, indicating improved competitiveness.
- The PC division contributes 54.9% of net sales, while the top five customers account for 40.1% and retailers contribute 71.59%, highlighting dependence on a single product division, key customers, and sales channels.

**Recommendations:**

- Improve profitability by reviewing operating costs in India and North America, which have the weakest net margins.
- Review LATAM's cost structure and investment strategy to establish a clear path to profitability.
- Diversify revenue across product divisions, customer accounts, and sales channels while expanding market share in profitable segments.

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

