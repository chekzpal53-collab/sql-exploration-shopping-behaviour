# Customer Shopping Behavior Analysis — SQL

Analyzed a retail customer dataset using PostgreSQL to answer 10 business questions across revenue, product performance, discounts, and customer loyalty.

## Dataset
A single `customer` table with fields including `gender`, `age_group`, `item_purchased`, `category`, `purchase_amount`, `review_rating`, `shipping_type`, `discount_applied`, `subscription_status`, and `previous_purchases`.

## Questions Explored

| # | Question | Technique |
|---|---|---|
| 1 | Revenue by gender | GROUP BY + SUM |
| 2 | Discount users who outspend the average | Subquery |
| 3 | Top 5 products by average review rating | AVG + ORDER BY |
| 4 | Standard vs Express shipping spend | Filtered aggregation |
| 5 | Do subscribers spend more? | GROUP BY + AVG + SUM |
| 6 | Products with highest discount rate | CASE WHEN inside SUM |
| 7 | Segment customers: New / Returning / Loyal | CTE + CASE WHEN |
| 8 | Top 3 products per category | ROW_NUMBER() OVER (PARTITION BY) |
| 9 | Are repeat buyers likely to subscribe? | WHERE filter + GROUP BY |
| 10 | Revenue contribution by age group | GROUP BY + SUM |

## Skills Used
`PostgreSQL` `CTEs` `Window Functions` `Subqueries` `CASE WHEN` `Aggregations` `Customer Segmentation`

## Tools
PostgreSQL · pgAdmin / DBeaver
