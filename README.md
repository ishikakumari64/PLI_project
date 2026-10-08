# PLI Data Engineering Project

## Overview

PLI is a data engineering and analytics project built using dbt to transform, test, and organize data into structured datasets for analysis and reporting.

The project follows a layered data transformation approach, where raw data is processed through staging models and converted into final analytical tables.

## What This Project Does

The project focuses on:

* Data transformation using dbt
* Building staging and final data models
* Data cleaning and preparation
* Data quality testing
* Reusable SQL transformations using macros
* Data analysis using dbt analyses
* Data monitoring and observability using Elementary

## Project Structure

```text
PLI_project/
|
|-- analyses/
|-- asset/
|-- dbt/
|-- macros/
|-- models/
|-- seeds/
|-- snapshots/
|-- tests/
|-- dbt_project.yml
|-- packages.yml
```

## Data Pipeline

```text
Raw Data
   |
   v
Staging Models
   |
   v
Data Transformation
   |
   v
Data Quality Tests
   |
   v
Final Analytical Tables
   |
   v
Analysis and Reporting
```

## Technology Stack

* dbt
* SQL
* Elementary
* Data Transformation
* Data Quality Testing
* Data Analysis

## Key Learning

This project demonstrates how dbt can be used to build a structured and maintainable data transformation pipeline with testing, reusable transformations, and data observability.

