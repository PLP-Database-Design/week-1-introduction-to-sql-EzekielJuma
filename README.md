
Components of a DBMS (Database Management System)
A Database Management System (DBMS) is a software system designed to manage databases and provide an interface for users and applications to interact with the data. The primary components of a DBMS include:

DBMS Engine: The core component that is responsible for interacting with the database and managing data storage, retrieval, and update operations. It handles the data processing and ensures that queries and transactions are executed correctly.

Database Schema: Defines the logical structure of the database, including the tables, relationships, and constraints that are part of the database. It outlines how the data is organized.

Query Processor: The part of the DBMS that interprets and executes queries from users or applications. It processes SQL commands, optimizing them for performance.

Database Manager: Manages the physical storage of data, including indexing, and ensures efficient access and retrieval. It includes a storage manager that oversees data placement on storage devices.

Transaction Management: Ensures that database transactions are processed in a way that guarantees consistency, isolation, and durability (ACID properties). It handles the execution of multiple transactions and ensures that the database remains in a valid state.

Data Dictionary: Stores metadata about the structure of the database, such as table definitions, column types, and relationships between tables. It helps the DBMS know how the data is organized and provides essential information for query processing.

Security and Access Control: Manages user authentication and authorization, ensuring that only authorized users can access or modify certain data.

Backup and Recovery System: Manages the process of making regular backups of the database and ensures data can be restored in case of system failure or other issues.

What is a Relational Database? Give 4 Examples
A Relational Database is a type of database that stores data in tables, where each table is made up of rows (records) and columns (attributes). The data in different tables can be related through common attributes (keys). Relational databases use Structured Query Language (SQL) to manage and manipulate data.

Examples of relational databases:

MySQL
PostgreSQL
Oracle Database
Microsoft SQL Server
Three Classifications of SQL
SQL (Structured Query Language) can be classified into three main categories based on its functionality:

Data Definition Language (DDL):

Deals with the structure of the database, such as creating, altering, or deleting tables and databases.
Examples: CREATE, ALTER, DROP
Data Manipulation Language (DML):

Deals with the manipulation of data within the database, including inserting, updating, and deleting records.
Examples: SELECT, INSERT, UPDATE, DELETE
Data Control Language (DCL):

Deals with permissions and access control to the database.
Examples: GRANT, REVOKE
Difference Between a Primary Key and a Foreign Key
Primary Key:

A primary key is a column or a set of columns in a table that uniquely identifies each record in the table.
It cannot contain NULL values, and it ensures that each row in the table has a unique identifier.
Example: In a students table, a student_id could be the primary key.
Foreign Key:

A foreign key is a column (or set of columns) in one table that links to the primary key in another table, establishing a relationship between the two tables.
It may contain NULL values and is used to enforce referential integrity by ensuring that a value in one table corresponds to an existing value in another table.
Example: In a grades table, a student_id could be a foreign key that references the student_id in the students table.
What is an Entity-Relationship Diagram (ERD)?
An Entity-Relationship Diagram (ERD) is a graphical representation of the entities (objects) in a database and the relationships between them. It helps in designing the database structure. In an ERD:

Entities are represented by rectangles.
Attributes are represented by ovals.
Relationships between entities are represented by diamonds.
Primary keys are typically underlined.
ERDs are used in the database design process to visualize how entities interact with each other and to organize data logically.

Advantages of Relational Databases
Data Integrity: Enforces rules like primary keys, foreign keys, and constraints to maintain data accuracy and consistency.
Flexibility: Allows easy querying and modification of data using SQL.
Data Security: Provides robust security measures, including user authentication and access control.
Scalability: Can handle large amounts of data and users effectively, supporting growth.
Ease of Maintenance: With well-defined relationships and a structured approach, relational databases are easier to maintain and modify over time.
Transaction Support: Ensures ACID properties, providing reliable and consistent data processing, even in the case of system failures.
Four Types of Data Types Used to Store Data in Tables
Integer: Used to store whole numbers. Example: INT, SMALLINT
String: Used to store text or alphanumeric characters. Example: VARCHAR, CHAR
Date/Time: Used to store date and time information. Example: DATE, TIME, DATETIME
Decimal/Float: Used to store numbers with decimal points. Example: DECIMAL, FLOAT
Purpose of a Database Management System (DBMS)
The primary purpose of a DBMS is to provide an efficient, secure, and manageable way to store, retrieve, and manipulate data in a database. It ensures that data is organized logically and efficiently, supports multiple users and applications, and enforces rules for consistency and integrity. Additionally, a DBMS helps:

Protect data through security and access control.
Maintain data consistency through ACID properties in transactions.
Enable data sharing and collaboration.
Provide efficient query and reporting mechanisms.
