# Big-Data-For-Manager-Project-1

**Chaayos Database Project**

*Overview*
This project is a database design and implementation exercise focused on the Chaayos tea café chain. The primary objective was to create a robust database schema that efficiently manages data related to stores, employees, customers, products, orders, and order details, along with implementing user roles and access control.

*Project Structure*
The project consists of the following key components:

*Entity-Relationship Diagram (ERD)*
A visual representation of the database structure, showing the relationships between different entities like Stores, Employees, Customers, Products, Orders, and Order Details.

*SQL Schema*
SQL code for creating tables for each entity in the database:
Stores: Stores data related to Chaayos branches.
Employees: Contains details about the employees working in various stores.
Customers: Records customer information.
Products: Manages the product catalog, including product categories, prices, and stock levels.
Orders: Captures customer orders, associating them with the respective store and employee.
OrderDetails: Tracks specific products ordered, including quantity and price at the time of the order.

*Insert Statements*
SQL insert statements to populate the tables with sample data. These establish relationships across the database entities to simulate real-world operations at Chaayos.
User Roles and Access Control

*Implementation of Data Control Language (DCL) commands to assign roles and manage permissions:*
Manager (Alice): Granted full access to all database tables.
Employee (Bob): Granted read-only access to specific tables like Customers, Products, and Orders.

*How to Use*

*Database Setup:*
Clone the repository and execute the provided SQL scripts to create the database schema.
Use the insert statements to populate the tables with initial data.

*Access Control:*
Run the DCL commands to create users and assign roles. This sets up a manager with full privileges and an employee with restricted access.

*Assumptions*
The project assumes a basic understanding of SQL and database management.
User roles are defined based on typical responsibilities within a retail environment.

*Contributors*
Manish Mrityunjay Mohapatra (045029)
Parth Narula (045039)
Rahul Gohri (045044)
