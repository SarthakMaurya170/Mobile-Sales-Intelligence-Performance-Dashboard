Mobile Sales Intelligence & Performance Dashboard
Executive Summary
This project delivers an interactive Business Intelligence dashboard designed to monitor and analyze mobile handset sales performance across the Indian market. By transforming raw transactional data into a dynamic visual model, this tool empowers stakeholders to track revenue health, identify seasonal demand shifts, and optimize regional distribution strategies.

Business Objectives
Revenue Tracking: Provide a real-time, high-level overview of core KPIs (Gross Sales, Transaction Volume, Average Order Value).

Geospatial Analysis: Map sales density across Tier 1 and Tier 2 cities to evaluate regional market penetration.

Consumer Behavior: Analyze purchasing patterns, payment method preferences, and overall customer satisfaction/brand loyalty.

Data Methodology & Tech Stack
Tools Utilized
Primary Platform: Power BI Desktop

Data Modeling: Power Pivot / Star Schema implementation

Calculations: DAX (Data Analysis Expressions)

Data Transformation: Power Query (ETL processes)

Advanced DAX Implementations
To move beyond standard aggregations, custom DAX measures were engineered for dynamic reporting. Key implementations include:

Dynamic KPIs: Measures calculating $769M Total Sales and $40K Average Ticket Size, fully responsive to temporal and geospatial slicers.

Time Intelligence: ```dax
// Example Placeholder: Replace with your actual DAX formula
MoM_Sales_Growth =
DIVIDE(
[Total Sales] - CALCULATE([Total Sales], DATEADD('Calendar'[Date], -1, MONTH)),
CALCULATE([Total Sales], DATEADD('Calendar'[Date], -1, MONTH))
)

Segmentation: Custom binning logic for the 5-tier Customer Ratings funnel.

Key Insights & Strategic Recommendations
Market Share & Brand Dominance: Apple and Samsung lead overall revenue generation, yet OnePlus captures a highly competitive segment. Recommendation: Increase promotional bundling for mid-tier brands to capture unassigned market share.

Geographic Concentration: Sales volume is heavily localized in major metropolitan hubs (Mumbai, Delhi). Recommendation: Investigate logistics and marketing reach in underperforming regional zones mapped in the dashboard.

Temporal Demand & Seasonality: Analysis reveals distinct peak sales periods in January and July, with a notable valley in September. Recommendation: Optimize inventory procurement ahead of July and launch targeted discount campaigns in September to stimulate demand.

Payment Channel Parity: Transactions are evenly distributed across UPI, Credit, Debit, and Cash (~25% each). Recommendation: Maintain diverse payment gateway support; consider partnering with credit/UPI providers for exclusive cashback offers.
