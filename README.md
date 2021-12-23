### -----------------------------------------------------------------------------------------------------
# Format SQL output into Pandas DataFrame using PostgreSQL
### -----------------------------------------------------------------------------------------------------
### SQL:
- stands for **Structured Query Language**
- **standardized programming language for Relational Database Management Systems** (RDBMS)
- used **to**:
    - **access, communicate with and manage** databases
    - **store, manipulate and retrieve data** in databases
- SQL **can do**:
    - **execute queries** against database
    - **retrieve data** from database
    - **insert records** in database
    - **update records** in database
    - **delete records** from database
    - **create new databases**
    - **create new tables** in database
    - **modify tables** in database
    - **create stored procedures** in database
    - **create views** in database
    - **set permissions** on tables, procedures, and views
- **types of** SQL **commands**:
    - **Data Manipulation Language (DML)** statements -> **retrieve and manipulate data** (SELECT, INSERT, UPDATE, DELETE)
    - **Data Definition Language (DDL)** statements -> **define and modify database structures** (CREATE, ALTER, DROP)
    - **Data Control Language (DCL)** statements -> **control database access and to create user roles and permissions** (GRANT, REVOKE)
- SQL **syntax**:
    - **actions performed on database** are done with **SQL statements**
    - SQL **keywords are NOT case sensitive**
    - some database systems require **semicolon at the end of each SQL statement**
- **standard** SQL **commands**:
    - **CREATE** - creates new table, view of table, or other object in database
    - **SELECT** - retrieve data from database
    - **INSERT** - inserts new data into database
    - **DELETE** - deletes data from database
    - **DROP** - deletes entire table, view of table or other objects in the database
    - **ALTER** - modifies existing database object

### PostgreSQL:
- **free and open-source Relational Database Management System** (RDBMS)
- **started** at **Berkeley Computer Science Department, University of California** and **developed by PostgreSQL Global Development Group**
- **supports** both **SQL (relational)** and **JSON (non-relational) querying**
- **available for** the following **operating systems**: **Linux** (all recent distributions), **macOS (OS X)**, **Windows**, and **Solaris**
- used as a **primary database for** many **web applications** as well as **mobile and analytics applications**
- **features**:
    - User-defined types
    - Table inheritance
    - Sophisticated locking mechanism
    - Foreign key referential integrity
    - Views, rules, subquery
    - Nested transactions (savepoints)
    - Multi-version concurrency control (MVCC)
    - Asynchronous replication


### -----------------------------------------------------------------------------------------------------
### Table of Contents:
1. File Descriptions
2. Technologies Used
3. Structure of Notebook
4. Executive Summary

#### 1. File Descriptions
- Format SQL output into Pandas DataFrame using Postgres.ipynb
- README.md

#### 2. Technologies Used
- Python
- MySQL
- Pandas

#### 3. Structure of Notebook
1. Import the Libraries
2. Create connection to Database
3. Execute SQL Query
4. Read Query
5. Show all Tables in Database
    5.1. Format SQL output into Pandas DataFrame
6. Show Columns in Table
    6.1. Format SQL output into Pandas DataFrame
7. Select (Read) Records
    7.1. Format SQL output into Pandas DataFrame
- SELECT DISTINCT statement
- WHERE clause
- COUNT function
- ORDER BY clause
- LIMIT clause
- BETWEEN operator
- IN operator
- LIKE operator
- GROUP BY clause
- HAVING clause
- AS command
- INNER JOIN clause
- FULL OUTER JOIN clause
- LEFT OUTER JOIN clause
- EXISTS operator

#### 4. Executive Summary
TBA
