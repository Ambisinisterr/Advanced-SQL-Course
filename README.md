# Advanced-SQL-Course

I purchased the advanced SQL Course from Udemy to ensure I understand all the major concepts in SQL. I will document my progress through the course although it will mainly be document based.

The course will cover:
* Subqueries
* Window Functions
* Advanced Join Operations
* Set Operations
* Grouping Sets
* Schema Structures and Table Relationships 
* Transactions
* Table Inheritance and Partioning
* Views
* SQL Functions
* Stored Procedures
* Triggers

# Subqueries
Subqueries are a pretty reasonable starting point for any advanced SQL.

I have been heavily using subqueries in my Google Sheets work as a way to join multiple data sets. For example if I wanted to aggregate data from multiple sheets in google sheets I might write something along the lines of:

```=QUERY({QUERY(Sheet1A:E, "SELECT A where B > 0 AND E LIKE 'A%'"),QUERY(Sheet1A:E, "SELECT A where B > 0 AND E LIKE 'A%'");})```

While the above is a common aspect of my day to day work I am looking forward to seeing what more true SQL can offer in the form of CTE's and Recursive methods.
