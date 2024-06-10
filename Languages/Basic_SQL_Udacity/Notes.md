Video 1: SQL Introduction
- SQL has many uses in software development which we will learn; primarily focus on data analysis
- Good for people in marketing, operations, finance, and more
- Bulk of analyst/data scientist work happens in SQL

Video 2: The Parch & Posey Database
- This course uses data from Parch & Posey, a company that sells paper (fake)
- The company has 50 sales reps across the country in 4 regions; 
- Types of paper they sell includes regular, poster, and glossy;
- Their clients are large Fortune 500 companies that advertise using Google, Facebook, and Twitter
- Throughout course, we will be able to analyze which of their product lines are worst performing, and which advertising stream should the company be focused on

Video 3 (& Text): The Parch & Posey Database
- One way to store data is on spreadsheets
- When we need lots of spreadsheets to store data from different sources, we can visualize these using an ERD (Entity Relationship Diagram)...each spreadsheet is represented by a table; at the top is the title of
  the spreadsheet and below (in the diagram in the video) the column names are listed. SQL CAN USE THIS INFORMATION TO QUERY ACROSS ONE OR MULTIPLE TABLES.

Text: Map of SQL content
- Jobs that use SQL: https://www.zippia.com/advice/what-jobs-use-sql/ 
- Will learn: SQL Joins, SQL Basics, SQL Aggregations

Video 4: Why SQL
- A lot of the world's data is in databases, and these databases are most commonly accessed through SQL (Structured Query Language)
- Been around since 1970's
- Used to read, change, manipulate, analyze data
- Popular in analysis for a few reasons: 1) easy to learn/understand; 2) can access data directly (without everything needing to be in the same spreadsheet); 3) easy to audit and replicate; 4) can run queries on
  multiple tables at once...good for pivot table type of stuff (SUM, COUNT, MIN, MAX)...but excel maxes out at a million rows, while SQL allows for billions; 5) can ask more complex questions of data

Video 5: How Databases Store Data
- Similar to Excel, tables have rows and columns, but with databases, there is mandatory organization by column and each column must have a unique (and ideally descriptive) name
- In a database, all the data in a column must be of the same data type

Text: Types of Databases
- Many different types of SQL databsses for different purposes
- Popular ones are MySQL, Access, Oracle, Microsoft SQL Server, and Postgres
- We will use Postgres in the course which should mostly translate
- Article for differences: https://www.digitalocean.com/community/tutorials/sqlite-vs-mysql-vs-postgresql-a-comparison-of-relational-database-management-systems

Videos: Type of Statements