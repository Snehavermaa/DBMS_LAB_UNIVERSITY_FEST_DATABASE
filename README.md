
# 🎉 University Fest Management System

This repository contains the lab work and code implementation for the **University Fest Management System** case study. The project focuses on designing and managing a database that streamlines the process of organizing and handling university fests.

## 📌 Project Overview

University fests are vibrant events involving multiple teams, participants, events, and stalls. To manage this effectively, we designed a **Database Management System (DBMS)** that captures and organizes all relevant data including:

* **Fests**: Unique ID, name, and year of occurrence.
* **Teams**: Management (`MNG`) and Organizing (`ORG`) teams with details like team ID, name, type, and members.
* **Members**: Individual details such as member ID, name, DOB, age, and reporting hierarchy.
* **Events**: Organized by ORG teams, each with ID, name, venue, date, and registration price.
* **Participants**: Student details including SRN, department, semester, and event registrations.
* **Visitors**: Friends/family of participants with gender, name, and age.
* **Stalls & Items**: Food/items sold with stall ID, item details, type (Veg/Non-Veg), prices, and stock.

The system also ensures proper access controls for **Administrators**, **Team Heads**, **Stall Owners**, and **Participants**.

---

## 🗂️ Contents of the Repository

* **📄 ER Diagram** – Entity-Relationship diagram of the system with cardinalities and participations.
* **📄 Relational Schema** – Conversion of the ER diagram into relational schema.
* **💻 SQL Scripts** – Queries for creating, inserting, and managing data in the database.
* **📑 Case Study Document** – Original problem statement and requirements (for reference).

---

## 🚀 Features

* Management of multiple fests per year.
* Event registration (individual & group).
* Hierarchical team structure with heads and members.
* Stalls with item tracking, pricing, and purchase records.
* Automatic cascading of deletions (e.g., deleting a team cancels its events).
* Role-based access control:

  * **Admin** → Full read/write access.
  * **Team Heads** → Update events.
  * **Stall Owners** → Manage items and prices.
  * **Participants** → Read-only access.

---

## 🛠️ Tech Stack

* **Database**: SQL 
* **Concepts Used**:

  * Entity-Relationship Modeling
  * Relational Schema Design
  * Constraints & Keys
  * Role-based Access Control
  * SQL Queries (DDL, DML)

---

## 📚 How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/Snehavermaa/DBMS_LAB_UNIVERSITY_FEST_DATABASE.git
   cd DBMS_LAB_UNIVERSITY_FEST_DATABASE
   ```
2. Import the SQL scripts into your preferred RDBMS.
3. Run the queries to create tables and insert sample data.
4. Explore and extend the project with your own test cases.

---

## 📝 Author

This repository is maintained as part of the **Database Management Systems Lab** coursework, Department of Computer Science & Engineering.

