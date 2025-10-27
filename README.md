# 🏧 ATM Database Management System

## 📘 Project Overview
The **ATM Database Management System** is a database-driven project designed to simulate the core backend structure of an Automated Teller Machine (ATM). It focuses on secure data storage and management of customer accounts, transactions, and authentication processes using **MySQL**.

This project demonstrates how a database can be designed and implemented to manage essential banking operations such as **account creation, deposits, withdrawals, and transaction tracking**.

---

## 🗂️ Project Structure
The project includes the following:
- `DBMS_ATM_PROJECT.sql` — The SQL script containing all database creation statements, table definitions, constraints, and sample data.
- Database schemas for:
  - **ATM** — Main database handling all ATM-related data.
  - **phpMyAdmin** — System-generated configuration tables for phpMyAdmin.
  - **Test** — Optional testing database created for validation and testing purposes.

---

## ⚙️ Technologies Used
- **Database:** MySQL / MariaDB  
- **Tool Used:** phpMyAdmin 5.2.1  
- **Server Version:** 10.4.32-MariaDB  
- **Language:** SQL  
- **Environment:** Localhost (XAMPP / WAMP)

---

## 🏗️ Database Design
The **ATM** database contains tables that manage:
- **User Accounts** – Customer details such as account number, balance, and authentication info.
- **Transactions** – Records of all deposit and withdrawal operations.
- **Security Management** – Ensures the protection of PINs and other sensitive data.
  
*(Note: Some phpMyAdmin internal tables may appear in the SQL dump but are not part of the actual ATM logic.)*

---

## 🚀 How to Use
1. **Open phpMyAdmin** from your local XAMPP/WAMP server.  
2. **Create a new database** named `atm`.  
3. **Import** the `DBMS_ATM_PROJECT.sql` file using the phpMyAdmin import option.  
4. Wait until the execution completes — all required tables and data will be created automatically.  
5. You can now **query the database** to perform operations such as:
   ```sql
   SELECT * FROM accounts;
   SELECT * FROM transactions;
