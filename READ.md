

![ChatGPT Image Jun 13, 2025, 03_54_15 PM](https://github.com/user-attachments/assets/3619227c-d44b-4308-8329-6b6ac2b80b0c)

# 🎓 University Management Database Project

This project is a relational database design for a **University Examination System**. It models real-world academic entities and relationships between departments, students, faculty members, courses, and exams using SQL.

## 📌 Project Overview

The goal is to design and implement an **Entity-Relationship (ER) schema** that efficiently captures the following:

- Departments with unique names and designated heads.
- Faculty members who can teach, coordinate, or head departments.
- Courses offered by departments and managed by faculty.
- Students enrolled in departments and taking multiple courses.
- Exams linked to courses, created and evaluated by faculty.
- Student performance records with support for multiple exam attempts.

## 🛠️ Features Implemented

- Normalized relational schema for managing academic data.
- Primary and foreign key constraints to maintain integrity.
- Tables:
  - `Department`
  - `Faculty`
  - `Course`
  - `Student`
  - `Exam`

- Sample SQL data for testing and demonstration.

## 📂 Database Tables

Each table reflects real-world entities:

- **Department**: Stores department info and head faculty.
- **Faculty**: Stores faculty identity and roles.
- **Course**: Stores course details offered by departments.
- **Student**: Stores student records and their departments.
- **Exam**: Stores exams conducted for each course, including student attempts.

## 🧪 Sample Data

Included sample `INSERT` statements to populate the schema with:
- Faculty members with designations.
- Departments with heads.
- Courses mapped to departments.
- Students in departments.
- Exams with details like type, date, subject, and duration.

## 📚 Technologies Used

- MySQL / SQL
- Relational Database Design Principles
- ER to Schema Conversion
![project 2 img](https://github.com/user-attachments/assets/80e6631b-19a3-4c44-845d-b0176344fd96)

---

👨‍🎓 *Project by a First-Year Student exploring database systems and academic data modeling.*

Feel free to explore, modify, or extend the schema as needed!
