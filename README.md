# 🧪 Research Projects Database

This project is a SQL-based **Research Projects Database System** designed using the **Entity-Relationship (ER) model**. It captures essential data and relationships between research projects, employees, and funding agencies.

## 📌 Description

The database models a real-world scenario where:

- Research **projects** are conducted under **employees**.
- Each **project** has:
  - A unique name (within a funding agency),
  - A **manager** (who is also an employee),
  - A **budget**, **duration**, and a **funding agency**.
- Each **employee** has:
  - A unique **SSN**,
  - Name and salary details.
- Employees can **work on multiple projects**, and each **project** can have multiple employees.
- A **project manager** is one of the employees.
- Each project is funded by **only one agency**, and agencies have a **name and address**.

## 🧾 SQL Tables Included

1. **Employee** – Stores employee details.
2. **FundingAgency** – Stores agency names and addresses.
3. **Project** – Stores project information (name, duration, budget).
4. **Employee_Project** – A junction table linking employees to projects, along with the manager SSN.
5. **Project_Manager** – Links each project to a single manager.

## 📂 Sample Data

Sample `INSERT` queries are provided to populate:

- 3 Employees
- 3 Funding Agencies
- 3 Projects
- Project Manager assignments
- Employee-Project mappings

## 📐 ER Model Features

- **One-to-many** relationship between FundingAgency and Project.
- **Many-to-many** relationship between Employee and Project (handled via `Employee_Project`).
- **One-to-one** relationship for Project and Manager (via `Project_Manager`).

## 🧮 Technologies Used

- SQL (DDL + DML)
- Relational Database Design Principles
- ER Modeling Concepts

---

![image](https://github.com/user-attachments/assets/6b282aa0-39d5-4fad-a347-09f3d5f38bb4)

![image](https://github.com/user-attachments/assets/e0c7ac33-2b5e-4e6d-b187-8eaf61aabdbd)


