📊 Task 3 — SQL for Data Analysis (Olist Customers Dataset)

This repository contains my complete solution for Task 3: SQL for Data Analysis, performed using SQLite and DB Browser for SQLite.
The objective of this task was to analyze structured data using SQL and practice essential querying skills such as filtering, grouping, joining (when applicable), subqueries, views, and indexing.

✅ Task Overview

Objective:
Use SQL queries to extract and analyze data from a dataset using SQLite.

Tools Used:

SQLite

DB Browser for SQLite

Olist Customers Dataset (olist_customers_dataset.csv)

Deliverables:

SQL queries in a .sql file

Screenshots of query results

Database file

PDF reports

📁 Repository Contents
.
├── Task3_SQL_queries.txt          # All SQL queries in plain text
├── Task3_SQL_Analysis.sql         # SQL file containing all executed queries
├── olist_task3.db                 # SQLite database created for the task
├── olist_customers_dataset.csv    # Dataset used for analysis
├── task3.pdf                      # Task 3 instructions/questions
└── task3_result.pdf               # Screenshots of outputs & results

🗂️ Dataset Used: olist_customers_dataset.csv

This dataset contains customer-level information from the Olist Brazilian E-commerce platform, including:

customer_id

customer_unique_id

customer_zip_code_prefix

customer_city

customer_state

This table was imported into SQLite and used as the basis for all SQL analysis.

🧠 What I Did

The following SQL concepts were applied:

✔ 1. Basic SQL Queries

SELECT

WHERE

ORDER BY

LIMIT

✔ 2. Aggregations

COUNT

AVG

MIN

MAX

GROUP BY

HAVING

✔ 3. Subqueries

Used to compare values against aggregated results (e.g., customers with zip prefix above the global average).

✔ 4. Views

Created views to simplify repeated analytical queries.

✔ 5. Indexing

Added indexes on columns frequently used in filtering to improve performance.

✔ 6. Data Exploration

Identified:

Most common customer states

Cities with highest customer counts

Duplicate customer_unique_id entries

Numeric patterns in zip code prefixes

Note: The customers dataset contains one main table, so JOIN operations were not applied. Full JOIN-based analysis is possible if additional Olist tables are included.

📝 SQL Query Files
📌 Task3_SQL_queries.txt

A clean text file containing every SQL query used during this task.

📌 Task3_SQL_Analysis.sql

Executable SQL script containing:

Table structure verification

Select queries

Grouped summaries

Aggregates

Subqueries

View creation

Index creation

Temporary table creation

You can import this file into any SQLite environment.

🖼️ Results & Screenshots

All final outputs (query results, view outputs, summary tables, and data analysis visuals) are included in:

👉 task3_result.pdf

This PDF contains:

Screenshots of executed queries

Output tables

Summary results

View outputs

Verification tables

🗄️ Database File
olist_task3.db

This SQLite database contains:

The imported Olist customers table

Indexes

Views

Temporary tables

Executed SQL changes

It can be opened directly using DB Browser for SQLite.

🚀 How I Completed the Task

Installed SQLite + DB Browser for SQLite

Created a new database olist_task3.db

Imported olist_customers_dataset.csv

Verified schema and data types

Wrote and executed SQL queries for:

Data exploration

Grouping & aggregation

Subqueries

View creation

Index optimization

Exported all queries to .sql and .txt files

Captured screenshots of outputs and compiled into task3_result.pdf

Organized repository with all deliverables

🎯 Learning Outcome

By completing this task, I strengthened my SQL skills in:

Understanding relational datasets

Data filtering

Aggregation and summarization

Writing clean and optimized SQL queries

Creating reusable views

Using indexes for performance

Analyzing real-world customer data

This task helped build a strong foundation for data analyst roles where SQL is essential.

🙌 Feel Free to Explore the Repository

You can:

Run the SQL queries

Open the database

Reproduce the results

Extend the analysis to other Olist tables

This repository is created as beginer for learning purpous only.
