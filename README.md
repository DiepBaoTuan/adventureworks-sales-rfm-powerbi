# AdventureWorks Sales & RFM Customer Analysis (Power BI)

A Power BI report on the **AdventureWorks** sales database. It analyses customers, products and sales over time, segments customers with **RFM (Recency, Frequency, Monetary)**, and turns the findings into business recommendations.

**File:** [`INSIGHTS AND RECOMMENDATION PROJECT ADVENTUREWORKS.pbix`](INSIGHTS%20AND%20RECOMMENDATION%20PROJECT%20ADVENTUREWORKS.pbix). Open it with [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free).

## Report pages

| Page | What it shows |
|---|---|
| **Customers overview** | Customers by continent and country, customer count vs. revenue over time, RFM customer segments, quantity sold by product category |
| **Production** | Sales orders by product subcategory, quantity per customer, and how each RFM segment is distributed across products |

## Analysis approach

1. **Data model:** relationships between the AdventureWorks tables (sales orders, customers, products, categories and subcategories, locations), with a date hierarchy.
2. **RFM segmentation:** customers are scored on how recently, how often and how much they buy, then grouped into segments.
3. **Insights:** the report shows which regions, product categories and customer segments drive revenue.
4. **Recommendations:** the insights are turned into business recommendations for each customer segment.

## Skills demonstrated

Data modelling · RFM segmentation · DAX · Date hierarchies · Geographic analysis · Business storytelling
