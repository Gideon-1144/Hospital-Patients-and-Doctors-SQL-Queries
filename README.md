# Hospital-Patients-and-Doctors-SQL-Queries

A set of SQL queries I wrote to practice joining tables and answering questions from hospital data. The data has two tables: one for doctors and one for patients.

## Tables

- **Doctors**: Doctor_ID, Doctor_Name, Specialization
- **Patients**: Patient_ID, Patient_Name, Doctor_ID, Length_of_Stay

The two tables are linked through `Doctor_ID`.

## Questions I answered

1. Show each patient's name along with their doctor's specialization.
2. Find all patients treated by doctors who specialize in Internal Medicine.
3. Work out the average length of stay for the patients each doctor treats.
4. Find the doctor who has treated the most patients.

## What I used

- `SELECT` and `WHERE` for pulling and filtering data
- `INNER JOIN` to combine the Patients and Doctors tables
- `GROUP BY` with `AVG()` and `COUNT()` for summaries
- `ORDER BY` and `TOP 1` to find the highest result

I wrote these in SQL Server, so `TOP 1` may need to change to `LIMIT 1` on MySQL or PostgreSQL.

## Preview

![SQL queries](images/sql-queries.png)

## Files

- `SQL_Assignment.sql`: all the queries, with a comment above each one explaining what it does

## What I learned

This project helped me get comfortable with joins and with grouping data correctly. The most common mistake I ran into was forgetting to include every non-aggregated column in the `GROUP BY`.

## Author

Gideon Adebayo
www.linkedin.com/in/gideon-adebayo-
