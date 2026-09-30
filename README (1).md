# Student Grade Management System

A CLI-based Python application designed to process student academic performance, calculate averages, assign letter grades, and persist data across sessions using JSON.

## Features

- **Record Management**: Add, view, and delete student academic details.
- **Dynamic Grading System**: Automatically calculates percentage and assigns letter grades ($A+$, $A$, $B$, $C$, $D$, $F$).
- **Data Persistence**: Stores and retrieves student records locally via standard `JSON` format.
- **Input Validation**: Ensures system stability by validating numeric grades ($0 \le \text{grade} \le 100$) and menu choices.

---

## Prerequisites

- **Python Version**: `Python 3.7+`
- **Dependencies**: None (Uses Python Standard Library modules `json` and `os`)

---

## Setup & Execution Instructions

### 1. Clone the Repository
Clone this repository to your local machine:
```bash
git clone https://github.com/koppolu24bac10055/Student-grade-management-system.git
cd Student-grade-management-system
```

### 2. Run the Application
Execute the application directly from your command line / terminal:
```bash
python main.py
```
*(Use `python3 main.py` if your environment defaults to Python 2.x)*

---

## Project Structure

```text
Student-grade-management-system/
│
├── main.py              # Main source code containing application logic & CLI loop
├── grades.json          # Automatically generated JSON file for data storage
├── README.md            # Execution setup instructions and documentation
└── PROJECT_REPORT.md    # Structured project evaluation report
```

---

## Program Usage Overview

Upon running `main.py`, you will be presented with a text menu:

1. **Add New Student Record**: Prompts for Student ID, Name, subject count, subject names, and respective marks.
2. **View All Student Summary**: Displays a tabular overview of all recorded students, including their calculated averages and final assigned grades.
3. **View Detailed Student Report**: Input a specific Student ID to view their individual breakdown across all individual subjects.
4. **Delete Student Record**: Removes a student record permanently from storage.
5. **Exit**: Saves current state and terminates the application cleanly.