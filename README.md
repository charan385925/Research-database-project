![image](https://github.com/user-attachments/assets/db8e72cb-0b62-4ab3-b27f-0d2477ba1500)






# Research-database-project
# 🗂️ Research Projects Database

This project is a relational database schema designed to manage and track information about research projects, the employees involved, and the funding agencies. It provides a structured way to handle data related to multiple entities and their relationships.

## 📌 Key Features

- Store and manage **research project** details.
- Maintain a registry of **employees** and their salaries.
- Track **project assignments** of employees and their project managers.
- Record **funding agencies** supporting the projects.

## 🛠️ Database Tables

### 📋 `project` Table
Stores details about individual research projects.
- `Project_ID` (INT, Primary Key): Unique ID of the project
- `Name` (VARCHAR(100)): Name of the project
- `Duration` (INT): Duration of the project
- `Budget` (DECIMAL(12,2)): Budget allocated to the project

### 📋 `fundingagency` Table
Holds information about the agencies funding the projects.
- `Agency_ID` (INT, Primary Key): Unique ID of the agency
- `Name` (VARCHAR(100)): Name of the agency
- `Address` (VARCHAR(255)): Address of the agency

### 📋 `employee` Table
Stores employee records.
- `SSN` (INT, Primary Key): Social Security Number of the employee
- `Emp_Name` (VARCHAR(50)): Name of the employee
- `Salary` (DECIMAL(10,0)): Employee's salary

### 📋 `employee_project` Table
A many-to-many relationship table that maps employees to projects.
- `SSN` (INT, Foreign Key): References `employee.SSN`
- `Project_ID` (INT, Foreign Key): References `project.Project_ID`
- `Manager_SSN` (INT): SSN of the manager (possibly a foreign key to `employee`)

### 📋 `project_manager` Table
Specifies the manager responsible for each project.
- `Project_ID` (INT, Foreign Key): References `project.Project_ID`
- `Manager_SSN` (INT, Foreign Key): References `employee.SSN`

## 📦 How to Use

You can use this schema in any SQL-compatible database system. Simply create the tables using the provided structure, then populate them with your data.

## 📚 Use Cases

- University or institutional research management
- Budget tracking for funded projects


![ChatGPT Image Jun 13, 2025, 03_50_51 PM 1](https://github.com/user-attachments/assets/0560f0f8-98df-4bd7-8c34-9fd6ec11e459)

- Employee workload and assignment tracking

---

Feel free to fork this repository and adapt the schema to suit your specific needs.
