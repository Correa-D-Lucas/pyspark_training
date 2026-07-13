# PySpark Training

This repository contains exercises and practice materials for learning Apache Spark with Python (PySpark).

## Overview

This project focuses on hands-on practice with PySpark fundamentals, covering essential concepts such as:

- **Module 1: Data Loading & DataFrames**
  - Creating a SparkSession
  - Reading CSV files with various options (header, schema inference)
  - Reading multiple CSV files together
  - Creating DataFrames manually with custom data
  - Defining and inspecting schemas
  - Displaying and exploring data

- **Module 2: Data Selection & Filtering**
  - Selecting specific columns
  - Filtering data with comparison operators
  - Using AND/OR conditions
  - Using the `isin()` method for multi-value filtering
  - Sorting data in ascending and descending order

- **Module 3: Column Operations & Transformations**
  - Creating new columns with calculations
  - String manipulation (uppercase, lowercase, concatenate)
  - Date extraction (year, month)
  - Conditional logic with `when()`
  - Type casting
  - Dropping columns

- **Module 4: Aggregations & Grouping**
  - Calculating averages and sums by group
  - Counting records
  - Finding min/max values
  - Counting distinct values
  - Grouping by multiple columns
  - Ordering aggregated results
  - Filtering grouped results
  - Multiple aggregations in one query

- **Module 5: Joins**
  - Inner joins
  - Left joins
  - Right joins
  - Full outer joins
  - Anti joins
  - Semi joins
  - Joining multiple tables
  - Joining with multiple conditions
  - Removing duplicates after joins
  - Finding unmatched records

- **Module 6: Window Functions**
  - `row_number()` for sequential numbering
  - `rank()` for ranking with gaps
  - `dense_rank()` for ranking without gaps
  - Running totals
  - Moving averages
  - `lag()` to access previous rows
  - `lead()` to access next rows
  - Top N per group
  - First/last record by group

- **Module 7: Date & Time Operations**
  - Converting strings to dates
  - Extracting year, month, day
  - Calculating date differences
  - Adding days and months
  - Filtering by date range
  - Working with timestamps
  - Using `current_date()`

- **Module 8: Data Cleaning & Quality**
  - Detecting null values
  - Dropping null rows
  - Filling nulls and replacing missing values
  - Replacing null salary values with group averages
  - Removing duplicate records
  - Trimming whitespace
  - Replacing values
  - Regex-based replacements
  - Standardizing text
  - Detecting inconsistent rows

- **Module 9: Data Persistence & File Formats**
  - Writing DataFrames to CSV
  - Writing DataFrames to JSON
  - Writing DataFrames to Parquet
  - Writing partitioned Parquet files
  - Overwrite and append write modes
  - Compressing Parquet output
  - Saving selected columns only
  - Reading saved output back

- **Module 10: Performance & Caching**
  - Caching DataFrames
  - Persisting DataFrames
  - Using `explain()` to inspect query plans
  - Counting partitions
  - Measuring execution time

- **Module 11: Spark SQL & Temp Views**
  - Creating temporary views
  - Using `SELECT`, `WHERE`, `GROUP BY`, `HAVING`, and `ORDER BY`
  - Performing inner joins in SQL
  - Using window functions in SQL
  - Writing `CASE WHEN` expressions
  - Running subqueries
  - Using common table expressions (CTEs)
  - Counting distinct values

## Project Structure

```
.
├── datasets/              # Sample CSV datasets
│   ├── employees.csv
│   ├── sales.csv
│   ├── departments.csv
│   └── products.csv
├── exercises.ipynb        # Main Jupyter notebook with exercises
├── requirements.txt       # Python dependencies
└── README.md
```

## Getting Started

### Prerequisites

- Python 3.11+
- Apache Spark 4.1+
- Jupyter Notebook

### Installation

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Run the notebook:
```bash
jupyter notebook exercises.ipynb
```

## Datasets

The project includes sample datasets for practice:
- **employees.csv**: Employee information with salary and department details
- **sales.csv**: Sales transactions with amounts and dates
- **departments.csv**: Department information
- **products.csv**: Product catalog

## License

See LICENSE file for details.