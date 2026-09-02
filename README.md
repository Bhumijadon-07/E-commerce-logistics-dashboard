# E-commerce-logistics-dashboard
An interactive Power BI dashboard analyzing 180,000+ e-commerce orders
to track delivery performance, shipping costs, and profitability.

## 📊 Overview

This project simulates a real-world logistics analytics use case inspired
by platforms like Amazon and Flipkart, using a public supply chain dataset.

## Dashboard Pages

1. **Executive Overview** — Total orders, on-time delivery %, average
   delivery time, and total profit at a glance
2. **Delivery Performance** — Late delivery trends by region, shipping
   mode, and time, with drill-down to order-level detail
3. **Cost & Warehouse Analysis** — Profit margin, sales by category, and
   performance by customer segment

## Tools & Techniques

- **Power Query** — data cleaning, type correction, encoding fixes
- **Data Modeling** — star schema with a dedicated date dimension table
- **DAX** — custom measures for on-time delivery %, late delivery %,
  profit margin %, and year-over-year growth
- **Power BI Desktop** — custom dark theme, interactive slicers, drill-through

## Dataset

[DataCo Smart Supply Chain Dataset](https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis)
(Kaggle, public dataset)
