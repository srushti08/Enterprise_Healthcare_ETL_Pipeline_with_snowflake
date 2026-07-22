
# Business Requirements Document (BRD)

# Enterprise Healthcare ETL Pipeline

---

## 1. Business Background

MediCore Health System is a multi-specialty hospital network operating across multiple locations. Each department, including Patient Registration, Appointments, Billing, Laboratory, Pharmacy, and Emergency, maintains its own operational system.

As the organization has grown, these systems have become isolated, making it difficult for management to obtain a unified view of hospital operations.

The leadership team requires a centralized reporting platform that combines data from all departments to support faster and more informed decision-making.

---

## 2. Current Challenges

The hospital currently faces several business challenges:

- Data is stored in multiple disconnected systems.
- Reports are manually prepared using Excel.
- Different departments report inconsistent numbers.
- Executive reporting takes several hours to prepare.
- Management cannot monitor hospital performance in real time.
- Identifying operational bottlenecks is difficult due to fragmented data.

---

## 3. Project Objectives

The primary objective of this project is to design and build an end-to-end Enterprise ETL Pipeline that integrates data from multiple hospital systems into a centralized Snowflake Data Warehouse.

The project aims to:

- Extract data from multiple hospital systems.
- Clean and validate incoming data.
- Transform data into a standardized format.
- Load the processed data into Snowflake.
- Enable SQL-based business analysis.
- Build interactive Power BI dashboards for stakeholders.
- Create a single source of truth for organizational reporting.

---

## 4. Success Criteria

The project will be considered successful if it achieves the following outcomes:

- Hospital data is successfully integrated into Snowflake.
- Data quality issues are minimized through validation and transformation.
- Business users can access consistent and reliable information.
- Executive dashboards provide real-time operational insights.
- Decision-makers can quickly identify trends, bottlenecks, and performance metrics.
- The ETL pipeline is modular, scalable, and easy to maintain.

---

## Document Status

**Version:** 1.0

**Status:** In Progress

**Prepared By:** Srushti Nakil

**Date:** July 2026
