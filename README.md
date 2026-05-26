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
