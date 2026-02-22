# 📚 Online Bookstore SQL Analytics

## 🔷 Project Overview

This project demonstrates the design and analysis of an **Online Bookstore Database** using PostgreSQL.
It includes database creation, data import, and analytical SQL queries to extract business insights from bookstore operations.

The project simulates real-world scenarios such as inventory tracking, customer analysis, and revenue calculation.

---

## 🛠️ Tech Stack

* PostgreSQL
* pgAdmin 4
* SQL

---

## 📂 Dataset

The project uses three CSV datasets:

* Books.csv
* Customers.csv
* Orders.csv

These datasets are imported into PostgreSQL using the COPY command.

---

## 🗄️ Database Schema

The database consists of three main tables:

* **Books** — stores book details and inventory
* **Customers** — stores customer information
* **Orders** — stores order transactions

---

## 🔍 Key SQL Operations

### Basic Queries

* Retrieve books by genre
* Filter books by publication year
* Customer country filtering
* Monthly order filtering
* Total stock calculation
* Revenue calculation

### Advanced Queries

* Genre-wise books sold
* Average price by genre
* Customers with multiple orders
* Most frequently ordered book
* Author-wise sales
* Highest spending customer
* Remaining stock after orders

---

## ▶️ How to Run the Project

1. Create the database:

```sql
CREATE DATABASE OnlineBookstore;
```

2. Connect to the database:

```sql
\c OnlineBookstore;
```

3. Run the SQL script:

* Execute `online_bookstore.sql`

4. Ensure CSV file paths are correct in COPY commands.

---

## 📊 Sample Insights

* Total revenue generated from orders
* Most expensive book in inventory
* Top customers by spending
* Stock remaining after fulfilling orders

---

## 🚀 Future Improvements

* Add indexes for performance optimization
* Build dashboard using Power BI / Tableau
* Add stored procedures and views
* Implement triggers for stock updates

---

## 👤 Author

**Sachin Kumar**

---

⭐ If you find this project useful, consider giving it a star!
