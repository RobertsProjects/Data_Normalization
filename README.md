# Data_Normalization
Data normalization and database system creation


In Part A, data normalization was performed, a fundamental database design process, to efficiently organize data and reduce redundancy. 
The original table, "BAGEL ORDER," was transformed into three normalized tables:

BAGEL ORDER: This table contains general order information such as order date, customer details, and delivery information.
BAGEL ORDER LINE ITEM: Details about each bagel ordered, including bagel quantity and related information, are stored in this table.
BAGEL: Information about the bagels themselves, such as bagel names, descriptions, and prices, is stored in this table.
The achieved normal forms were as follows:

First Normal Form (1NF): Initial structure.
Second Normal Form (2NF): Splitting into multiple tables to remove partial dependencies.
Third Normal Form (3NF): Further separation of customer information into a dedicated table.
This process is essential for improving data integrity, query efficiency, and maintainability.

In Part B, the transition to the implementation phase of database design was made:

Table Creation: The database tables were created based on the normalized structure.
Data Population: The tables were populated with data to simulate real-world scenarios.
Views: SQL views, which are virtual tables generated from the database, were created to simplify complex queries.
Indexes: SQL indexes were created to improve query performance by allowing faster data retrieval.
Simple Feature Workflow (SFW): This likely relates to creating workflows or processes within the database application.
SQL Queries: SQL code for various queries, including joins and other operations, was developed to extract specific information from the database.
Overall, this project combines the theoretical aspect of database normalization (Part A) with practical database design, implementation, and query development (Part B). 
This comprehensive approach ensures that data is well-organized, efficiently accessed, and ready for real-world applications.
