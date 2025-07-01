>>Objective
------------
This task demonstrate the use of subqueries and nested queries in SQL within the context of a Library Management System.
This includes writing and executing subqueries in the SELECT, WHERE, and FROM clauses using scalar subqueries, correlated subqueries, and logical operators like IN, 
EXISTS, and NOT EXISTS.

>>Description
--------------
This project simulates a simple Library Management System with three primary tables: Members, Books, and Borrow. It uses realistic sample data to illustrate 
how SQL subqueries can solve complex querying tasks such as calculating the total books borrowed by a member, identifying members who borrowed specific categories
of books, and filtering data based on conditions across related tables.

The script demonstrates:
1. Scalar subqueries to compute values like total borrow count per member
2. Correlated subqueries for row-wise comparisons (e.g., borrow date vs. membership date)
3. Subqueries in WHERE to find specific patterns (e.g., members who borrowed programming books)
4. EXISTS/NOT EXISTS to filter based on borrow history
5. Subqueries in FROM to create temporary tables for advanced joins
