[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/dNK7xGxu)
# SPARK Academy 2026 | Mini Capstone Project

**Submission Deadline:** 20th March 2026 · 11:59 PM GMT+1  
**Submission Method:** Push all files to this GitHub Classroom repo before the deadline

---

## 📌 Project Title

> Hospital KPI Dashboard
> e.g. *Patient Records Management System*

---

## 👥 Team Name & Members

**Team Name:** Team Pearl AI

| Full Name | Task Carried Out |
|-----------|-----------------|
| Ayebare Vicky | Built the Hospital class and the Department class, and error handling |
| Namuhubembe Melisa Grace | Handled data cleaning and visualization |
| Mayinja Bob Williams | Reviwed the initial Department class and Hospital class |
| Matovu Steven Ziritwawula | Drafted the README file and the one-page report |
| Mudhasi Andrew | Reviewed the README file and the one-page report |

---

## 📖 What This Project Does

> Write 2–3 sentences here explaining:
> - The program displays the different department plus their corresponding KPIs: bed occupancy, average wait time, and scan utilization.
> - The program addresses the lack of data driven decision making in hospitals by enabling evidence-based allocation of resources across different hospital departments.
> - The hospital administrators and department heads would use this program.

---

## 🗂️ Repository Structure

```
├── data/
│   └── dataset.csv        # Dataset provided for this project
├── report/
│   └── report.pdf                # One-page project report (push PDF here)
├── main.py                       # Main program entry point (or main.ipynb)
├── README.md                     # This file
└── requirements.txt              # List of Python libraries used
```

---

## ⚙️ How to Run This Project

### 1. Clone the repository
```bash
git clone https://github.com/Pearl-Ug/mini_capstone_week_4
cd Mini-Capstone-2026-Pearl-Ug
```

### 2. Install required libraries
```bash
pip install -r requirements.txt
```

> If you don't have a `requirements.txt` yet, install manually:
> ```bash
> pip install pandas matplotlib seaborn
> ```

### 3. Run the program

**If using a Python script:**
```bash
python main.py
```

**If using a Jupyter Notebook:**
```bash
    explain
```

---

## 📦 Requirements

List all libraries your project uses. Add these to your `requirements.txt` file:

```
pandas
matplotlib
seaborn
```

> Add any additional libraries your team uses below these.

---
numpy

## 📊 Visualisations

> Briefly describe the 3 charts your project produces:
>
> 1. **Chart 1** — Bar Chart showing the average wait time(minutes) across all departments
> 2. **Chart 2** — Heat Map showing daily bed occupancy rate per department
> 3. **Chart 3** — Line Chart showing daily scan volume across all departments.

---

## 🧱 Classes & Functions

> Briefly list the classes and standalone functions in your project:
>
> **Classes:**
> - `Department` — It loads hospital data, lets the user select a preferred department, and retrieves data for that department.
> - `Hospital` — It calculates key performance indicators for the selected department from the Department class.
>
> **Standalone Functions:**
> - `Department.load_data()` — Loads hospital data and filters it to return one selected department's records.
> - `Hospital.calculate_kpis` — Calculates key performance indicators


---

## 📄 Report

The one-page PDF report is located in the `report/` folder.
It covers: project overview, technical summary, challenges faced, and team contributions.

---

## ⚠️ Academic Integrity

This project was built independently by our team.
We did not share code or collaborate with any other team assigned to the same project.

---

*SPARK Academy 2026 · Mini Capstone · Submitted via GitHub Classroom*
