Assignment Questions

1. State and Explain the components of a DBMS(Database Management System)

 **Database Engine**: Core service for storing and processing data.
 **Database Schema**: Structure defining data organization.
 **Query Processor**: Interprets and executes queries.
 **Transaction Management**: Ensures reliable processing of transactions (ACID properties).
 **Storage Management**: Manages data storage and retrieval.
 **DBA Tools**: Tools for administrators to manage and maintain the DBMS.
 **Data Dictionary**: Repository of metadata about data.
 **User Interfaces**: Interfaces for users to interact with the database.
 **Client-Server Architecture**: Structure where server handles data and clients handle user requests.


2. What is a relational database? Give 4 examples

A relational database stores data in structured tables with rows and columns, using SQL for management and querying.
### Examples:
 **MySQL**: Popular for web applications.
 **PostgreSQL**: Known for complex queries.
 **Microsoft SQL Server**: Widely used in enterprises.
 **Oracle Database**: Scalable and reliable for large operations.

3. State and Explain three classifications of SQL?

### 1. **Data Definition Language (DDL)**
   - **Commands**: `CREATE`, `ALTER`, `DROP`, `TRUNCATE`
   - **Purpose**: Defines and manages database structures.
### 2. **Data Manipulation Language (DML)**
   - **Commands**: `INSERT`, `UPDATE`, `DELETE`, `SELECT`
   - **Purpose**: Manipulates data in database tables.
### 3. **Data Control Language (DCL)**
   - **Commands**: `GRANT`, `REVOKE`
   - **Purpose**: Controls access to data.

4. What is the difference between a Primary Key and a Foreign Key?

**Primary Key:**
- **Purpose:** Uniquely identifies each record in a table.
- **Characteristics:** Must be unique, cannot be NULL.
- **Usage:** Ensures each row in a table is unique.
**Foreign Key:**
- **Purpose:** Establishes a relationship between two tables.
- **Characteristics:** Refers to the Primary Key in another table.
- **Usage:** Enforces referential integrity between tables.

5. What is an Entity-Relationship Diagram?

An Entity-Relationship Diagram (ERD) is a visual representation of a database's structure, showing entities and their relationships.
### Key Components:
 **Entities:** Objects or concepts (e.g., "Customer").
 **Attributes:** Properties of entities (e.g., "Customer Name").
 **Relationships:** Links between entities (e.g., "Customer places Order").
 **Primary Key:** Unique identifier for each entity.
 **Foreign Key:** Links entities by referencing the primary key of another entity.
ERDs help in designing and organizing databases.

6. What are the advantages of relational databases?

### Advantages of Relational Databases:
 **Data Integrity**: Ensures accuracy and consistency of data through constraints.
 **Flexibility**: Easy to update and modify data structures.
 **Scalability**: Handles large amounts of data efficiently.
 **Data Security**: Provides robust access control mechanisms.
 **Query Capability**: Powerful querying with SQL.
 **Normalization**: Reduces data redundancy.

7. State four types of data type used to store data in tables?

### Four Types of Data Types in Tables:

1. **Integer (INT)**
   - Stores whole numbers.
   - Example: `age INT`

2. **Character/String (VARCHAR, CHAR)**
   - Stores text.
   - Example: `name VARCHAR(255)`

3. **Date/Time (DATE, TIMESTAMP)**
   - Stores dates and times.
   - Example: `birthdate DATE`

4. **Boolean (BOOL)**
   - Stores true/false values.
   - Example: `is_active BOOL`

8. What is the purpose of a database management system (DBMS)?

### Purpose of a Database Management System (DBMS):

1. **Data Storage and Retrieval:** Efficiently stores and retrieves large amounts of data.
2. **Data Security:** Ensures data integrity and security through access controls.
3. **Data Management:** Simplifies data management with tools for organization and manipulation.
4. **Data Consistency:** Maintains data consistency and reduces redundancy through relational models.

A DBMS helps manage, organize, and secure data efficiently.
