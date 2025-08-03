# Performance Tuning & Optimization Notes

## DAX Optimization
- Used VAR to cache intermediate results and avoid repeated calculations
- Replaced complex FILTER expressions with simple column comparisons where possible
- Used DIVIDE() instead of / to handle division by zero
- Avoided CALCULATE(FILTER(...)) anti-patterns

## Model Compression
- Set correct data types:
  - Whole Number → for IDs
  - Decimal → for prices
  - Text → only where needed
- Removed unused columns (e.g., duplicate keys)
- Used query folding in Power Query to push transformations to source

## Mobile Layout
- Designed mobile layout in Power BI Desktop (View > Mobile Layout)
- Prioritized key KPIs: Total Sales, QTD Sales, Online sales etc 
- Simplified visuals for small screens

## Load Time
- Initial load: ~8 seconds
- After optimization: ~3 seconds
- File size: 5.2 MB (compressed)

## Best Practices Applied
- Star schema with proper relationships
- Marked date[full_date] as Date Table
- Used parameters for dynamic filtering (e.g., discount threshold)
- Enabled drill-through from summary to customer-level details