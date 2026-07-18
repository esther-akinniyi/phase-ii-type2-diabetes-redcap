# Phase II Type 2 Diabetes Clinical Trial REDCap Database

## Project Overview

This project demonstrates the design, configuration, testing, and validation of a REDCap Electronic Data Capture (EDC) database for a simulated Phase II clinical trial evaluating a treatment for Type 2 Diabetes Mellitus.

The database was designed following common Clinical Data Management (CDM) principles used in clinical research, including electronic Case Report Form (eCRF) development, data validation, data quality review, audit trail verification, reporting, and user acceptance testing (UAT).

> **Note:** This is a simulated portfolio project created for educational and professional development purposes. It does not contain real participant data.

---

## Study Objective

To build a production-style REDCap database capable of collecting and managing participant data throughout a simulated Phase II Type 2 Diabetes clinical trial.

---

## Project Goals

- Design a multi-instrument REDCap database
- Build standardized electronic Case Report Forms (eCRFs)
- Configure field validation and required fields
- Perform User Acceptance Testing (UAT)
- Execute REDCap Data Quality checks
- Generate participant reports
- Export study datasets
- Document the project following Clinical Data Management best practices

---

# Study Workflow

Participant Screening
        ↓
Medical History
        ↓
Concomitant Medications
        ↓
Adverse Events
        ↓
Follow-up Visit
        ↓
End of Study

---

# REDCap Instruments

The project includes six electronic Case Report Forms (eCRFs):

| Instrument | Purpose |
|------------|---------|
| Screening & Enrollment | Participant eligibility, demographics, baseline clinical information |
| Medical History | Medical conditions, lifestyle factors, family history |
| Concomitant Medications | Medication documentation throughout the study |
| Adverse Events | Capture and management of adverse events |
| Follow-up Visit | Collection of follow-up clinical measurements |
| End of Study | Study completion and participant disposition |

---

# REDCap Features Demonstrated

- Electronic Case Report Form (eCRF) Design
- Required Field Configuration
- Data Validation Rules
- Calculated Fields (BMI)
- Dropdown Menus
- Radio Buttons
- Checkboxes
- Notes Fields
- Date Validation
- Numeric Validation
- Record Status Dashboard
- Codebook
- Data Dictionary
- Data Export
- Reports
- Audit Trail (Logging)
- Data Quality Module
- User Acceptance Testing (UAT)

---

# User Acceptance Testing (UAT)

A fictional participant record was entered to verify:

- Data entry workflow
- Required field enforcement
- Field validation
- Calculated BMI
- Instrument completion
- Record saving
- Data export
- Report generation

All instruments successfully passed testing.

---

# Data Quality

REDCap Data Quality Rules were executed to verify database integrity.

Validation included:

- Required fields
- Data validation errors
- Calculated fields
- Missing values

Result:

**No data discrepancies were identified during testing.**

---

# Reports Created

- Participant Demographics Report

---

# Repository Structure

```text
phase-ii-type2-diabetes-redcap/
│
├── README.md
├── LICENSE
│
├── screenshots/
│   ├── Project setup
│   ├── Online Designer
│   ├── Data Dictionary
│   ├── Codebook
│   ├── Record Status Dashboard
│   ├── Participant Report
│   ├── Sample Study Data
│   ├── Data Quality
│   └── Audit Trail
│
├── data/
│   ├── Data Dictionary
│   ├── Participant Demographics Export
│   └── Sample Study Data
│
├── documentation/
│
└── assets/
```

---

# Project Screenshots

The repository includes screenshots demonstrating:

- Project Setup
- Online Designer
- Data Dictionary
- Codebook
- Record Status Dashboard
- Participant Demographics Report
- Data Quality Results
- Audit Trail Logging

---

# Walkthrough Video

A complete walkthrough of the REDCap database is available here:

**Video:** *(Add YouTube or Google Drive link here)*

---

# Technologies Used

- REDCap
- Clinical Data Management
- Electronic Data Capture (EDC)
- Electronic Case Report Forms (eCRFs)
- Data Validation
- User Acceptance Testing (UAT)
- Data Quality Review
- CSV Data Export
- GitHub

---

# Clinical Data Management Skills Demonstrated

This project demonstrates experience with:

- REDCap Database Design
- eCRF Development
- Clinical Trial Data Collection
- Data Validation
- Data Cleaning
- Data Quality Review
- Audit Trail Review
- User Acceptance Testing
- Clinical Documentation
- Clinical Data Export
- Clinical Reporting
- Database Documentation

---

# Future Improvements

Potential enhancements include:

- Branching Logic
- Longitudinal Events
- Repeating Instruments
- User Rights Management
- Data Access Groups (DAGs)
- Automated Survey Distribution
- Randomization Module
- Scheduling Module

---

# License

This project is licensed under the MIT License.
