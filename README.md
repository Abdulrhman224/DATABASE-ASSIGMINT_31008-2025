# Advanced SQL Assignment: CTEs & Window Functions

## Academic Integrity Statement
I affirm that this submission is entirely my own original work conducted in accordance with university academic regulations.

* **Student Name:** [ABDALRHMAN ELTYEB]
* **Student ID:** [31008/2025]
* **Course:**  Database Programming
* **Instructor:** Eric Maniraguha
* **Institution:** UNILAK (University of Lay Adventists of Kigali)

---

Business Scenario
This project implements a **Hospital Management System** to track clinical operations, doctor-patient assignments, and consultation fees. The database architecture consists of 3 interrelated tables: `Doctors` (featuring a self-referencing administrative hierarchy), `Patients`, and `Appointments`.

### Database ER Diagram
```text
[Doctors] (1) <------- (N) [Appointments] (N) -------> (1) [Patients]
