# sql-customer-analysis
A portfolio project demonstrating complex SQL queries (JOINs, GROUP BY) to analyze the Chinook music store database with PostgreSQL.

# Customer Spending Analysis using SQL

## Project Summary

This project is an exploratory data analysis of the Chinook Music Store database. The primary goal is to practice and demonstrate proficiency in writing complex SQL queries to uncover business insights. By acting as a data analyst for the store, I have identified top customers, popular genres, and high-performing employees using PostgreSQL.

---

## Key Business Questions Answered

The analysis focuses on answering the following questions:

1.  **Who are the top 5 customers by total spending?**
2.  **What is the best-selling music genre in the USA?**
3.  **Which sales support agent is responsible for the most sales revenue?**

All queries used to answer these questions are available in the `analysis.sql` file.

---

## How to Use This Project

To reproduce this analysis, you will need to have PostgreSQL installed.

1.  **Create the Database:**
    ```bash
    createdb chinook
    ```

2.  **Load the Schema and Data:**
    ```bash
    psql -d chinook -f chinook_database.sql
    ```

3.  **Run the Analysis:**
    ```bash
    psql -d chinook -f analysis.sql
    ```

---

## Tech Stack

* **Language:** SQL
* **Database:** PostgreSQL
* **Environment:** Linux (WSL)
* **Version Control:** Git & GitHub
