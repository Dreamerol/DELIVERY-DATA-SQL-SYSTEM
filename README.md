# DELIVERIES‑SQL

---

![SQL Data](https://raw.githubusercontent.com/Dreamerol/Dreamerol/9cc733b4ef8b54f63e8571152bbade25bd51ef12/SQL%20DATA.jpg)

---

## 🌈✨ Overview

A structured **SQL project** that models a basic **delivery system database**, including **users, items, addresses**, and their relationships.  
This repository contains the **database schema**, **sample inserts**, and **example queries** to explore delivery data efficiently.  
The project demonstrates how to design and work with **relational databases using SQL**.  

It includes:

✔️ Well-structured tables for **users, items, deliveries**, and related entities  
✔️ **Primary and foreign key relationships** to enforce data integrity  
✔️ **Sample data** for testing  
✔️ **SQL queries** for retrieving delivery tracking information  

### *This setup helps you understand **real-world database organization** and how to query related data across tables using **joins, aggregations, and filters**.*


---

## 🧱 Database Schema

The database is designed with multiple related tables. Each table serves a specific purpose:

### 👤 Users Table  
Stores registered users including their profile information.

### 📦 Items Table  
Contains all item details which can be delivered.

### 🚛 Deliveries Table  
Tracks orders or packages being delivered.

### 🎯 Relationships

- Each **delivery** belongs to a **user**  
- Deliveries are linked to items so you can fetch details like delivery contents, status, and schedule  

Relational databases allow you to **connect data across tables** using foreign keys, keeping data consistent and easy to fetch. :contentReference[oaicite:1]{index=1}

---

## 🧠 How It Works

This repository includes:

### 📌 Schema Files  
Define the database structure using `CREATE TABLE`.

### 📥 Insert Scripts  
Insert sample data into the tables for testing queries.

### 🔍 Select Queries  
Examples of real SQL usage:

- Fetch all deliveries for a specific user  
- Count deliveries per date  
- Join users with their delivery records  

These example queries demonstrate how to use SQL to retrieve meaningful insights from a relational dataset. :contentReference[oaicite:2]{index=2}

---

## 💡 Core SQL Concepts

This project showcases:

### 🪪 Relational Structure  
Use of **primary keys** to uniquely identify rows and **foreign keys** to relate tables.

### 🧾 Joins  
Retrieve data from multiple tables by linking fields (e.g., `INNER JOIN`, `LEFT JOIN`).

### 📊 Filtering & Sorting  
Using `WHERE`, `ORDER BY`, and conditions to shape output.

### ✨ Aggregation  
Counting, grouping, and summarizing data (e.g., number of deliveries per user).

These concepts reflect standard practices in database design and querying.

---

## 📂 Included Files

| File | Description |
|------|-------------|
| `dostavki_project1.png` | ER diagram / project visual |
| `dostavki1.txt` | Raw SQL for creating tables |
| `insert_project.txt` | Sample insert data |
| `select.txt` | Example SELECT queries |

---

## 🔌 Getting Started

1. Import the SQL schema into your database (MySQL, PostgreSQL, SQL Server, etc.)
2. Run the insert scripts to populate sample data
3. Use the provided queries to explore the dataset
4. Modify or add your own queries for deeper analysis

---

## 🏁 Learning Outcomes

By exploring this project, you’ll gain experience with:

- Creating and linking relational tables  
- Writing SQL queries for real use cases  
- Analyzing delivery data using joins and conditions  
- Understanding database relationships and normalization

---


## ⭐ Acknowledgements

Thanks to everyone exploring SQL database design and joining the delivery system learning journey!
