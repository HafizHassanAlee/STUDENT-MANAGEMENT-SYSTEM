# Student Management System

A Python-based Student Management System that stores and manages student records using a JSON file.

## Features

* Add, view, search, update, and delete student records.
* Validate student information such as age, gender, city, and GPA.
* Search and filter students using different criteria.

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/HafizHassanAlee/STUDENT-MANAGEMENT-SYSTEM.git
```

### 2. Open the project folder

```bash
cd STUDENT-MANAGEMENT-SYSTEM
```

### 3. Run the program

```bash
python main.py
```

The program uses `students.json` to store the student records.

## Project Files

```text
STUDENT-MANAGEMENT-SYSTEM/
│
├── main.py
├── students.json
└── README.md
```

* `main.py` — Main Python program.
* `students.json` — Sample/fake student data used by the program.
* `README.md` — Project documentation.

## JSON Version vs PostgreSQL Version

This version stores student records in a local `students.json` file, making it simple to run without installing or configuring a database server.

The PostgreSQL version stores student records in a PostgreSQL database and uses Python with `psycopg` to perform database operations.

The PostgreSQL version is available here:

[Student Management System using PostgreSQL](https://github.com/hassan-ali-228/Student-Management-System-using-SQL)

## Requirements

* Python 3.x
* No external Python packages are required for the JSON version.

## Sample Data

The `students.json` file contains only sample/fake student data for testing and demonstration purposes.
