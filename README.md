# OKR Dashboard Project

- **Author Name**: Yue (Crystal) Hu
- **Date**: February 2023
 
## Introduction
The company recently launched an OKR (Objectives and Key Results) tool to track and manage OKRs across departments. This tool serves as a centralized repository for OKR data input, providing a structured approach to tracking goals and progress. The company's OKR structure is as follows:  
*(insert an image of OKR structure here)*

Due to licensing restrictions, only 250 licenses are available for the tool, including administrators. This means that access to the tool is limited to specific groups of employees, preventing company-wide access to the OKR tool directly.

## Project Goal
The goal of this project is to create a **Tableau dashboard** that allows every employee to access OKR data, even if they do not have a license for the OKR tool. This dashboard will serve as a centralized and accessible platform for viewing company-wide OKRs.

## Key Features
- **One Page Annual OKR View**: A high-level, one-page overview of all annual OKRs that can be used during readouts for executives. This summary view provides quick insights into company-wide progress.
- **Departmental Interactive Dashboard**: Employees can filter data by department, team, or individual OKRs.
- **Real-time Data Sync**: The dashboard will be regularly updated with data from the OKR tool, ensuring that employees always have access to the latest information.
- **User-friendly Design**: A simple, intuitive design that makes it easy for all employees to navigate and access the information they need.

## Data Source
The OKR data is sourced from the OKR tool. It includes the following key elements:
- Objective titles
- Key results
- Progress tracking (percentages)
- Departmental and individual-level OKRs

## Tools Used
- **Python**: To extract, transform, and load (ETL) the OKR data from the tool.
- - **Tableau**: For data visualization and dashboard creation.

## Data Process
1. **Data Extraction**:
   - Pull OKR data from the tool’s database, including objectives, key results, progress, and employee data.
   
2. **Data Transformation**:
   - Clean the data to ensure consistency in format and completeness.
   - Map objectives and key results to the correct teams and departments.

3. **Data Loading**:
   - Load the transformed data into Tableau for visualization.

## Dashboard Design
- **Overview Page**: Displays high-level OKR progress for the entire company, with options to filter by department or team.
- **Departmental Page**: Breaks down OKRs by department, allowing employees to view detailed progress.
- **Team Page**: Focuses on team-level OKRs, showing how teams are contributing to the company's overall objectives.

## Recommendations
1. **Expand License Allocation**: If demand for more direct interaction with the OKR tool increases, consider expanding the number of licenses available.
2. **
