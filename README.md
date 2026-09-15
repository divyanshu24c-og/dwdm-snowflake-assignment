# dwdm-snowflake-assignment
Snowflake tutorial and practical assignment covering SnowSQL, object creation, data loading, and Time Travel features.
# Snowflake DWDM Tutorial Assignment

This repository contains the practical lab work and implementation steps for the Data Warehousing and Data Mining (DWDM) Snowflake tutorial assignment.

---

## Assignment Overview & Steps

### Task 1: SnowSQL Login and Connection
* Connected to the Snowflake account via SnowSQL CLI using account identifier `yjemxcs-hj02840`.
* Verified session parameters (`CURRENT_USER`, `CURRENT_ROLE`, `CURRENT_WAREHOUSE`, `CURRENT_DATABASE`, `CURRENT_SCHEMA`).

### Task 2: Creation of Snowflake Objects & DML Operations
* Created an `XSMALL` warehouse (`dwdm_wh`), database (`dwdm_db`), schema (`dwdm_schema`), and internal stage (`my_internal_stage`).
* Created a `student_records` table and performed `INSERT`, `SELECT`, `UPDATE`, and `DELETE` operations on 10 student records.

### Task 3: Data Loading Using SnowSQL
* Prepared a local CSV dataset containing student entries.
* Staged the file into Snowflake using the `PUT` command and loaded the records into the table using `COPY INTO`.
* Verified data ingestion using `SELECT` queries.

### Task 4: Snowflake Time Travel & Data Recovery
* Created a demonstration table (`time_travel_demo`) and performed data modifications (`UPDATE` and `DELETE`).
* Used Snowflake's **Time Travel** feature (`AT (OFFSET => ...)`) to query the historical state of the table before modifications occurred.

---

## Repository Structure
* `scripts/` - Contains SQL execution scripts for object creation and data loading.
* `screenshots/` - Contains output verification screenshots for all tutorial tasks.
