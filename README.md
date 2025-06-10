# E-Commerce Sales Dashboard

This project presents sales performance dashboards built using Tableau, based on an e-commerce orders dataset.

## Project Files

- `ecommerce_orders_clean.xlsx` → Cleaned dataset (manually cleaned in Excel).
- `ecommerce_sales_dashboard.twbx` → Tableau packaged workbook → Dashboard 1: Executive Overview.
- `ecommerce_sales_dashboard.op.twbx` → Tableau packaged workbook → Dashboard 2: Operational Insights.
  
## Dashboards Overview
### Dashboard 1: Executive Overview

Summary of sales performance:

- **Key KPIs** → Total Revenue, Total Orders, Average Order Value (AOV), Unique Customers, Average Time to Ship.
- **Revenue Trend by Month** → A clear spike in sales during December 2019 and 2020, likely driven by holiday and New Year demand.
- **Top Products**:
  - *By Revenue*: 27-inch 4K Gaming Monitor dominates revenue, despite lower sales volume.
  - *By Volume*: Nintendo Switch leads in sales volume, indicating its popularity.
  
**Key Insight**:  
High-priced products (e.g., gaming monitors) drive substantial revenue even with lower sales volumes.  
Further analysis using Order Timestamps can help identify product sales trends to inform restocking strategies.

### Dashboard 2: Operational Insights

Operational performance and customer behavior:

- **Shipping Performance**:
  - Average time to ship remains very stable at ~2 days.
  - Slight peak in June 2019 (~3 days), suggesting possible seasonal/logistical challenges.

- **Purchase Platform**:
  - 90% of purchases occur via the website.
  - Suggestion: prioritize enhancements on the website experience:
    - Faster server response times
    - Improved UI/UX for checkout and navigation
    - Personalization and product recommendations

- **Marketing Channel Effectiveness**:
  - Majority of revenue comes from Direct and Email channels.
  - Strong emphasis on in-store customer service is important to drive repeat purchases.

- **Geographic Sales**:
  - The US dominates revenue, as indicated by a significantly darker blue tone on the map.
  - Possible reasons include larger population, higher purchasing power, and greater consumer spending mentality.

## Credits

Dataset source: [Christine Jiang Data on YouTube](https://www.youtube.com/@christinejiangdata).  

## Notes

- The dataset was cleaned in Excel before importing to Tableau.
- Minor data inconsistencies (e.g., extra spaces) were handled via calculated fields and filtering in Tableau.
