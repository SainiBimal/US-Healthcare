Healthcare Dataset Analysis 

Overview

This repository contains a comprehensive healthcare dataset with patient records spanning multiple years. The dataset includes detailed information about patient demographics, medical conditions, treatments, billing, and hospital administration details.

Dataset Description
File Information
Filename: USA Healthcare Bimal.xlsx

Sheet Name: Data1

Number of Records: 265 patient entries

Data Range: 2018-2023

Columns Included
The dataset contains the following fields for each patient record:

Patient Information

Name

Age

Age Bucket (Young/Middle/Senior)

Gender

Demographic Group (Age-Gender combination)

Medical Details

Blood Type

Medical Condition (e.g., Diabetes, Asthma, Cancer, etc.)

Medication Prescribed

Test Results

Hospitalization Details

Date of Admission

Admission Type (Elective/Emergency/Urgent)

Discharge Date

Room Number

Doctor

Hospital

Financial Information

Insurance Provider (e.g., Medicare, Aetna, Blue Cross, etc.)

Billing Amount

Temporal Information

Year, Month, Quarter, Week, Day (derived from admission date)

Data Characteristics
Age Distribution: Patients range from 19 to 85 years old

Medical Conditions: Includes common conditions like Diabetes, Hypertension, Asthma, Arthritis, Obesity, and Cancer

Insurance Providers: Medicare, Aetna, Blue Cross, UnitedHealthcare, Cigna, etc.

Time Period: Data covers admissions from November 2018 through November 2023

Potential Use Cases
This dataset can be used for:

Healthcare Analytics

Patient demographic analysis

Treatment effectiveness studies

Hospital resource utilization

Financial Analysis

Insurance claim patterns

Billing amount distributions

Cost analysis by condition

Temporal Analysis

Admission trends over time

Seasonal patterns in medical conditions

Length of stay analysis

Medical Research

Condition prevalence by demographic

Medication prescription patterns

Test result correlations

Data Quality Notes
Formulas: Some columns contain Excel formulas (visible in the raw data)

Reference Errors: Some VLOOKUP formulas reference #REF! indicating possible broken links

Consistency: Demographic Group is consistently generated from Age Bucket and Gender

Date Formats: Most dates follow standard formats, with a few exceptions

Suggested Analysis Approaches
Data Cleaning

Convert formulas to values for stability

Standardize date formats

Handle any missing or inconsistent data

Exploratory Analysis

Distribution of medical conditions

Average billing amounts by condition

Most common insurance providers

Advanced Analytics



Clustering of patient profiles

Time series analysis of admissions
