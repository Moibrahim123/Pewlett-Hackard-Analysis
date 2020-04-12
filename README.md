# Pewlett-Hackard-Analysis

## Project Overview

In Pewlett-Hackard-Analysis, we learned about data modeling, engineering, and analysis. Applying our knowledge of DataFrames and tabular data, we created entity relationship diagrams (ERDs), import data into a database, troubleshot common errors, and created queries that use data to answer questions using SQL techniques.

## Objectives

-	Use an ERD to understand relationships between SQL tables.
-	Create new tables in pgAdmin by using different joins.
-	Write basic- to intermediate-level SQL statements.
-	Export new tables to a CSV file.


## Number of [titles] Retiring

We were instructed to create a new table using a RIGHT JOIN that contains Employee number, First and last name, Title, From_Date, and Salary. Then, export the data as a CSV. To create the new list of potential mentors, we created a query that returns a list of current employees eligible for retirement, as well as their most recent titles from my table there will be 41,380 retirees.


## Only the Most Recent Titles

Here, we were instructed to list the frequency count of employee titles in descending order. To get the final list with the recent titles, we partition the data so that each employee is only included on the list once. In addition, we performed a query that shows how many current employees of each title are presently eligible for retirement.


## Who’s Ready for a Mentor?

To find who's ready for a mentor, we created a new table. The birth date was set to be between January 1, 1965 and December 31, 1965. Also, we made sure only current employees were included in this list. The final query returns the potential mentor’s employee number, first and last name, their title, birth date and employment dates.
