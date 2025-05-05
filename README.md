# WHERE-Clause
# 🏦 Bank Employee Database - SQL Project

This project demonstrates how to build a basic employee database for a banking system using SQL Server. It includes table creation, data insertion, alteration, and common query operations to retrieve and update data.

---

## 📁 Database Overview

**Database Name**: `BANKDB`

This project creates and manipulates three main tables:

- `Gender` - Stores gender options
- `Department` - Stores departments within the bank
- `Employee` - Stores employee details, linked with `Gender` and `Department`

---

## 📐 Tables Structure

### 🧑‍🤝‍🧑 Gender Table
| Column | Type         | Description         |
|--------|--------------|---------------------|
| ID     | INT (PK)     | Auto-increment ID   |
| GENDER | VARCHAR(20)  | Gender description  |

### 🏢 Department Table
| Column | Type         | Description         |
|--------|--------------|---------------------|
| ID     | INT (PK)     | Auto-increment ID   |
| NAME   | VARCHAR(50)  | Department name     |

### 👨‍💼 Employee Table
| Column       | Type         | Description                             |
|--------------|--------------|-----------------------------------------|
| ID           | INT (PK)     | Auto-increment ID                       |
| NAME         | VARCHAR(100) | Employee name                           |
| EMAILID      | VARCHAR(100) | Email address                           |
| GENDERID     | INT (FK)     | Linked to `Gender(ID)`                  |
| DEPARTMENTID | INT (FK)     | Linked to `Department(ID)`              |
| SALARY       | INT          | Salary in USD                           |
| CITY         | VARCHAR(30)  | City of residence                       |

---

## 🧩 Key Features

- Creation of normalized tables with primary and foreign keys
- Sample data population
- ALTER statement to add new column (`CITY`)
- SELECT queries to filter by city, gender, salary, and department
- UPDATE and DELETE operations

---

## 🧪 Sample Queries Included

- List employees by city
- Get male employees earning above $5,000
- Update salaries for payroll department
- Delete employees based in Dallas
- And more...

---

## 📂 Usage

1. Run the script in SQL Server Management Studio or any SQL execution environment.
2. Modify or extend the schema and data as needed for your application.

---

## 🛠️ Author

**Your Name**  
Feel free to contribute or suggest improvements
