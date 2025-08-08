# Employee Management System (Python)

## 📌 Overview
This is a simple **Employee Management System** built in Python that allows you to:
- Add new employees
- View all employees
- Update employee details
- Delete employees
- Search employees by ID

All data is stored in a **CSV file** (`Employees.csv`) for persistence.

---

## 🚀 Features
1. **Add Employee**
   - Assigns an ID, name, position, salary, and email.
   - Validates salary (must be a number) and email (must contain `@` and `.`).
   
2. **View Employees**
   - Displays all employees in the system.

3. **Update Employee**
   - Update name, position, salary, or email.
   - Option to leave fields blank to keep existing values.

4. **Delete Employee**
   - Remove employee by their ID.

5. **Search Employee**
   - Look up an employee by ID.

6. **Persistent Storage**
   - Stores all employee data in a CSV file.

---

## 📂 File Structure
├── Employees.csv
├── employee_manager.py
└── README.md
---

## 🛠 Requirements
- Python 3.x
- No extra dependencies (uses built-in `csv` and `os` modules)

---

## 📖 Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/employee-manager.git
   cd employee-manager

