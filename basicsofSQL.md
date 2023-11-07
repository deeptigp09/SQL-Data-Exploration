# Basics of SQL

A **Database** is a collection of related information, for example, a phone book, to-do list, or even a Facebook's userbase.

Data can be stored in different ways:

- on paper
- in your mind
- on a computer
- in the comments section of a post

When you combine computer + Database = ❤️ Amazon.com is a great example of this.

**DBMS** - Database Management System

This is a special software that allows users to create and maintain a database. It can:

- Easily manage large amounts of data
- Handle security
- Perform backups
- Import and export data
- Manage concurrency
- Interact with software applications (programming languages)

**Types of Databases:**

1. **Relational Database**
   - Organize data into one or more tables
   - Each table has columns and rows
   - A unique key is used to identify each row

2. **Non-Relational Database**
   - Organize data into anything but a traditional table
   - Data is stored as key-value pairs
   - Supports documents (JSON files), graphs, and flexible tables

**RDBMS** - Create and maintain a Relational Database Management System like MySQL, Oracle, PostgreSQL, MariaDB, etc.

**SQL** - It is a standardized language for interacting with RDBMS. SQL is used to:

- Define tables and structures
- Perform CRUD operations: Create, Read (Select), Update, Delete

**Non-Relational DBMS** - Helps create and maintain non-relational DBMS like MongoDB, Dynamo DB, Apache Cassandra, Firebase, etc.

**NoSQL** - Implementation-specific

---
Important terms: 
- **Row** - Individual Entry
- **Column** - Single Attribute
- **Primary Key** - An attribute that uniquely defines the row in the database
- **Surrogate Key** - No mapping in the real world
- **Natural Key** - Something like a social security number
- **Foreign Key** - A link to another database table (primary key of another table); one table can have multiple foreign keys
- **Composite Key** - A key that needs two attributes together to identify uniquely in the table

**SQL** - A hybrid language

**DQL (Data Query Language)**
- Used to query the database for information
- Retrieve existing information

**DDL (Data Definition Language)**
- Used for defining schema

**DCL (Data Control Language)**
- Used for controlling access to the database
- Manage users and permissions

**DML (Data Manipulation Language)**
- Used for inserting, updating, and deleting data from the database

**Query**
- A query is a set of instructions given to the RDBMS that tells the RDBMS what information you want it to retrieve for you.
