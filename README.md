# SQL-Intermediate-Joins-INNER-LEFT
# SQL-Intermediate-Joins-INNER-LEFT-

Dataset Information

Dataset Name: Chinook Database

SQL File Used: Chinook_MySql.sql

🛠 Tools & Technologies

MySQL Workbench

Key Relationships

customer.CustomerId → invoice.CustomerId

invoice.InvoiceId → invoiceline.InvoiceId

track.TrackId → invoiceline.TrackId

genre.GenreId → track.GenreId

Tasks Performed
Data Loading

Imported Chinook_MySql.sql into MySQL Workbench

Verified tables using:

SHOW TABLES;

INNER JOIN – Customers with Orders

Combined customer details with their orders to analyze transactional data.

LEFT JOIN – Customers Without Orders

Identified customers who have never placed an order, useful for marketing and retention strategies.

Revenue per Product

Joined order details with products to calculate total revenue per product and identify high-performing SKUs.

Category-wise Revenue Analysis

Joined products with categories to analyze revenue distribution across genres.

Conditional Analysis Using WHERE

Applied filters on joined tables to answer business questions such as:

Sales by country

Sales between specific date ranges

Use of Aliases

Used clear aliases (c, i, il, t, g) to ensure queries are readable, professional, and scalable.
