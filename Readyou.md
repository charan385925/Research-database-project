![ChatGPT Image Jun 13, 2025, 12_22_33 PM 2](https://github.com/user-attachments/assets/d9cce518-57a8-4249-9578-9311186e7746)


# 📚 Online Book Publishing and Sales Platform

This project is a **relational database design** for an online book publishing and sales system. It models various real-world entities involved in book publishing, customer interaction, and online ordering.

---

## 🔍 Project Overview

The system is designed to manage:

- Books (with details like title, edition, ISBN, price, genres, publisher, etc.)
- Authors and their works
- Customers, their purchase history, shipping addresses, and wishlists
- Orders and order items with pricing and discount data
- Payments and shipment statuses

---

## 🧱 Database Schema Includes

### 🗂️ Core Tables

- `BOOK`: Stores book details like title, edition, ISBN, price, etc.
- `AUTHOR`: Information about authors and their bios.
- `PUBLISHER`: Publisher details for each edition of a book.
- `GENRE`: Genres assigned to books.
- `CUSTOMER`: Customer information and purchase history.
- `SHIPPING_ADDRESS`: Multiple shipping addresses per customer.
- `WISHLIST`: Books added to wishlists by customers.
- `ORDER`: Order data including shipping, payment, and status.
- `ORDER_ITEM`: Line-items in each order with discounts and quantities.
- `PAYMENT`: Payment records for each order.

### 🔗 Junction Tables

- `BOOK_AUTHOR`: Many-to-many relation between books and authors.
- `BOOK_GENRE`: Many-to-many relation between books and genres.

---

## 💾 Sample Data

Sample `INSERT` statements are included to:

- Add authors, publishers, books, genres, and customers
- Add wishlists and shipping addresses
- Record orders, order items, and payment transactions

Example:
```sql
INSERT INTO BOOK VALUES 
(101, 'The Great Gatsby', '9780743273565', '1st', 1925, 15.99, 1);
```

---

## 📌 Features

- 📚 Support for multiple authors per book
- 📦 Order management with quantity, discounts, and status tracking
- 🧾 Payment tracking with methods and statuses
- 📜 Wishlist and purchase history for customers
- 🎯 Normalized schema with foreign key constraints

---

## 🧪 Technologies Used

- SQL (MySQL / PostgreSQL syntax)
- Relational Database Design
- Entity-Relationship Modeling

- 

---
![project 3 img](https://github.com/user-attachments/assets/f4fdb3e4-087a-4d1f-9bc0-6a5212061bfc)


👨‍💻 *Developed by a first-year student exploring full-stack database systems through real-world scenarios.*

Feel free to fork, clone, or enhance the schema for your own e-commerce, bookstore, or academic projects!
