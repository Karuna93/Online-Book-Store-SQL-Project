# 📚 Online Book Store – SQL Project (PostgreSQL)

This is a relational database project for an **Online Book Store** developed using **PostgreSQL**. 
It includes a complete SQL script for schema creation, data import from CSV files, and a wide range of SQL queries — from basic selections to advanced analytics and aggregation.


## 📁 Project Structure

Online-Bookstore-Project/
├── Online Book Store.sql  # Main SQL script with all queries
├── books.csv              # Sample data for Books table
├── customers.csv          # Sample data for Customers table
├── orders.csv             # Sample data for Orders table
└── README.md              # Project documentation


## 🧱 Database Schema

### 📘 Books Table
Stores book information such as title, author, genre, price, and stock.
(Book_ID, Title, Author, Genre, Published_Year, Price, Stock)

### 🧑‍💼 Customers Table
Contains customer details including contact and location information.
(Customer_ID, Name, Email, Phone, City, Country)

### 🛒 Orders Table
Represents orders placed by customers along with order date and quantity.
(Order_ID, Customer_ID, Book_ID, Order_Date, Quantity, Total_Amount)


## 💻 How to Run

1. Open **pgAdmin** or your PostgreSQL client.
2. Create a new database (e.g., onlinebookstore).
3. Open the OnlineBookStore.sql file and execute the script.
4. Execute all queries to view and analyze data.

## 🔍 Queries Covered

### ✅ Basic Queries
- Retrieve all books in the "Fiction" genre.
- Find books published after the year 1950.
- List all customers from Canada.
- Show orders placed in November 2023.
- Retrieve the total stock of books available.
- Find the most expensive book.
- Show all customers who ordered more than 1 quantity.
- Retrieve all orders where the total amount exceeds $20.
- List all genres available in the Books table.
- Find the book with the lowest stock.
- Calculate the total revenue generated from all orders.

### ✅ Advanced Queries
- Retrieve total books sold for each genre.
- Find the average price of books in the "Fantasy" genre.
- List customers who have placed at least 2 orders.
- Find the most frequently ordered book.
- Show top 3 most expensive books in the "Fantasy" genre.
- Retrieve the total quantity of books sold by each author.
- List cities where customers who spent over $30 are located.
- Find the customer who spent the most on orders.
- Calculate stock remaining after fulfilling all orders.


## 🧪 Features Demonstrated

- Relational database schema design.
- Data import using PostgreSQL 'COPY' command.
- Use of `SELECT`, `JOIN`, `GROUP BY`, `ORDER BY`, `HAVING`, `LIMIT`, `DISTINCT`.
- Aggregate functions: `SUM`, `COUNT`, `AVG`, `MAX`, `MIN`.
- Query optimization using filters and indexing concepts.
- Business-focused insights from structured data.


## 🛠️ Tools Used

- PostgreSQL
- pgAdmin
- CSV Files (for sample data)


## ⚠️ Notes

- Ensure the `.csv` file paths are correctly set when using the `COPY` command.
- Compatible only with **PostgreSQL**. Not intended for MySQL Workbench.
- Great for academic submissions, SQL practice, and analytics learning.


