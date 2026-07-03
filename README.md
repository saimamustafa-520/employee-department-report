# Employee Department Report

This project is a practice exercise completed as part of a Coursera Python course. It demonstrates how to read data from a CSV file, process it using Python, and generate a report summarizing the number of employees in each department.

## Features

* Reads employee data from a CSV file
* Uses Python's built-in `csv` module
* Counts employees in each department
* Generates a text report (`report.txt`)
* Demonstrates file handling, dictionaries, and CSV processing

## Project Structure

```text
employee-department-report/
│
├── department_report.py   # Main Python script
├── employees.csv          # Sample input data
├── report.txt             # Generated output
├── .gitignore
└── README.md
```

## Requirements

* Python 3.x

## How to Run (Linux)

1. Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/employee-department-report.git
```

2. Move into the project directory:

```bash
cd employee-department-report
```

3. Run the script:

```bash
python3 department_report.py
```

Or, if the script has execute permissions and includes a shebang (`#!/usr/bin/env python3`):

```bash
chmod +x department_report.py
./department_report.py
```

## Input

The program expects an `employees.csv` file in the project directory.

Example:

```csv
Name,Department
John,Sales
Alice,IT
Bob,Sales
Emma,Human Resources
Michael,IT
```

## Output

The program creates a file named `report.txt` containing the employee count for each department.

Example:

```text
Human Resources:1
IT:2
Sales:2
```

## How It Works

1. Reads employee records from `employees.csv`.
2. Extracts the `Department` field from each record.
3. Counts how many employees belong to each department.
4. Writes the results to `report.txt` in alphabetical order.

## Learning Objectives

This practice project demonstrates:

* Reading CSV files with `csv.DictReader`
* Processing data using Python dictionaries
* File input/output
* Functions and modular programming
* Basic data analysis using Python

## Acknowledgements

This project was completed as a practice exercise while following a Python course on Coursera. It is shared for learning and portfolio purposes.

## Author

**Saima Mustafa**
