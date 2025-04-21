# cmsc408 - sp2025 - Homework 8 - World Bank Indicator Analysis

This Homework focuses on writing and executing SQL queries to analyze data on countries, income groups and regions revealing global patterns in economic development

---

## Table of Contents

1. [Project Description](#project-description)  
2. [What to Learn](#what-to-learn)
3. [Motivation](#motivation)
4. [Technologies Used](#technologies-used)
5. [Project Structure](#project-structure)
6. [How to Run this Project](#how-to-run-this-project)  
7. [Sample Highlights](#sample-highlights)  
8. [Features](#features)  
9. [Credits](#credits)

---

## Project Description

Homework 8 was developed using World Bank datasets, it explores country-level indicators across income categories and geographical regions through SQL queries

The tasks range from basic SELECTs to advanced CTEs, subqueries, aggregation, and conditional pivots using `CASE`. The aim is to develop SQL by solving challenges based on real data

---

## What to Learn

- SQL fundamentals and advanced techniques  
- Using CASE statements for pivoting  
- Grouping, filtering and joining data  
- CTEs (Common Table Expressions)  
- Transforming data into insightful summaries  
- Performing cross tab and percentage analysis  

---

## Motivation

Understanding global development requires both data and the tools to analyze it and this homework helps building strong SQL skills while also revealing interesting points about income distribution and regional development globally

---

## Technologies Used

- **SQL** (MySQL-style dialect)  
- **Python** (for execution and visualization)  
- **Pandas** (used in the helper functions)  
- **Jupyter/Quarto Notebook (`.qmd`)**

---

## Project Structure

- `report.qmd` – The main project notebook with all 21 SQL tasks  
- Tasks include data exploration, income-group distribution, cross-tabulations, and advanced analysis using percentages and missing-data logic  

---

## How to Run This Project

1. Clone this repo (see GitHub URL inside the `.qmd` file)  
2. Install Python dependencies (`pandas`, `sqlalchemy`, etc.)  
3. Set up environment variables for DB credentials
4. Run `report.qmd` in Quarto or convert it to a Jupyter Notebook  

---

## Sample Highlights

- Cross tabulation (crosstab) of region vs income groups  
- Identifying missing income or region combinations  
- Percentage breakdowns of countries by income levels  
- Analysis on where the most lower income countries are concentrated  

---

## Features

- 21 fully executed and tested SQL queries  
- Pivot table construction with CASE  
- Percent of total insights  
- Use of nested queries and subqueries  
- Clean output formatting using helper functions  

---

## Credits

- Author: Nima Behboudi 
- Instructor: Dr. John Leonard
