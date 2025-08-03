# Performance Tuning & Optimization Notes

## DAX Optimization
- Used VAR to cache intermediate results and avoid repeated calculations.
- Replaced complex FILTER expressions with simple column comparisons where possible.
- Used DIVIDE() instead of / to handle division by zero.
- Avoided CALCULATE(FILTER(...)) anti-patterns.

## Model Compression
- Set correct data types:
  - Whole Number → for IDs
  - Decimal → for prices
  - Text → only where needed
- Removed unused columns (e.g., duplicate keys)
- Used query folding in Power Query to push transformations to source.

## Mobile Layout
- Designed a dedicated mobile layout for a seamless user experience on smaller devices.
- The mobile layout prioritizes the display of key KPIs such as Total Sales, Total Customers and Revenue by Product, to ensure critical information is always accessible.
- Simplified visuals were used to improve readability and performance on small screens.

## Load Time
- The dashboard is optimized for fast loading and responsiveness, providing a smooth experience for users.

## Best Practices Applied
- Star schema with proper relationships.
- Marked date[full_date] as Date Table.
- Used parameters for dynamic filtering such as the slicers for Store Name, City, State and Manager on the dashboards.
- Enabled drill-through functionality, allowing users to navigate from high-level summaries to more detailed views.
