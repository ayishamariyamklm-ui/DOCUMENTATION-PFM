# 📘 Personal Finance Manager – Complete Project Documentation

---

##  Project Description

The **Personal Finance Manager** is a Python-based command-line application designed to help users **record, manage, analyze, and visualize personal expenses**.

The project demonstrates real-world use of:
- Python programming fundamentals
- Object-Oriented Programming (OOP)
- File handling using CSV
- Input validation and error handling
- Modular project structure
- Data analysis and visualization using **Matplotlib**


---

##  Project Objectives

- Track daily expenses efficiently
- Store expense data persistently
- Generate meaningful summaries and reports
- Visualize spending patterns
- Follow clean and scalable coding practices

---

##  Technologies Used

- **Python 3.9+**
- **CSV module** (file persistence)
- **Matplotlib** (charts & visualization)
- **Datetime module** (date validation)
- **Unittest** (basic testing)

---

##  System Requirements

### Software
- Python 3.9 or above
- pip package manager
- Any IDE (VS Code recommended)

### Hardware
- Any standard computer/laptop
- Minimum 4GB RAM

---

##  Setup Instructions

### Step 1: Install Python
Download Python from:
https://www.python.org/downloads/


```bash
python --version

## 📂 Project Structure

Personal-Finance-Manager/
│
├── README.md
├── requirements.txt
├── main.py
├── Basics/
│ ├── basics.py
│ ├── python_basics.py
│ ├── python_numpy_pandas_basics.py
│
├── src/
│ ├── _init_.py
│ ├── expense.py
│ ├── file_manager.py
│ ├── menu.py
│ ├── reports.py
│ └── utils.py
│
├── data/
│ ├── expenses.csv
│ └── expenses_backup.csv
│
├── docs/
│ ├── documentation.md
│ └── user_guide.md
│
├── reports/
├── tests/
└── screenshots/


---
## File & Module Explanation

### main.py
Entry point of the application
Controls menu flow and user interaction
Connects all modules

### expense.py

Defines the Expense class
Stores amount, category, date, description
Formats expense display

### file_manager.py

Loads expenses from CSV
Saves expenses to CSV
Creates backup file

### menu.py

Displays CLI menus
Keeps UI logic separate from business logic

### reports.py

Category-wise summary
Monthly report
Search functionality
Matplotlib charts

### utils.py

Validates user inputs
Ensures data consistency
Provides pause utility for CLI

## Application Features
### Add New Expense

Validates amount, category, and date
Stores data persistently

### View All Expenses

Displays all stored expenses in readable format

### Category-wise Summary

Displays total expenses per category

### Monthly Report

Total expenses
Average expense
Number of records

### Search Expenses

Searches by category or description keyword

### Backup Data

Creates backup CSV file to prevent data loss

### Data Visualization (Matplotlib)

Category-wise bar chart
Monthly trend line chart

## Screenshots Section 

Screenshots provide visual proof of project functionality.
Place all screenshots inside the screenshots/ folder.

Screenshot Name	Description
main_menu.png	Main menu display
add_expense.png	Adding a new expense
view_expenses.png	Viewing all expenses
category_summary.png	Category summary output
monthly_report.png	Monthly report output
category_chart.png	Category-wise bar chart
monthly_trend.png	Monthly trend line chart


## Reports Folder Explanation

The reports/ folder contains generated output files, not code.


category_summary.txt
monthly_report.txt
category_expenses.png
monthly_trend.png


## Input Validation & Error Handling

Amount must be positive
Category must be predefined
Date must follow YYYY-MM-DD format
Handles empty files safely
Prevents application crashes

## Testing

Testing is implemented using Python’s built-in unittest.

### Tests Included

Expense class tests
Validation tests
File operations tests
Report execution tests
Matplotlib chart execution tests

### Run all tests using:

python -m unittest discover tests

## Future Enhancements

Budget planning per category
Export reports to Excel/PDF
GUI using Tkinter or Streamlit
Automated CI testing

## Conclusion

The Personal Finance Manager project demonstrates practical application of Python programming concepts with real-world relevance.
It follows clean coding practices and is suitable for academic evaluation, internships, and professional portfolios.

## Author

Ayisha Mariyam
Aspiring Data Analyst
