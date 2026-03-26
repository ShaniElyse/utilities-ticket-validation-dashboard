# utilities-ticket-validation-dashboard

Overview
This project was built based on a real-world workflow where operational ticket data was used for reporting and revenue tracking.

The original process relied on manual corrections and was prone to:

inconsistent data entry (e.g., “Mike” vs “mike”)
missing or invalid hours
fragile Excel formulas
lack of validation controls

Problem
Data inconsistencies and manual processing created:

unreliable reporting
time-consuming cleanup
potential revenue leakage

Solution
I designed a structured Excel-based validation system with:

Controlled Input Layer
Automated Data Cleaning (standardization)
Validation Engine (error detection)
Revenue Risk Tracking
Executive Dashboard

Example Insight
Even Excel’s Copilot flagged inconsistent entries:

“MIKE vs mike”

The system handles this automatically using standardization logic, preventing reporting errors.

Key Features
Standardizes names using UPPER(TRIM())
Flags:
missing fields
invalid hours
outlier values
Calculates estimated revenue risk
Separates input, processing, and reporting layers

Impact
Reduced manual intervention
Improved data reliability
Increased visibility into data quality issues
Created a scalable validation framework

Skills Demonstrated
Data Validation & Quality Control
Excel Modeling
Process Improvement
Risk Identification
Data Governance
