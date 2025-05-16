# 📚 Library Management System

## 📖 Project Overview  
This project is a **Library Management System** built using **MySQL**. It allows users to manage books, authors, categories, members, and loans efficiently.

## 🛠 Features  
- Add and manage **books** with categories.
- Track **authors** and their published works.
- Maintain **library members** and their details.
- Handle **borrowing and returning books** via loans.
- View reports on **book availability and loan history**.

## 🔗 Database Schema  
The system includes the following key tables:
- **Books**
- **Authors**
- **Categories**
- **Members**
- **Loans**
- **BooksAuthors** (for many-to-many relationships)

## 🚀 Setup Instructions  
1. **Clone the Repository**  
   ```bash
   git clone https://github.com/yourusername/library-management-system.git
   cd library-management-system
   ```

2. **Import Database**  
   Open MySQL and run:
   ```sql
   source library_management.sql;
   ```

3. **Verify Tables**  
   ```sql
   SHOW TABLES;
   ```

4. **Run Queries**  
   Try some queries:
   ```sql
   SELECT * FROM Books;
   ```

## 📌 Entity Relationship Diagram (ERD)  


---

