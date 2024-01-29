# SHAI Organization - Salary Analysis Project

## Overview

This repository contains the code and data for the Salary Analysis project conducted by SHAI Organization. The goal of this project is to preprocess and analyze salary data to derive meaningful insights.

## Data Preprocessing

### Steps taken during Data Preprocessing:

1. **Convert Year column to datetime and integer:** The 'Year' column was converted to a datetime format and then to integer values for consistency and ease of analysis.

2. **Remove Notes and Status columns:** Columns 'Notes' and 'Status' were removed as they contained no valuable information.

3. **Filter out invalid rows:** Rows with numerical values less than zero in relevant columns were removed.

4. **Fill NaN values:** NaN values in 'Benefits' and 'BasePay' columns were filled with the mean value for each respective column.

## Feature Engineering

### Steps taken during Feature Engineering:

1. **Remove Agency column:** The 'Agency' column, containing only one unique value, was removed as it does not contribute to analysis.

2. **Update TotalPayBenefits:** TotalPayBenefits column was updated to reflect the changes made in the 'Benefits' and 'BasePay' columns.

3. **Create Department column:** A new 'Department' column was created by extracting information from the 'JobTitle' column.

4. **Mapping unique values for Department:** Each department was mapped to a unique identifier for better analysis.

## Data Analysis Summary

The analysis of the salary data reveals the following insights:

- **Department Proportions:** Employees in the CIVIL & CRIMINAL department have the second-largest proportion after the Management department.

- **Base Pay:** The Fire department has the highest average base pay per employee, followed by the CIVIL & CRIMINAL department.

- **Benefits:** Employees in the CIVIL & CRIMINAL department receive the highest average benefits among all departments.

- **Earnings:** The Fire department stands out with the highest average earnings per employee, reaching 272k.

## Conclusion

This project provides valuable insights into the salary distribution among different departments within the organization. Further analysis and interpretation can be carried out based on these findings. Feel free to explore the code and data in this repository for a detailed understanding of the methodology and results. For any questions or clarifications, please contact the SHAI Organization team.
