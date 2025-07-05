# Skillovilla-Python-Project
Employee Data Analysis using Python &amp; Pandas
# Python Capstone Project – Employee Data Analysis

This project is built using **Python** and **Pandas** as part of a capstone assignment.  
It covers a full real-world data workflow including data cleaning, transformation, logic application, and reporting.

---

## 📁 Project Summary

This project simulates managing employee and project data, involving:

- Reading and merging multiple CSV files
- Handling missing values using **running average**
- Splitting and reorganizing columns (`Name → First Name + Last Name`)
- Applying conditional business logic:
  - **Promotions** based on age
  - **Demotions** for failed projects
  - **Bonus calculation** for finished work
- Aggregating total project cost per employee
- Filtering based on city name (`'o'` in it)

---

## 🛠️ Technologies Used

- Python 3
- Pandas
- Jupyter Notebook (for `.ipynb` file)
- CSV files

---

## 📄 Files Included

- `employee.csv`, `seniority.csv`, `project.csv`
- `project_filled.csv` – after handling missing cost
- `employee_updated.csv` – after name split
- `final_merged.csv`, `final_with_bonus.csv`, `final_promoted.csv`
- `total_project_cost.csv` – final report

---

## 🔥 Key Skills Demonstrated

- `merge()`, `groupby()`, `apply()`, `str.contains()`, `str.split()`
- Conditional logic using `if-else`
- File saving/loading using `.to_csv()` and `read_csv()`



