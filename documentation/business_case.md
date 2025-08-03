# Business Case: Retail Sales Optimization

## Scenario
A multi-channel retail company wants to improve profitability by analyzing sales performance across in-store, online, mobile app and phone order channels. The business faces challenges with:
- Inconsistent customer data.
- Lack of unified reporting.

## Objectives
1. Clean and model sales data into a star schema - The provided dashboards for Sales Overview, Product Insights, Customer Insights and Store Performance all seamlessly integrated under a single navigation menu, suggest that the underlying data has been consolidated and modeled for consistent reporting.
2. Identify top-performing products, stores and customer segments - The dashboards were designed to highlight key performers, such as the highest-revenue product categories (e.g., Cameras), the top-selling cities and the demographic with the highest sales quantity (e.g., Youth)
3. Analyze performance across different sales channels: The project focuses on comparing and contrasting performance between In-Store, Online and Mobile App channels, identifying which channel generates the most revenue and quantity sold.
4. Enable data-driven decision-making: The final Power BI dashboard is intended to be a tool for decision-makers, providing them with a clear view of business performance to guide strategic initiatives.

## Success Metrics
- Increased sales across all channels - Track key metrics like Total Sales and Total Revenue from Customers as shown on the dashboards to measure growth.
- Improved understanding of customer base - The Customer Distribution by State and Quantity Sold by Age Group visualizations are key to understanding and targeting specific customer segments.
- Enhanced product performance visibility - The Top 5 Revenue Generating Products and Revenue by Product charts provide a clear view of which products and brands are driving sales.
- Better insight into store-level performance - The Store Performance dashboard, including In-Store Sales and Revenue by Store City, provides the data needed to evaluate and optimize store operations.

## Data Sources
- Simulated sales fact table (3,500+ rows)
- Product, customer, store and date dimension tables.
- Data includes realistic quality issues: missing values, typos, negative sales (returns), inconsistent formats.

## Expected Outcomes
- A trusted single source of truth for sales analytics, as evidenced by the unified reporting across four distinct but related dashboards.
- Actionable insights into customer behavior and channel performance, such as the finding that the Youth demographic has the highest quantity sold and that Mobile App is the top-performing sales channel by revenue.
- Dashboard accessible via web link for stakeholders.
