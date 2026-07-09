# E-Commerce Order Fulfillment & Delivery Performance Dashboard

## Overview
This project analyzes 96,000+ order deliveries from the Olist Brazilian e-commerce marketplace to identify fulfillment bottlenecks, measure on-time delivery performance, and provide actionable insights for logistics teams.

**Live Dashboard:**   (https://public.tableau.com/views/olist_delivery_dashboard_17834668513070/EcommerceOrderFulfillmentDeliveryPerformance?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Tools Used
- **SQL (SQLite)** — Data cleaning, table joins, feature engineering, analytical queries
- **Excel** — Pivot tables, conditional formatting, data bars, trend charts
- **Tableau Public** — Interactive dashboard with KPI cards, map, trend lines, and category breakdowns

## Data Source
Brazilian E-Commerce Public Dataset by Olist (available on Kaggle):  
https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

## Project Structure

## Key Metrics Tracked
- **On-Time Delivery Rate:** 92.4%
- **Average Delivery Delay:** 1.8 days
- **Total Orders Analyzed:** 96,000+
- **Orders >3 Days Late:** 8.5%

## Key Insights
1. **Worst-performing category:** Furniture & decor averages 4+ day delivery delays, likely due to shipping complexity and product dimensions.
2. **Geographic bottlenecks:** Two northern states (RR and AP) exceed 5-day average delays, indicating last-mile delivery challenges.
3. **Seasonal pattern:** On-time delivery drops 3 percentage points during November–December holiday season.
4. **Seller variability:** The bottom 10% of sellers account for 18% of all late deliveries.

## Dashboard Features
- KPI cards for overall metrics
- Filled map of average delay by Brazilian state
- Monthly trend line of on-time delivery percentage
- Bar chart of average delay by product category
- Delay distribution by bucket (on-time, 1–3 days, 4–7 days, >7 days)
- Filters for date range, product category, and state

## How to Recreate
1. Download the Olist dataset from Kaggle.
2. Import CSVs into SQLite using DB Browser for SQLite.
3. Run the `olist_delivery_analysis.sql` script to clean and query the data.
4. Export query results and build pivot tables in Excel.
5. Connect Tableau Public to the exported CSV or SQLite database.
6. Build dashboard sheets and assemble them.

## Contact
Jonathan Figaro  
(https://www.linkedin.com/in/jonathan-figaro-343221394/)  
j.figaro999@gmail.com
