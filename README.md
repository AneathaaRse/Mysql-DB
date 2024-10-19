 Database Overview

This project outlines a simple e-commerce system consisting of three main tables: `customers`, `orders`, and `products`. The database manages customer information, product listings, and order records.

## Key Tables

1. **customers**: Stores customer details like name, email, and address.
2. **orders**: Stores order details, including customer reference, order date, and total amount.
3. **products**: Stores product information such as name, price, and description.

### Additional Table (Normalization)

- **order_items**: This table normalizes the database by breaking down the relationship between `orders` and `products`. It tracks the quantity of each product in an order.

## Queries

Sample SQL queries are provided to:
- Retrieve customer orders.
- Update product prices.
- Add new fields.
- Normalize the database.

## Usage

Run the provided SQL queries to set up and manage the database.


