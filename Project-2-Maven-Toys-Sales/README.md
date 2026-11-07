# Maven Toys Sales Analysis (Power BI)

An interactive Power BI dashboard analyzing sales, profit, and inventory for Maven Toys, a toy store chain in Mexico, to identify the best-performing locations and categories and where the business is losing sales.

## Business Questions
- How much revenue and profit is the business generating, and how is it trending over time?
- Which store locations and product categories are the most profitable?
- Where are sales being lost, and how does that relate to inventory?

## Dataset
- **Source:** Maven Analytics Toy Sales dataset (add the link here)
- **Period:** January 2022 to September 2023
- **Scope:** 50 stores across Mexican cities, 35 products in 5 categories
- **Tables:** Sales, Products, Stores, Inventory (modeled with relationships in Power BI)

## Tools
Power BI Desktop: Power Query (data cleaning), Data Modeling, DAX measures, interactive visuals, slicers

## Dashboard Features
- KPI cards: Number of Products, Number of Stores, Profit, Revenue, Average Product Price, Products Sold
- Slicers: Date range, Store City, Store Name
- Visuals: Revenue trend by month, profit by store location, profit by product category, stock on hand by location, lost sales by location

## Key Insights

| KPI | Value |
|-----|-------|
| Total Revenue | **$14.4M** |
| Total Profit | **$4.0M** |
| Profit Margin | **about 28%** |
| Products Sold | **829.3K** |
| Average Product Price | **$14.8** |

1. **Downtown drives the business:** it generates $2.2M of the $4.0M profit (about 55%), followed by Commercial ($0.9M), Residential ($0.5M), and Airport ($0.4M).
2. **Toys and Electronics lead the categories:** Toys ($1.08M) and Electronics ($1.00M) together bring about half of the profit, ahead of Art & Crafts ($0.75M), Games ($0.67M), and Sports & Outdoors ($0.51M).
3. **Strong growth in 2023:** revenue for January to September 2023 (about $7.0M) is roughly 30% higher than the same months of 2022 (about $5.3M).
4. **Seasonality:** monthly revenue peaks at $0.88M in December 2022 and again in March 2023, and is lowest in August 2022 ($0.49M).
5. **Downtown also has the biggest lost sales ($66K)** and the highest stock on hand (17.2K units), which points to an inventory allocation issue: the right products are not always in stock at the right time.

## Recommendations
- Improve **inventory planning in Downtown stores** to reduce lost sales at the highest-revenue location.
- Prepare stock and promotions ahead of the **December peak**.
- Focus marketing and assortment on **Toys and Electronics**, and review Sports & Outdoors for improvement.
- Study why Airport stores have the lowest profit, and whether a different product mix would help.
