# Experience

## Engineering Intern
**InSitu Technologies Inc.** | Internship  
**Feb 2025 – Present** | United States | On-site
- Wrote and executed roughly 60 manual test cases supporting software V&V under IEC 62304, mapping each case back
to software requirements and ISO 14971 risk controls to maintain full traceability.
- Executed performance and functionality test protocols for a Class III intravascular device as part of a 5-year real-time
aging study, logging results in the eQMS for quality and regulatory review.
- Led IQ/DQ/OQ/PQ qualification protocols for new cleanroom equipment, scripting test execution steps, documenting
results, and tracking deviations through closure.
- Investigated a customer complaint through PMFEA, performed root cause analysis, and documented findings to support
post-market surveillance reporting.
- Closed CAPAs for software documentation gaps, including a missing design and development records issue, by
coordinating fixes across engineering and quality.
- Collaborated daily with software, systems, and quality engineers to resolve test discrepancies and keep manufacturing
and verification activities on schedule.

**Skills:** AI Engineering, API Integration, Medical Device Quality Systems, Process Validation, Automation, C#, SQL, Minitab, eQMS, Regulatory Compliance

---

## Data Engineer Intern
**Data Logics** | Internship  
**Aug 2024 – Dec 2024** | United States

- Designed and optimized data pipelines in Azure Databricks and Azure Data Lake, implementing ELT processes across bronze, silver, and gold layers.
- Managed efficient schema design with DDL scripts and shared solutions through GitHub for collaboration and version control.
- Processed large datasets, maintained historical records, and enforced business rules in enterprise data warehouses.
- Collaborated with teams to transform raw data into actionable insights, supporting reporting and analytics initiatives.
- Worked with subject-oriented architectures and dimensional data modeling techniques.

**Skills:** Data Modeling, Python, Azure Databricks, Azure Data Lake, SQL, ETL/ELT, Data Warehousing, Git, Analytics


# InOps - InSitu Operations

Currently working on **InOps**, an internal operations web app for **InSitu Technologies Inc.** that brings day-to-day manufacturing support tools into one browser-based command center.

InOps helps teams manage non-sterile inventory, QA product release, pull-out transactions, supply monitoring, equipment maintenance, calibration tracking, and operational reporting from the company network. It is built with Python, Flask, and pyodbc, connecting directly to MS Access databases and shared internal resources.

> **PS:** This is a vertical solution built specifically for InSitu Medical's internal infrastructure (network paths, Access databases, employee lists, product catalogue). It will not work out-of-the-box for any other organisation without significant configuration changes.

---

## Quick Overview

- **Web app** runs on one server, accessible from any PC on the network via browser (no installation on client machines)
- **InOps Command Center** central home screen for inventory, QA actions, supplies, and maintenance workflows
- **QA Product Release** look up a lot from the Master DB by Lot No or Ref No, review details, and release to inventory with verified-by, quantity, and optional comments
- **Pull-Out** record stock pull transactions against released lots; remaining quantity auto-decrements
- **Dashboard** live stats: total lots, available lots, total quantity, low-stock alerts, recent pulls, and per-catalog summary
- **Inventory Lookup** search and filter current inventory by Lot No or Ref No
- **Transaction History** full pull-out log, filterable by lot, catalog, or employee
- **Equipment Maintenance** track maintenance schedules, logs, status, and audit history
- **Barcode scanner ready** scanner acts as keyboard input with auto-submit on Enter

---

## App 
<img width="1446" height="770" alt="image" src="https://github.com/user-attachments/assets/fcfc6fb2-9d4d-44b2-a2be-864c18680773" />


<img width="1315" height="656" alt="image" src="https://github.com/user-attachments/assets/521da860-c8be-40af-bd41-fa03b9bff9da" />


