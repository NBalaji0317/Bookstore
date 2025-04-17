# 📚 Book Database Management System (BDMS)

A scalable and normalized relational database system to manage book-related information such as authors, categories, publishers, books, and pricing — built using PostgreSQL and Python.

---

## 🔍 Overview

The BDMS project addresses the inefficiencies of managing complex book datasets using flat files like Excel. It provides a normalized, relational database with optimized queries for real-world use cases such as libraries, bookstores, and publishers.

---

## 🛠️ Tech Stack

- **Database**: PostgreSQL
- **Scripting**: Python (for data cleaning and loading)
- **Data Source**: [BooksDatasetClean.csv](https://www.kaggle.com/datasets/books)
- **SQL Scripts**: `create.sql`, `load.sql`

---

## 🧱 Database Schema

The schema consists of the following tables:

| Table      | Description                              |
|------------|------------------------------------------|
| authors    | Stores author ID and name                |
| categories | Stores category ID and name              |
| publishers | Stores publisher ID and name             |
| books      | Links books with authors, categories, and publishers |
| prices     | Stores price history for each book       |

All tables are in **BCNF** to minimize redundancy and preserve data integrity.

---

## 📌 Features

- ✅ Fully normalized schema (BCNF)
- ✅ Handles many-to-one relationships (book-author, book-category)
- ✅ Python script for cleaning and truncating overlength author names
- ✅ Advanced SQL queries using JOIN, GROUP BY, and aggregate functions
- ✅ Indexing strategies for performance optimization
- ✅ Sample dataset for testing schema

---


