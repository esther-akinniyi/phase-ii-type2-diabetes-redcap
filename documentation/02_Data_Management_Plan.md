# Data Management Plan

## Project Information

**Project Title:** Phase II Type 2 Diabetes Clinical Trial REDCap Database

**Database Platform:** REDCap (Research Electronic Data Capture)

**Project Type:** Simulated Clinical Trial Portfolio Project

---

# Purpose

This Data Management Plan (DMP) describes the procedures used to collect, validate, review, and manage clinical trial data within the REDCap Electronic Data Capture (EDC) system.

The objective is to ensure that study data are complete, accurate, consistent, and audit-ready throughout the study lifecycle.

---

# Database Design

The REDCap database consists of six electronic Case Report Forms (eCRFs):

| Instrument | Purpose |
|------------|---------|
| Screening & Enrollment | Participant enrollment and baseline information |
| Medical History | Medical history and lifestyle information |
| Concomitant Medications | Medication tracking |
| Adverse Events | Safety monitoring |
| Follow-up Visit | Follow-up clinical assessments |
| End of Study | Study completion |

---

# Data Collection

Participant data are entered directly into REDCap using standardized electronic Case Report Forms (eCRFs).

Data collected include:

- Participant demographics
- Medical history
- Clinical measurements
- Medication history
- Adverse events
- Follow-up assessments
- Study completion information

---

# Data Validation

The following validation techniques were implemented:

- Required fields
- Date validation
- Integer validation
- Numeric range validation
- Dropdown selections
- Radio button selections
- Checkbox validation
- Calculated BMI field

These validations help minimize data entry errors and improve overall data quality.

---

# Data Entry

Data entry follows the chronological study workflow:

1. Screening & Enrollment
2. Medical History
3. Concomitant Medications
4. Adverse Events
5. Follow-up Visit
6. End of Study

Each completed instrument is marked using the REDCap Form Status field.

---

# Query Resolution

Data discrepancies identified during review are investigated and corrected before study completion.

Potential queries include:

- Missing required fields
- Invalid dates
- Incorrect numeric values
- Inconsistent participant information

---

# Audit Trail

All modifications made to the REDCap database are automatically recorded in the REDCap Logging module.

The audit trail captures:

- User
- Date and time
- Modified fields
- Data exports
- Report creation
- Data quality execution

---

# Data Quality Review

The REDCap Data Quality module was used to evaluate database integrity.

Validation checks included:

- Required fields
- Data validation errors
- Calculated fields
- Missing values

No discrepancies were identified during testing.

---

# Data Export

Study data were exported in CSV format for downstream analysis.

Exported files include:

- Data Dictionary
- Participant Demographics Report
- Sample Study Data

---

# Database Lock

Following successful User Acceptance Testing (UAT), data quality review, and verification of exported datasets, the database is considered ready for database lock.

No further modifications should occur after database lock without appropriate change control procedures.

---

# Conclusion

The REDCap database successfully supports standardized clinical data collection while demonstrating key Clinical Data Management processes, including database design, validation, quality review, reporting, and export.
