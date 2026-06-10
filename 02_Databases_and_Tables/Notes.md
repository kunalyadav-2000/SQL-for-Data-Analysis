# What is a Database? & Relational Databases

## Overview
A **database** is an organised collection of structured data, typically stored electronically.  
A **relational database** organises data into one or more tables where relationships can be defined between them.

## Why It Matters
Businesses run on data. A database ensures that data is:
- **Persistent** (survives after an application closes)
- **Consistent** (same rules for everyone)
- **Secure** (only authorised access)
- **Efficiently searchable**

## Real‑World Analogy
Imagine a library:
- The **library** is the database.
- **Shelves** are tables.
- **Books on a shelf** are rows.
- **Book details (title, author, ISBN)** are columns.

## Learning Objectives
- Define a database and a relational database.
- Differentiate between flat files (Excel) and relational databases.
- Understand the concept of tables and relationships using primary/foreign keys.

## Key Concepts
- **Database**: A container that holds multiple tables.
- **Relational Model**: Data is split into logical tables linked by keys to reduce redundancy (normalisation).
- **Schema**: The blueprint of a database (table names, columns, data types).

## Business Use Case
A retail company’s database might have separate tables for `customers`, `orders`, `products`, and `inventory`. The `orders` table links to `customers` via a customer ID, and to `products` via a product ID. This design avoids duplicating customer details in every order row.

## Interview Questions
1. **Beginner:** What is a relational database?  
   *Answer:* A database that stores data in tables with rows and columns, using keys to establish relationships between tables.
2. **Intermediate:** Why would a company use a database instead of a spreadsheet?  
   *Answer:* Databases can handle millions of rows, support concurrent users, enforce data integrity, and join multiple tables efficiently – impossible with a spreadsheet.
3. **Scenario:** You have customer data in a CSV and orders in another. How would you relate them?  
   *Answer:* Import both into database tables with a common column (e.g., customer_id), then use SQL JOINs to combine the information for analysis.

## Summary
Relational databases are the backbone of enterprise data. Understanding tables and relationships is essential before writing queries.