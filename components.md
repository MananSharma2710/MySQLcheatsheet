**DBMS Components**

1. **Data Model**:
   - Defines how data is structured and organized.
   - Examples: Hierarchical, Network, Relational, Object-Oriented.

2. **Data Definition Language (DDL)**:
   - Defines and manages database structure.
   - Create, modify, delete tables, indexes, constraints.
   - Specifies data integrity constraints (primary keys, foreign keys).

3. **Data Manipulation Language (DML)**:
   - Manages data within tables.
   - Insert, update, delete, query data.
   - SELECT retrieves data; INSERT adds records; UPDATE modifies records; DELETE removes records.
   

4. **Query Language**:
   - Used to interact with the database.
   - Executes queries to retrieve, modify, or manipulate data.
   - SQL (Structured Query Language) is a common query language.

5. **Database Administrator (DBA)**:
   - Manages and maintains the database system.
   - User management, security, handles installation, configuration, backups, and performance optimization.

6. **Users**:
   - End-users and applications interact with the database.
   - Can execute DML and query operations.
   - Different user types: administrators, developers, general users.

7. **Database Management System (DBMS)**:
   - Software that manages data.
   - Organizes, stores, retrieves, and maintains data.

8. **Schema**:
   - Defines database structure and constraints.
   - Logical schema (how data is viewed) and physical schema (how data is stored).

9. **Table**:
   - Basic unit for data storage.
   - Rows (records) and columns (attributes).

10. **Index**:
    - Data structure to improve data retrieval speed.
    - Facilitates quick access to rows based on indexed columns.

11. **Transaction**:
    - Sequence of operations treated as a single unit.
    - Follows ACID properties for data consistency.
    - ACID: Atomicity, Consistency, Isolation, Durability.

12. **Normalization**:
    - Process to reduce data redundancy and improve data integrity.
    - Organizes data into normal forms (1NF, 2NF, 3NF, etc.).

13. **Data Integrity**:
    - Ensures accuracy and consistency of data.
    - Entity integrity (unique identification) and referential integrity (relationships).

14. **Database Security**:
    - Protects data from unauthorized access or modification.
    - User authentication, authorization, encryption.

15. **Backup and Recovery**:
    - Regularly backs up data to prevent data loss.
    - Enables recovery from system failures.
    - Creates backups of data for disaster recovery.

16. **Concurrency Control**:
    - Manages simultaneous access to data by multiple users.
    - Ensures data consistency and avoids conflicts.
    - Prevents data inconsistencies in multi-user environments.

17. **Views**:
    - Virtual tables that provide a customized view of data.
    - Hides complex queries and sensitive information.

18. **Stored Procedures and Triggers**:
    - Predefined logic and actions.
    - Automates tasks or enforces business rules.

19. **Query Processor**:
    - Converts SQL queries into execution plans.
    - Optimizes query execution for performance.

20. **Database Engine**:
    - Executes database queries and transactions.
    - Manages memory, disk storage, and caching.

21. **Storage Management**:
    - Manages physical storage of data on disk.
    - Allocates space, handles file structures.

22. **Buffer Manager**:
    - Manages data in memory (buffers).
    - Caches frequently used data to improve performance.

23. **File Manager**:
    - Manages data storage and retrieval at the file level.
    - Reads and writes data to and from disk.

24. **Data Dictionary**:
    - Stores metadata about the database objects.
    - Information about tables, columns, constraints.

25. **Query Optimizer**:
    - Analyzes query execution plans.
    - Chooses the most efficient way to execute queries.

26. **Replication and Clustering**:
    - Replicates data across multiple servers for fault tolerance.
    - Clustering ensures high availability.