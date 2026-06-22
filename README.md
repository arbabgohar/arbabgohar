# Experience

## Engineering Intern
**InSitu Technologies Inc.** | Internship  
**Feb 2025 – Present** | United States | On-site

- Improved legacy C# application (QBApp) to retrieve materials required for product kitting and update the database without manually navigating the full database.
- Built an automated maintenance tracking workflow using SpecKit Plus, where agents monitor equipment due dates, send Slack alerts to engineers, and automatically update maintenance records.
- Performed sterilizer validation (IQ, OQ, PQ) for sterilization equipment to ensure compliance with medical device quality and regulatory requirements.
- Assisted with cleanroom environmental monitoring, including particulate and environmental data tracking to support controlled manufacturing conditions. Displayed data on Minitab statistical software for analysis.
- Supported equipment validation, calibration tracking, and document control within an electronic Quality Management System (eQMS) (Grand Avenue).
- Contributed to quality documentation, process verification, and compliance activities aligned with medical device quality standards.
- Developed automated workflows to track equipment maintenance schedules, send alerts to engineers, and update maintenance records for traceability.
- Assisted engineering teams with inventory and production data tracking to support manufacturing and quality operations.
- Familiar with ISO 13485, ISO 9001, and IEC 62304.

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

<img width="1915" height="940" alt="inops overview" src="https://github.com/user-attachments/assets/b15d7c1d-6ae2-4a27-b868-c08ca33b6bc9" />


