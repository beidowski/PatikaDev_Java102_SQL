# Patika.dev Java 102 SQL Assignments

This repository contains SQL assignments completed during Patika.dev's Java 102 intermediate programming course, which includes a module on SQL. These assignments involve writing various queries and database operations on sample databases (e.g., dvdrental with tables like film, actor, customer).

The SQL exercises cover basic to advanced topics, including SELECT statements, filtering, aggregates, grouping, joins, subqueries, and database modifications. They demonstrate proficiency in database management using PostgreSQL or similar.

## Assignments Overview

Here's a list of the SQL assignments, along with brief descriptions:

- **hw1**: Basic SELECT queries, filtering by length, rental rate, and replacement cost on the film table.
- **hw2**: Queries using BETWEEN for ranges and IN for specific values, e.g., on film and actor tables.
- **hw3**: Advanced filtering and sorting, possibly with DISTINCT or aggregate functions.
- **hw4**: Queries involving string patterns (LIKE), ordering, and limits.
- **hw5**: LIKE queries for ending characters, ordering by length, and offsets.
- **hw6**: Aggregate functions like AVG, COUNT, MAX on columns like rental_rate.
- **hw7**: GROUP BY on rating or replacement_cost, with HAVING clauses for filtering groups.
- **hw8**: CREATE TABLE, INSERT data, DELETE rows, and UPDATE operations on a custom table.
- **hw9**: INNER JOIN queries between tables like actor and film_actor.
- **hw10**: LEFT JOIN and RIGHT JOIN examples, combining tables like customer and payment.
- **hw11**: UNION, INTERSECT, EXCEPT operations, and subqueries with ANY/ALL.
- **hw12**: Subqueries in WHERE clauses, finding records based on aggregates like COUNT or AVG.

These SQL scripts are typically executed on sample databases provided in the course.

## Getting Started

### Prerequisites
- PostgreSQL or a similar SQL database setup.
- Tools like pgAdmin, DBeaver, or psql for executing queries.

### Running an Assignment
1. Clone the repository: `git clone https://github.com/beida-ce/PatikaDev_Java102.git`
3. Set up a PostgreSQL database and import sample data (e.g., dvdrental database).
4. Navigate to the assignment folder: `cd hwX`
5. Use a SQL client to execute the queries in the .sql file.

Each assignment is self-contained in its folder with SQL scripts.

## Course Context
These assignments are from Patika.dev's Java 102 course, which builds on Java 101 by introducing advanced Java topics and integrating SQL for database interactions via JDBC.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Inspired by Patika.dev's curriculum and coding challenges.
- Thanks to the course instructors for guidance.

Feel free to fork, contribute, or use these as learning resources!
