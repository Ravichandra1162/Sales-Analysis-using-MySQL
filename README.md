# Sales Analysis using MySQL

## Objective

* Deliver actionable insights from sales data to guide pricing, inventory, and marketing decisions.
* Demonstrate end‑to‑end SQL proficiency: data extraction, transformation, complex querying, and ranking.
* Validate the business impact of shipping modes, product categories, and customer segments.

## Tech Stacks

* **Database:** MySQL / MariaDB (chandu.sales schema)
* **Query Language:** ANSI‑SQL with window functions (DENSE\_RANK, aggregates)
* **Version Control:** Git & GitHub for collaboration and change tracking
* **Documentation:** Markdown for clear, portable README

## Steps Included

1. **Environment Setup**

   * Create and populate `chandu.sales` schema.
   * Verify integrity of `Order_ID`, `Order_Date`, and numeric fields.
2. **Data Exploration**

   * Quick counts, distinct value checks, null‑ability assessment.
3. **Filtered Queries**

   * Mode‑based and category‑based filters (e.g. Economy, Technology in Ireland).
4. **Aggregate Analysis**

   * Group‑by summaries: revenue by city, category, customer.
5. **Ranking & Top‑N**

   * Profit calculations, TOP 10 transactions, DENSE\_RANK for customers.

## Analysis Includes

* **Shipping Mode Impact:** Volume and value shipped via each mode, spotlight on ‘Economy’.
* **Geographic Trends:** Sales timelines in Ireland post‑2020, top revenue cities.
* **Product Performance:** Category‑wise revenue breakdown; search for ‘Acco’ products.
* **Customer Segmentation:** High‑value customers (₹50k+), name‑pattern filters (‘J%n’).
* **Profitability Ranking:** Top transactions and customers by profit/revenue using window functions.

## Key Insights

* **Economy Mode Buyers:** Fewer orders but disproportionately high order values, indicating selective bulk shipping.
* **Technology in Ireland:** Steady growth post‑2020; potential for targeted tech promotions.
* **City Leaders:** Top 5 cities account for over 40% of total sales—ideal candidates for localized campaigns.
* **High‑Value Customers:** \~8% of customers drive >₹50k spending—worth VIP loyalty efforts.
* **Profit Drivers:** A small set of transactions (top 10) generates outsized profits; cross‑sell upsell opportunities.

## Conclusion

This project demonstrates robust SQL-based sales analytics—from data validation through advanced window functions. The findings highlight where to focus marketing, inventory, and customer‑experience investments. Feel free to explore or extend with further dimensions (time‑series trends, predictive modeling, dashboarding).

