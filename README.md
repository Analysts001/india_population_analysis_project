India Population Project

Overview

This project analyzes India’s state-wise population data using Python, SQL, and Tableau. It covers the complete data analysis workflow, including data storage, cleaning, analysis, and visualization.

Database: india_data
Table: state_data (20 columns including population, literacy rate, year, etc.)
Python Analysis: Jupyter Notebook (analysis.ipynb)
Tableau Dashboard: Interactive visualizations (dashboard.twbx)
Database
SQL file: sql/india_data.sql

This file can recreate the entire database (schema + data)

Key columns include:

state
population
literacy_rate
year
"total/population"
Python Analysis
Data cleaning, transformation, and aggregation performed in Jupyter Notebook

Python libraries used:

Pandas
NumPy
Matplotlib
Seaborn
Tableau Dashboard
Interactive dashboard created using Tableau

Visualizations include:

Population trends over time
State-wise comparisons
Literacy rate analysis
File: tableau/dashboard.twbx

How to Run
Import the database using:

sql/india_data.sql
Run the Jupyter Notebook:

analysis.ipynb
Open the Tableau dashboard file:

dashboard.twbx

Notes

PostgreSQL is used for database management
Column names follow lowercase and underscore formatting
The column "total/population" requires double quotes in SQL queries
Tools used: Python, SQL, Tableau, Jupyter Notebook, PostgreSQL
This project is ready for GitHub and portfolio showcase
