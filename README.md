# Hospital-Patient-Records-Analysis
Hospital Patient Records Analysis with Tableau

Table of Contents
Case Study

Dataset Description

ER Diagram

Data Cleaning

Dashboard

Case Study
As part of the Maven Hospital Challenge, this project acts as an analytics consulting solution for Massachusetts General Hospital (MGH). It delivers a high-level KPI report designed for the executive team, drawn from a subset of patient records. The report provides insights into the hospital’s recent performance by answering these key questions:

How many patients have been admitted or readmitted over time?

What is the average length of patient stays?

What is the average cost per visit?

How many procedures are covered by insurance?

The dashboard is designed to scale as new data becomes available, while summarizing impactful insights from the current dataset.

Dataset Description
The dataset includes several core observations:

Encounters
Unique identifier for each encounter.

Start and stop dates/times (ISO 8601 UTC).

Foreign key references to Patients, Organizations, and Payers.

Encounter classifications (ambulatory, emergency, inpatient, wellness, urgent care).

Encounter and diagnosis codes from SNOMED-CT.

Costs including base encounter cost, total claim cost, and payer coverage.

Organization
Organization details including ID, name, and address fields.

Geographic coordinates (latitude and longitude).

Patients
Unique identifiers and demographic details including birth and death dates.

Personal information like name prefixes, suffixes, marital status, race, ethnicity, and gender.

Addresses and geographic data.

Payers
Insurance information with contact details and headquarters location.

Procedures
Procedure start and stop times.

Patient and encounter associations.

Procedure codes and descriptions.

Related costs and diagnosis reasons.

ER Diagram
A visual representation of the relationships between tables is available to illustrate the database schema.

Data Cleaning & Calculated Fields
Data preprocessing steps include:

Cleaning patient names to remove special characters.

Calculated metrics for admission/readmission counts.

Duration of hospital stays.

Counting procedures and assessing insurance coverage status.

Patient age groups and admission status classification.

Identification of the latest encounter per patient.

Filtering metrics to focus on recent data.

Determining patient survival status.

Dashboard
The Power BI dashboard provides:

An overview of key patient and hospital metrics.

Detailed views on patient demographics and encounter details.

Interactive visualizations to explore insights on admissions, procedures, costs, and coverage.

