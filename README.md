# Employee Attrition Prediction with AutoML and Power BI

## Objective
This project aims to build a predictive system for employee attrition using AutoML techniques (via PyCaret) and integrate it with Power BI for interactive visualization. The goal is to shift from a reactive analysis (observing employee departures) to a proactive strategy (anticipating and preventing attrition).

## Business Problems to Solve
- Identify employees at high risk of leaving the company
- Understand the main factors contributing to attrition (salary, commute distance, job role, manager, etc.)
- Provide HR and managers with decision-making tools for targeted retention actions
- Reduce costs related to hiring, onboarding, and lost productivity

## Deliverables
- A trained and validated binary classification model (Attrition: Yes/No)
- A saved machine learning model (.pkl file)
- An interactive Power BI report displaying:
  - List of employees with their attrition risk scores
  - Dashboards highlighting key attrition factors
  - Filtering capabilities (by department, manager, etc.)

## Project Phases
1. Data preparation and exploration
2. AutoML modeling using PyCaret
3. Model industrialization and saving
4. Integration with Power BI and dashboard creation

## Technologies Used
- Python (PyCaret, pandas)
- Power BI Desktop
- Power Query with embedded Python scripts
