E-Commerce Database Schema Design

Objective
Design and implement a normalized relational database schema for an online store using SQL Server Management Studio 21. 
This project demonstrates proficiency in database setup, table creation, primary/foreign key relationships, and ER diagram visualization.

---

Schema Overview

Entities
- **Customers**: Stores customer details
- **Products**: Catalog of items available for purchase
- **Orders**: Tracks customer purchases
- **OrderItems**: Line items within each order
Relationships
- One customer can place many orders
- Each order can contain multiple products
- Products can appear in many orders (many-to-many via OrderItems)
