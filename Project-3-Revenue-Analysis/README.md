# Revenue Analysis Dashboard (Power BI)

A multi-page Power BI report analyzing retail revenue across time, brands, stores, and geography, with a revenue forecast for the next period.

## Business Questions
- How much revenue is the business generating and how did it change over the years?
- Which brands, stores, and states contribute the most?
- How do returns and customer segments (gender) affect performance?
- What does future revenue look like?

## Dataset
- **Source:** Retail sales dataset (add the link here)
- **Period:** January 1997 to December 1999
- **Scope:** 24 stores in the USA, Mexico, and Canada, with 1,560 product types in stock
- **Data model:** a star schema with the tables `sales`, `Customer`, `Product`, `Region`, `Stores`, and `Return`

## Tools
Power BI Desktop: Power Query (data cleaning), Data Modeling (relationships), DAX measures, interactive visuals, slicers, bookmarks and page navigation, custom tooltip page, forecasting (Analytics pane)

## Report Pages

### 1. Home
Landing page with navigation buttons to all pages.

### 2. Sales Revenue
KPI cards, revenue by year (with year buttons), revenue by gender, by product brand, by store, and by state, with slicers for date, region, member card, brand, and country.

### 3. Geography
Revenue by location across stores and regions.

### 4. Tooltips
A custom tooltip page that shows the revenue share by brand when hovering over visuals.

### 5. Forecasted Sales Revenue
Monthly revenue trend with a forecast for 2000 and its confidence interval.

## Key Insights

| KPI | Value |
|-----|-------|
| Total Revenue | **$2.77M** |
| Quantity Sold | **1.31M** |
| Number of Stores | **24** |
| Average Product Cost | **0.85** |
| Quantity Returned | **8,289 (about 0.6% of units sold)** |

1. **Revenue doubled in 1998:** from $0.57M in 1997 to $1.20M in 1998 (about +110%), with a clear jump starting in January 1998.
2. **Decline in 1999:** revenue fell to $1.01M (about -16%) after the peak of about $120K in December 1998, then stabilized around $80K-$88K per month.
3. **Washington state leads:** WA generated $0.86M (about 31% of total revenue), followed by CA ($0.50M) and OR ($0.37M).
4. **Brand revenue is highly fragmented:** the top brand (Hermanos) brings only about 3% of revenue ($87K), so no single brand dominates and the business does not depend on one supplier.
5. **Store performance:** Store 13 ($0.21M) and Store 17 ($0.20M) are the top performers.
6. **Balanced customer base:** revenue is split almost evenly between female (49.9%) and male (50.1%) customers, so campaigns do not need to be gender-specific.
7. **Forecast:** the model projects revenue staying around the 1999 level with a very wide confidence band, meaning high uncertainty and the need for more data (such as seasonality and promotions) for reliable planning.

## Recommendations
- Investigate the **1999 decline** (competition, product mix, store performance) and replicate what worked in 1998.
- Strengthen performance in lower-performing stores by learning from Store 13 and Store 17.
- Keep a diversified brand portfolio, while negotiating better terms with the top 10 brands.
- Use the forecast as a rough guide only, and refine it with more history.
