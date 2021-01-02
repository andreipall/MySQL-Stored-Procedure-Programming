    I. Stored Programming Fundamentals
        1. Introduction to MySQL Stored Programs
            1.1. What Is a Stored Program?
                1.1.1. Why Use Stored Programs?
                1.1.2. A Brief History of MySQL
                1.1.3. MySQL Stored Procedures, Functions, and Triggers
            1.2. A Quick Tour
                1.2.1. Integration with SQL
                1.2.2. Control and Conditional Logic
                1.2.3. Stored Functions
                1.2.4. When Things Go Wrong
                1.2.5. Triggers
            1.3. Resources for Developers Using Stored Programs
                1.3.1. Books
                1.3.2. Internet Resources
            1.4. Some Words of Advice for Developers
                1.4.1. Don’t Be in Such a Hurry!
                1.4.2. Don’t Be Afraid to Ask for Help
                1.4.3. Take a Creative, Even Radical Approach
            1.5. Conclusion
        2. MySQL Stored Programming Tutorial
            2.1. What You Will Need
            2.2. Our First Stored Procedure
                2.2.1. Creating the Procedure
                2.2.2. Creating the Procedure Using the MySQL Query Browser
            2.3. Variables
            2.4. Parameters
                2.4.1. Parameter Modes
            2.5. Conditional Execution
            2.6. Loops
            2.7. Dealing with Errors
            2.8. Interacting with the Database
                2.8.1. SELECTing INTO Local Variables
                2.8.2. Using Cursors
                2.8.3. Returning Result Sets from Stored Procedures
                2.8.4. Embedding Non-SELECTs
            2.9. Calling Stored Programs from Stored Programs
            2.10. Putting It All Together
            2.11. Stored Functions
            2.12. Triggers
            2.13. Calling a Stored Procedure from PHP
            2.14. Conclusion
        3. Language Fundamentals
            3.1. Variables, Literals, Parameters, and Comments
                3.1.1. Variables
                3.1.2. Literals
                3.1.3. Rules for Variable Names
                3.1.4. Assigning Values to Variables
                3.1.5. Parameters
                3.1.6. User Variables
                3.1.7. Comments
            3.2. Operators
                3.2.1. Mathematical Operators
                3.2.2. Comparison Operators
                3.2.3. Logical Operators
                3.2.4. Bitwise Operators
            3.3. Expressions
            3.4. Built-in Functions
            3.5. Data Types
                3.5.1. String Data Types
                    3.5.1.1. The ENUM data type
                    3.5.1.2. The SET data type
                3.5.2. Numeric Data Types
                3.5.3. Date and Time Data Types
                3.5.4. TEXT and BLOB Data Types
            3.6. MySQL 5 “Strict” Mode
                3.6.1. Stored Program Behavior and Strict Mode
                3.6.2. Program Examples
            3.7. Conclusion
        4. Blocks, Conditional Statements, and Iterative Programming
            4.1. Block Structure of Stored Programs
                4.1.1. Structure of a Block
                4.1.2. Nested Blocks
            4.2. Conditional Control
                4.2.1. The IF Statement
                    4.2.1.1. TRUE or FALSE (or neither)?
                    4.2.1.2. Simple IF-THEN combinations
                    4.2.1.3. IF-THEN-ELSE statements
                    4.2.1.4. IF-THEN-ELSEIF-ELSE statements
                4.2.2. The CASE Statement
                    4.2.2.1. Simple CASE statement
                    4.2.2.2. “Searched” CASE statement
                4.2.3. IF Versus CASE
            4.3. Iterative Processing with Loops
                4.3.1. LOOP Statement
                4.3.2. LEAVE Statement
                4.3.3. ITERATE Statement
                4.3.4. REPEAT ... UNTIL Loop
                4.3.5. WHILE Loop
                4.3.6. Nested Loops
                4.3.7. Parting Comments on Loops
            4.4. Conclusion
        5. Using SQL in Stored Programming
            5.1. Using Non-SELECT SQL in Stored Programs
            5.2. Using SELECT Statements with an INTO Clause
            5.3. Creating and Using Cursors
                5.3.1. Defining a Cursor
                5.3.2. Cursor Statements
                5.3.3. Fetching a Single Row from a Cursor
                5.3.4. Fetching an Entire Result Set
                5.3.5. Types of Cursor Loops
                5.3.6. Nested Cursor Loops
                5.3.7. Exiting the Cursor Loop Prematurely
                5.3.8. Cursor Error Conditions
            5.4. Using Unbounded SELECT Statements
                5.4.1. Retrieving the Result Sets in the Calling Program
                5.4.2. Returning Result Sets to Another Stored Procedure
            5.5. Performing Dynamic SQL with Prepared Statements
            5.6. Handling SQL Errors: A Preview
            5.7. Conclusion
        6. Error Handling
            6.1. Introduction to Error Handling
                6.1.1. A Simple First Example
                6.1.2. Handling Last Row Conditions
            6.2. Condition Handlers
                6.2.1. Types of Handlers
                6.2.2. Handler Conditions
                6.2.3. Handler Examples
                6.2.4. Handler Precedence
                6.2.5. Scope of Condition Handlers
            6.3. Named Conditions
            6.4. Missing SQL:2003 Features
                6.4.1. Directly Accessing SQLCODE or SQLSTATE
                6.4.2. Creating Your Own Exceptions with the SIGNAL Statement
                6.4.3. Emulating the SIGNAL Statement
            6.5. Putting It All Together
            6.6. Handling Stored Program Errors in the Calling Application
                6.6.1. PHP
                6.6.2. Perl
                6.6.3. Java/JDBC
                6.6.4. Python
                6.6.5. C# .NET
                6.6.6. Visual Basic .NET
            6.7. Conclusion
    II. Stored Program Construction
        7. Creating and Maintaining Stored Programs
            7.1. Creating Stored Programs
                7.1.1. Editing Stored Programs Using a System Editor
                7.1.2. Using the MySQL Query Browser
                7.1.3. Using Third-Party Tools
                7.1.4. Handling Semicolons in Stored Program Code
            7.2. Editing an Existing Stored Program
                7.2.1. Editing a Program in Place
                7.2.2. Maintaining Stored Programs in External Files
            7.3. SQL Statements for Managing Stored Programs
                7.3.1. CREATE PROCEDURE
                7.3.2. CREATE FUNCTION
                7.3.3. CREATE TRIGGER
                7.3.4. ALTER PROCEDURE/FUNCTION
                7.3.5. DROP PROCEDURE/FUNCTION/TRIGGER
            7.4. Getting Information About Stored Programs
                7.4.1. SHOW PROCEDURE/FUNCTION STATUS
                7.4.2. SHOW CREATE PROCEDURE/FUNCTION
                7.4.3. INFORMATION_SCHEMA.ROUTINES Table
                7.4.4. INFORMATION_SCHEMA.TRIGGERS Table
            7.5. Conclusion
        8. Transaction Management
            8.1. Transactional Support in MySQL
                8.1.1. Isolation Levels
                8.1.2. Transaction Management Statements
            8.2. Defining a Transaction
            8.3. Working with Savepoints
            8.4. Transactions and Locks
                8.4.1. Situations in Which Locks Arise
                8.4.2. Deadlocks
                8.4.3. Lock Timeouts
                8.4.4. Optimistic and Pessimistic Locking Strategies
                    8.4.4.1. Pessimistic locking strategy
                    8.4.4.2. Optimistic locking strategy
                    8.4.4.3. Choosing between strategies
            8.5. Transaction Design Guidelines
            8.6. Conclusion
        9. MySQL Built-in Functions
            9.1. String Functions
                9.1.1. ASCII
                9.1.2. CHAR
                9.1.3. CHARSET
                9.1.4. CONCAT
                9.1.5. CONCAT_WS
                9.1.6. INSERT
                9.1.7. INSTR
                9.1.8. LCASE
                9.1.9. LEFT
                9.1.10. LENGTH
                9.1.11. LOAD_FILE
                9.1.12. LOCATE
                9.1.13. LPAD
                9.1.14. LTRIM
                9.1.15. REPEAT
                9.1.16. REPLACE
                9.1.17. RPAD
                9.1.18. RTRIM
                9.1.19. STRCMP
                9.1.20. SUBSTRING
                9.1.21. TRIM
                9.1.22. UCASE
                9.1.23. Other String Functions
            9.2. Numeric Functions
                9.2.1. ABS
                9.2.2. BIN
                9.2.3. CEILING
                9.2.4. CONV
                9.2.5. FLOOR
                9.2.6. FORMAT
                9.2.7. HEX
                9.2.8. LEAST
                9.2.9. MOD
                9.2.10. POWER
                9.2.11. RAND
                9.2.12. ROUND
                9.2.13. SIGN
                9.2.14. SQRT
                9.2.15. Other Numeric Functions
            9.3. Date and Time Functions
                9.3.1. ADDTIME
                9.3.2. CONVERT_TZ
                9.3.3. CURRENT_DATE
                9.3.4. CURRENT_TIME
                9.3.5. CURRENT_TIMESTAMP
                9.3.6. DATE
                9.3.7. DATE_ADD
                9.3.8. DATE_FORMAT
                9.3.9. DATE_SUB
                9.3.10. DATEDIFF
                9.3.11. DAY
                9.3.12. DAYNAME
                9.3.13. DAYOFWEEK
                9.3.14. DAYOFYEAR
                9.3.15. EXTRACT
                9.3.16. GET_FORMAT
                9.3.17. MAKEDATE
                9.3.18. MAKETIME
                9.3.19. MONTHNAME
                9.3.20. NOW
                9.3.21. SEC_TO_TIME
                9.3.22. STR_TO_DATE
                9.3.23. TIME_TO_SEC
                9.3.24. TIMEDIFF
                9.3.25. TIMESTAMP
                9.3.26. TIMESTAMPADD
                9.3.27. TIMESTAMPDIFF
                9.3.28. WEEK
                9.3.29. WEEKDAY
                9.3.30. YEAR
                9.3.31. YEARWEEK
                9.3.32. Other Date and Time Functions
            9.4. Other Functions
                9.4.1. BENCHMARK
                9.4.2. COALESCE
                9.4.3. CURRENT_USER
                9.4.4. DATABASE
                9.4.5. GET_LOCK
                9.4.6. IFNULL
                9.4.7. INTERVAL
                9.4.8. IS_FREE_LOCK
                9.4.9. ISNULL
                9.4.10. NULLIF
                9.4.11. RELEASE_LOCK
                9.4.12. SESSION_USER
                9.4.13. SYSTEM_USER
                9.4.14. USER
                9.4.15. UUID
                9.4.16. VERSION
            9.5. Conclusion
        10. Stored Functions
            10.1. Creating Stored Functions
                10.1.1. The RETURN Statement
                10.1.2. Parameters to Stored Functions
                10.1.3. The DETERMINISTIC and SQL Clauses
            10.2. SQL Statements in Stored Functions
            10.3. Calling Stored Functions
            10.4. Using Stored Functions in SQL
                10.4.1. Using SQL in Stored Functions
            10.5. Conclusion
        11. Triggers
            11.1. Creating Triggers
                11.1.1. Referring to Column Values Within the Trigger
                11.1.2. Triggering Actions
                11.1.3. BEFORE and AFTER Triggers
            11.2. Using Triggers
                11.2.1. Maintaining Derived Data
                11.2.2. Implementing Logging
                11.2.3. Validating Data with Triggers
            11.3. Trigger Overhead
            11.4. Conclusion
    III. Using MySQL Stored Programs in Applications
        12. Using MySQL Stored Programs in Applications
            12.1. The Pros and Cons of Stored Programs in Modern Applications
            12.2. Advantages of Stored Programs
                12.2.1. They Enhance Database Security
                12.2.2. They Provide a Mechanism for Data Abstraction
                12.2.3. They Reduce Network Traffic
                12.2.4. They Allow for Common Routines Across Multiple Application Types
                12.2.5. They Facilitate Division of Duties
                12.2.6. They May Provide Portability
            12.3. Disadvantages of Stored Programs
                12.3.1. They Can Be Computationally Inferior
                12.3.2. They Can Lead to Logic Fragmentation
                12.3.3. They Do Not Provide Portability
            12.4. Calling Stored Programs from Application Code
                12.4.1. Preparing a Stored Program Call for Execution
                12.4.2. Registering Parameters
                12.4.3. Setting Output Parameters
                12.4.4. Executing the Stored Program
                12.4.5. Retrieving Result Sets
                12.4.6. Retrieving Output Parameters
                12.4.7. Closing or Re-Executing the Stored Program
                12.4.8. Calling Stored Functions
            12.5. Conclusion
        13. Using MySQL Stored Programs with PHP
            13.1. Options for Using MySQL with PHP
            13.2. Using PHP with the mysqli Extension
                13.2.1. Enabling the mysqli Extension
                13.2.2. Connecting to MySQL
                13.2.3. Checking for Errors
                13.2.4. Executing a Simple Non-SELECT Statement
                13.2.5. Retrieving a Result Set
                13.2.6. Managing Transactions
                13.2.7. Using Prepared Statements
                13.2.8. Retrieving Result Sets from Prepared Statements
                13.2.9. Getting Result Set Metadata
                13.2.10. Processing a Dynamic Result Set
                13.2.11. Calling Stored Programs with mysqli
                13.2.12. Handling Output Parameters
                13.2.13. Retrieving Multiple Result Sets
            13.3. Using MySQL with PHP Data Objects
                13.3.1. Connecting to MySQL
                13.3.2. Executing a Simple Non-SELECT Statement
                13.3.3. Catching Errors
                13.3.4. Managing Transactions
                13.3.5. Issuing a One-Off Query
                13.3.6. Using Prepared Statements
                13.3.7. Binding Parameters to a Prepared Statement
                13.3.8. Getting Result Set Metadata
                13.3.9. Processing a Dynamic Result Set
                13.3.10. Calling Stored Programs with PDO
                13.3.11. Binding Input Parameters to Stored Programs
                13.3.12. Handling Multiple Result Sets
                13.3.13. Handling Output Parameters
                13.3.14. A Complete Example
            13.4. Conclusion
        14. Using MySQL Stored Programs with Java
            14.1. Review of JDBC Basics
                14.1.1. Installing the Driver and Configuring Your IDE
                14.1.2. Registering the Driver and Connecting to MySQL
                14.1.3. Issuing a Non-SELECT Statement
                14.1.4. Issuing a SELECT and Retrieving a Result Set
                14.1.5. Getting Result Set Metadata
                14.1.6. Using Prepared Statements
                14.1.7. Handling Transactions
                14.1.8. Handling Errors
            14.2. Using Stored Programs in JDBC
                14.2.1. Using the CallableStatement Interface
                14.2.2. Registering OUT Variables
                14.2.3. Supplying Input Parameters
                14.2.4. Executing the Procedure
                14.2.5. Retrieving a Result Set
                14.2.6. Retrieving Multiple Result Sets
                14.2.7. Dynamically Processing Result Sets
                14.2.8. Retrieving Output Parameter Values
            14.3. Stored Programs and J2EE Applications
                14.3.1. Using Stored Programs Within Java Servlets
                14.3.2. Using Stored Programs from EJB
            14.4. Using Stored Procedures with Hibernate
                14.4.1. Hibernate Support for MySQL Stored Procedures
                14.4.2. Using a Stored Procedure to Load an Object
                14.4.3. Hibernate Queries
                14.4.4. Using Stored Procedures for Persistence
            14.5. Using Stored Procedures with Spring
            14.6. Conclusion
        15. Using MySQL Stored Programs with Perl
            15.1. Review of Perl DBD::mysql Basics
                15.1.1. Installing DBD::mysql
                    15.1.1.1. Installing DBD::mysql on Linux or Unix
                    15.1.1.2. Installing DBD::mysql on Windows
                15.1.2. Connecting to MySQL
                    15.1.2.1. Connection attributes
                15.1.3. Handling Errors
                15.1.4. Issuing a Simple One-off Statement
                15.1.5. Preparing a Statement for Reuse
                15.1.6. Using Bind Variables
                15.1.7. Issuing a Query and Retrieving Results
                15.1.8. There’s More Than One Way To Do It
                    15.1.8.1. fetchrow_arrayref method
                    15.1.8.2. fetchrow_hashref method
                    15.1.8.3. fetchall_arrayref method
                    15.1.8.4. dump_results method
                    15.1.8.5. bind_col and fetch methods
                15.1.9. Getting Result Set Metadata
                15.1.10. Performing Transaction Management
            15.2. Executing Stored Programs with DBD::mysql
                15.2.1. Handling Multiple Result Sets
                15.2.2. Handling Dynamic Result Sets
                15.2.3. Handling Output Variables
                15.2.4. A Complete Example
            15.3. Conclusion
        16. Using MySQL Stored Programs with Python
            16.1. Installing the MySQLdb Extension
            16.2. MySQLdb Basics
                16.2.1. Creating a Connection
                16.2.2. Handling Exceptions
                16.2.3. Executing a Simple Statement
                16.2.4. Passing Parameters to a Statement
                16.2.5. Retrieving Rows from a Query
                16.2.6. Managing Transactions
                16.2.7. Getting Metadata
                16.2.8. Dynamically Processing a Result Set
            16.3. Using Stored Programs with MySQLdb
                16.3.1. Calling Simple Stored Programs
                16.3.2. Retrieving a Single Stored Program Result Set
                16.3.3. Retrieving Multiple Stored Program Result Sets
                16.3.4. Retrieving Dynamic Result Sets
                16.3.5. Obtaining Output Parameters
            16.4. A Complete Example
            16.5. Conclusion
        17. Using MySQL Stored Programs with .NET
            17.1. Review of ADO.NET Basics
                17.1.1. Installing the Connector/Net Driver and Configuring Your IDE
                17.1.2. Registering the Driver and Connecting to MySQL
                17.1.3. Issuing a Non-SELECT Statement
                17.1.4. Reusing a Statement Object
                17.1.5. Using Parameters
                17.1.6. Issuing a SELECT and Using a DataReader
                17.1.7. Getting DataReader Metadata
                17.1.8. DataSets
                17.1.9. Handling Errors
                17.1.10. Managing Transactions
            17.2. Using Stored Programs in ADO.NET
                17.2.1. Calling a Simple Stored Procedure
                17.2.2. Supplying Input Parameters
                17.2.3. Using a DataReader with a Stored Program
                17.2.4. Processing Multiple Result Sets in a DataReader
                17.2.5. Dynamically Processing Result Sets
                17.2.6. Using DataSets with Stored Programs
                17.2.7. Retrieving Output Parameters
                17.2.8. Calling Stored Functions
            17.3. Using Stored Programs in ASP.NET
            17.4. Conclusion
    IV. Optimizing Stored Programs
        18. Stored Program Security
            18.1. Permissions Required for Stored Programs
                18.1.1. Granting Privileges to Create a Stored Program
                18.1.2. Granting Privileges to Modify a Stored Program
                18.1.3. Granting Privileges to Execute a Stored Program
            18.2. Execution Mode Options for Stored Programs
                18.2.1. The SQL SECURITY Clause
                18.2.2. Using Definer Rights to Implement Security Policies
                18.2.3. Stored Program or View?
                18.2.4. Handling Invoker Rights Errors
            18.3. Stored Programs and Code Injection
                18.3.1. Protecting Against SQL Injection with Stored Programs
                18.3.2. SQL Injection in Stored Programs
            18.4. Conclusion
        19. Tuning Stored Programs and Their SQL
            19.1. Why SQL Tuning Is So Important
                19.1.1. An Instructive Example
            19.2. How MySQL Processes SQL
                19.2.1. Parsing SQL
                19.2.2. Caching
                    19.2.2.1. Buffer pool and key cache
                    19.2.2.2. Table cache
                    19.2.2.3. Query cache
                    19.2.2.4. Table statistics
            19.3. SQL Tuning Statements and Practices
                19.3.1. EXPLAIN Statement
                19.3.2. EXPLAIN and Stored Programs
                19.3.3. Details of the EXPLAIN Output
                19.3.4. Extended EXPLAIN
                19.3.5. Optimizer Hints
                19.3.6. Measuring SQL and Stored Program Execution
                19.3.7. The Slow Query Log
            19.4. About the Upcoming Examples
            19.5. Conclusion
        20. Basic SQL Tuning
            20.1. Tuning Table Access
                20.1.1. Index Lookup Versus Full Table Scan
                20.1.2. How MySQL Chooses Between Indexes
                20.1.3. Manually Choosing an Index
                20.1.4. Prefixed (“Partial”) Indexes
                20.1.5. Concatenated Indexes
                    20.1.5.1. Merging multiple indexes
                    20.1.5.2. Covering indexes
                20.1.6. Comparing the Different Indexing Approaches
                20.1.7. Avoiding Accidental Table Scans
                    20.1.7.1. Accidentally suppressing an index using a function
                    20.1.7.2. Accidentally suppressing an index using a substring
                    20.1.7.3. Creating concatenated indexes with a poor column order
                20.1.8. Optimizing Necessary Table Scans
                20.1.9. Using Merge or Partitioned Tables
            20.2. Tuning Joins
                20.2.1. How MySQL Joins Tables
                20.2.2. Joins Without Indexes
                20.2.3. Joins with Indexes
                20.2.4. Join Order
                20.2.5. A Simple Join Example
            20.3. Conclusion
        21. Advanced SQL Tuning
            21.1. Tuning Subqueries
                21.1.1. Optimizing Subqueries
                21.1.2. Rewriting a Subquery as a Join
                21.1.3. Using Subqueries in Complex Joins
            21.2. Tuning “Anti-Joins” Using Subqueries
                21.2.1. Optimizing an Anti-Join
            21.3. Tuning Subqueries in the FROM Clause
                21.3.1. Using Views
            21.4. Tuning ORDER and GROUP BY
                21.4.1. Creating an Index to Avoid a Sort
                21.4.2. Reducing Sort Overhead by Increasing Sort Memory
            21.5. Tuning DML (INSERT, UPDATE, DELETE)
                21.5.1. Batching Inserts
                21.5.2. Optimizing DML by Reducing Commit Frequency
                21.5.3. Triggers and DML Performance
            21.6. Conclusion
        22. Optimizing Stored Program Code
            22.1. Performance Characteristics of Stored Programs
            22.2. How Fast Is the Stored Program Language?
            22.3. Reducing Network Traffic with Stored Programs
            22.4. Stored Programs as an Alternative to Expensive SQL
                22.4.1. Avoid Self-Joins with Procedural Logic
                22.4.2. Optimize Correlated Updates
            22.5. Optimizing Loops
                22.5.1. Move Unnecessary Statements Out of a Loop
                22.5.2. Use LEAVE or CONTINUE to Avoid Needless Processing
            22.6. IF and CASE Statements
                22.6.1. Test for the Most Likely Conditions First
                22.6.2. Avoid Unnecessary Comparisons
                22.6.3. CASE Versus IF
            22.7. Recursion
            22.8. Cursors
            22.9. Trigger Overhead
            22.10. Conclusion
        23. Best Practices in MySQL Stored Program Development
            23.1. The Development Process
            23.2. Coding Style and Conventions
            23.3. Variables
            23.4. Conditional Logic
            23.5. Loop Processing
            23.6. Exception Handling
            23.7. SQL in Stored Programs
            23.8. Dynamic SQL
            23.9. Program Construction
            23.10. Performance
            23.11. Conclusion
