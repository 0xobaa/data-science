# E-Commerce Sales Database (SQL)

A relational database built in MySQL to model a small Nigerian e-commerce business, then queried to answer the kind of questions an owner would actually ask.

**File:** `ecommerce_sales_database.sql`

## Design

Three normalised tables:

- `customers` — 10 records
- `products` — 10 records
- `orders` — 20 records

## Queries

The script works through a set of business questions:

- Every order joined to its customer and product details
- Lagos customers who signed up in 2024
- Total revenue per product
- The three highest-spending customers
- Products ordered more than twice (`HAVING`)
- Customer status classified with `CASE`
- Products never bought and customers with no orders (`LEFT JOIN`)

## Stack

MySQL: schema design, joins, aggregation, subqueries, conditional logic.
