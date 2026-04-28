# Dahel-Technology-Internship-SQL-project
NORTHWIND SQL PROJECT
The following quries were used to explore the northwind database: 
After creating the database using create database northwind;
Selected the database (use northwind;)
Showing all tables that were loaded into the northwind database (show table;)
Examined customers table  structure, Retrieved first 10 records from
customers
orders
products.
Advanved SQL Analysis second file
The section contains additional SQL queries performed the Northwind database
Revenue Calculation(Calculated total revenue using (SELECT ROUND(SUM(od.quantity * od.unit_price * (1 - od.discount)), 2) AS total_revenue
FROM order_details od;  (This shows total sales after discount)  Customer count: calculated total number of customers in the database:SELECT COUNT(*) AS total_customers
FROM customers;
