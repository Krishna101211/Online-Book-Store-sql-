---

# 📚 Online Bookstore SQL Project

## 📌 Project Overview

The **Online Bookstore SQL Project** is a relational database project built using **PostgreSQL** that simulates a real-world online bookstore system.

The project demonstrates:

* Database design
* Table relationships (Primary & Foreign Keys)
* Data import using CSV
* Business-driven SQL queries
* Aggregate functions
* JOIN operations
* Grouping & filtering
* Revenue & stock analysis

This project showcases strong SQL fundamentals along with analytical query writing skills.

---

## 🛠️ Technologies Used

* **Database:** PostgreSQL
* **Language:** SQL
* **Tools:** pgAdmin / psql
* **Data Format:** CSV

---

## 🗂️ Database Schema

The database created is:

```sql
CREATE DATABASE OnlineBookstore;
```

### 📘 Tables Created

### 1️⃣ Books Table

Stores information about books available in the store.

| Column         | Description        |
| -------------- | ------------------ |
| Book_ID        | Primary Key        |
| Title          | Book Title         |
| Author         | Book Author        |
| Genre          | Book Category      |
| Published_Year | Year Published     |
| Price          | Book Price         |
| Stock          | Available Quantity |

---

### 2️⃣ Customers Table

Stores customer information.

| Column      | Description      |
| ----------- | ---------------- |
| Customer_ID | Primary Key      |
| Name        | Customer Name    |
| Email       | Email Address    |
| Phone       | Contact Number   |
| City        | Customer City    |
| Country     | Customer Country |

---

### 3️⃣ Orders Table

Stores purchase details.

| Column       | Description             |
| ------------ | ----------------------- |
| Order_ID     | Primary Key             |
| Customer_ID  | Foreign Key (Customers) |
| Book_ID      | Foreign Key (Books)     |
| Order_Date   | Date of Purchase        |
| Quantity     | Number of Books Ordered |
| Total_Amount | Total Price             |

---

## 🔗 Database Relationships

* One **Customer** can place multiple **Orders**
* One **Book** can appear in multiple **Orders**
* `Orders` table acts as a bridge between `Customers` and `Books`

---

## 📥 Data Import

Data was imported from CSV files using:

```sql
COPY table_name FROM 'file_path' CSV HEADER;
```

This simulates real-world production data loading.

---

# 📊 SQL Queries Implemented

The project includes **Basic to Advanced SQL queries** covering real business scenarios.

---

## 🔹 Basic Queries

✔ Retrieve books by genre
✔ Find books published after 1950
✔ Filter customers by country
✔ Find orders within a specific month
✔ Calculate total stock
✔ Find most expensive book
✔ Find lowest stock book
✔ Calculate total revenue
✔ Retrieve distinct genres

---

# 📈 Business Insights Derived

* Identified best-selling genres
* Calculated total revenue
* Found top-spending customer
* Analyzed inventory depletion
* Determined high-performing authors

---

# 🎯 Skills Demonstrated

* Database Design
* Normalization Concepts
* Primary & Foreign Keys
* INNER JOIN / LEFT JOIN
* GROUP BY & HAVING
* Aggregate Functions (SUM, AVG, COUNT)
* Filtering with WHERE
* Sorting with ORDER BY
* Business Query Writing
* Data Import from CSV
* Inventory & Revenue Analysis

---

# This project demonstrates:

✔ Real-world database structure
✔ Analytical thinking using SQL
✔ Business-oriented query writing
✔ Strong understanding of relational databases
✔ Ability to derive insights from structured data

It reflects practical SQL skills required for:

* Data Analyst
* SQL Developer
* Business Intelligence Roles
* Backend Developer

---

# 📌 How to Run the Project

1. Install PostgreSQL
2. Create the database
3. Run table creation queries
4. Import CSV files
5. Execute SQL queries

---

# 👨‍💻 Author

**KRUSHNA SHINDE**
SQL | Data Analytics | Database Design
