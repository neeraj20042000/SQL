# SQL Inventory Project

This code repository contains SQL Inventory Project for auto updation of Inventory Database on placing an order for a particular product

## Tables of the project

Tables of the database is as follows:

1\. Supplier - Details of the suppliers from where purchase order can be placed by the company for different products

2\. Product - Details of the products(including supplier), company is selling 

3\. Stock - Details of the each product stock including re-order level and minimum order quantity for placing new purchase

4\. Customers - Details of the customers placing orders

5\. Orders - Details of the orders placed (auto updating stock quantity in stock table as per order quantity)

6\. Purchase - Auto updated by stock table as per the stock quantity, re-order level and minimum order quantity of a product

## Features of the project

1\. Sequences - For auto increment of unique ID's in each table

2\. User defined function - For auto increment of unique ID's in each table

3\. Procedures - Adding a new record on each table

4\. Triggers - Auto updation of each and related table on insert, update or delete an order

## Reports generated

1\. Bill - Bill for each order

2\. Customer Ledger - Customer Ledger for each customer

3\. Daily Ledger - Daily Ledger for each customer

4\. Supplier products - Product details of each supplier

5\. Product Sales - Sales report of each product

## Clone the Repository

Clone the repository to your local machine using the following command:

```bash
git clone https://github.com/neeraj20042000/SQL.git
```

