# Automated Data Dictionary System for the MSA ERP Environment

## Overview

This repository contains the final capstone project report for the **Automated Data Dictionary System for the MSA ERP Environment**, developed as part of a Master's in Information Science (Data Analytics Concentration).

The project focuses on designing and implementing a **fully automated, governed, and scalable enterprise metadata management system** to replace fragmented and manually maintained documentation in an ERP environment.

The solution integrates structured metadata submission, governance workflows, automated processing pipelines, and enterprise publication to improve **metadata quality, accessibility, consistency, and operational efficiency**.

---

## Problem Statement

Enterprise ERP systems contain large and complex datasets that often suffer from:

- Fragmented metadata documentation
- Inconsistent business definitions
- Manual spreadsheet-based maintenance
- Lack of governance and validation
- Difficulty tracking ownership and schema changes

These challenges can lead to reporting errors, reduced data trust, compliance risks, and inefficiencies in analytics and decision-making.

This project addresses these limitations by building an **automated enterprise Data Dictionary system** for the **MSA ERP environment**.

---

## Project Objectives

The system was designed with the following objectives:

- Centralize metadata contribution through a structured submission process
- Introduce governance and approval workflows
- Improve metadata quality and consistency
- Automate metadata extraction and transfer
- Enable enterprise-wide accessibility through searchable publication
- Support scalability and long-term maintainability

---

## System Architecture

The project follows an **end-to-end metadata lifecycle architecture**:

### Workflow

1. **Metadata Submission**
   - Business users submit metadata through a Power Apps interface.

2. **Administrative Governance**
   - Metadata is reviewed and validated for accuracy, consistency, and completeness.

3. **Operational Storage**
   - Approved metadata is stored in SQL Server as the authoritative source of truth.

4. **Automated Export & Transfer**
   - Metadata is exported to GitHub and securely transferred through HTTPS APIs.

5. **Microsoft Fabric Processing**
   - Data is ingested into a Fabric Lakehouse and transformed into curated Warehouse tables.

6. **Enterprise Publication**
   - Finalized metadata is published as a searchable Data Dictionary in FreshService.

---

## Technologies Used

- **Microsoft Fabric**
- **SQL Server**
- **Microsoft Power Apps**
- **GitHub**
- **FreshService**
- **HTTPS APIs**
- **ERP Metadata Management**
- **Data Governance Frameworks**

---

## Key Features

- Automated metadata ingestion pipeline
- Governance and approval workflow
- Structured metadata validation
- Version-controlled metadata storage
- Enterprise searchability and accessibility
- Secure data transfer architecture
- Scalable and modular system design

---

## Project Impact

This solution improves enterprise metadata management by:

- Reducing reliance on fragmented spreadsheets
- Improving metadata consistency and governance
- Supporting auditability and version tracking
- Increasing trust in ERP analytics and reporting
- Enabling both technical and non-technical stakeholders to access standardized metadata

---

## Repository Contents

```text
├── Capstone Project Report.pdf
├── User Manual.pdf
└── README.md
```

## Disclaimer

This repository contains academic project documentation developed for educational purposes. Certain implementation details and organizational references are included solely within the scope of the capstone project.
