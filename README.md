# Employee Department Report

A simple Python program that reads employee information from a CSV file, counts the number of employees in each department, and generates a text report.

---

## Features

- Reads employee data from a CSV file
- Uses Python's built-in `csv` module
- Counts employees in each department
- Generates a text report (`report.txt`)
- Simple and easy to modify

---

## Project Structure

```
employee-department-report/
│
├── department_report.py   # Main Python script
├── employees.csv          # Input employee data
├── report.txt             # Generated report
├── .gitignore
└── README.md
```

---

## Requirements

- Python 3.x
- Linux (or any operating system with Python 3 installed)

---

## How to Run (Linux)

### 1. Clone the repository

```bash
git clone https://github.com/saimamustafa-520/employee-department-report.git
```

### 2. Navigate to the project directory

```bash
cd employee-department-report
```

### 3. (Optional) Make the script executable

```bash
chmod +x department_report.py
```

### 4. Run the program

Using Python:

```bash
python3 department_report.py
```

Or, if the script includes the shebang line (`#!/usr/bin/env python3`):

```bash
./department_report.py
```

---

## Input File

The program expects a file named `employees.csv` in the project directory.

Example:

```csv
Name,Department
John,Sales
Alice,IT
Bob,Sales
Emma,Human Resources
Michael,IT
```

---

## Output

The program generates a file named `report.txt`.

Example output:

```text
Human Resources:1
IT:2
Sales:2
```

---

## How It Works

1. Reads employee records from `employees.csv`.
2. Extracts the **Department** field from each record.
3. Counts the number of employees in each department.
4. Writes the department counts to `report.txt` in alphabetical order.

---

## Technologies Used

- Python 3
- CSV module
- Dictionaries
- File handling

---

## Author

**Saima Mustafa**

---

## License

This project is for educational purposes.
