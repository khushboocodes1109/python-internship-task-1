# Task 1: Python Environment Setup & First Script 🐍

## 📌 Task Description
This task focuses on setting up a Python development environment and creating the first Python script. The aim is to understand Python installation, file execution, variables, user input/output, and basic IDE usage. It also helps in developing good coding practices such as commenting and readability.

---

## 🛠 Tools Used
- Python (Official CPython)
- Visual Studio Code (VS Code)
- Terminal / Command Prompt

---

## 📂 Files Included
- `hello_world.py`
- Screenshot of terminal output
- `README.md`

---

## 🧠 What This Task Covers
- Installing and verifying Python
- Creating and running a Python file
- Using variables instead of hardcoding values
- Taking user input using `input()`
- Printing output to the terminal
- Understanding program execution flow
- Writing readable code with comments

---

## 💻 Python Code
```python
# Task 1: Python Environment Setup & First Script

# Importing datetime module to get today's date
import datetime

# Taking user input
name = input("Enter your name: ")
role = input("Enter your internship role: ")

# Getting today's date
today_date = datetime.date.today()

# Printing the output
print("\n--- Internship Details ---")
print("Name:", name)
print("Role:", role)
print("Date:", today_date)
📸 Output
The program is executed using the terminal, and the output is displayed showing the entered name, internship role, and the current date.
