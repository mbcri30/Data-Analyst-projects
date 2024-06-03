# Employee Retention Dashboard in Excel

This repository contains an Employee Retention Dashboard created in Excel, designed to analyze key KPIs related to employee retention. The dashboard provides insights into various factors affecting employee attrition and retention across different departments and roles.

## Introduction
This Excel dashboard is created to analyze and visualize key KPIs related to employee retention. The dashboard helps in understanding the factors influencing employee attrition and provides actionable insights for improving retention strategies.

## KPI Details
The key KPIs included in this dashboard are:
1. **Average Attrition Rate for All Departments**
2. **Average Hourly Rate of Male Research Scientists**
3. **Attrition Rate vs Monthly Income Statistics**
4. **Average Working Years for Each Department**
5. **Job Role vs Work-Life Balance**
6. **Attrition Rate vs Years Since Last Promotion Relationship**

## Data Import and Cleaning
The data provided was in CSV format. The steps taken to import and clean the data are as follows:
- Imported the CSV data into Excel.
- Used Power Query to remove duplicates, handle missing values, and standardize data formats.
- Transformed the data to make it suitable for analysis.

## Data Transformation
Data transformation steps included:
- Converting data types to ensure consistency.
- Creating new calculated columns needed for analysis.
- Aggregating data to generate summary statistics.

## Data Modeling
Data modeling involved using Power Pivot to establish relationships between different tables in the dataset.

Relationships were established based on common keys such as employee ID, department ID, and job role ID.

## Visualization
To visualize the KPIs, PivotTables and PivotCharts were used. The steps taken are:
1. **Average Attrition Rate for All Departments:**
   - Created a PivotTable to calculate the average attrition rate for each department.
   - Used a bar chart to visualize the attrition rates across departments.

2. **Average Hourly Rate of Male Research Scientists:**
   - Filtered data to include only male research scientists.
   - Created a PivotTable to calculate the average hourly rate.
   - Used a card visual to display the average hourly rate.

3. **Attrition Rate vs Monthly Income Statistics:**
   - Created a PivotTable to calculate attrition rates and average monthly income.
   - Used a scatter plot to visualize the relationship between attrition rate and monthly income.

4. **Average Working Years for Each Department:**
   - Created a PivotTable to calculate the average working years for employees in each department.
   - Used a bar chart to display the average working years.

5. **Job Role vs Work-Life Balance:**
   - Created a PivotTable to analyze work-life balance scores for different job roles.
   - Used a heat map to visualize the work-life balance scores across job roles.

6. **Attrition Rate vs Years Since Last Promotion Relationship:**
   - Created a PivotTable to analyze the relationship between attrition rate and years since last promotion.
   - Used a line chart to visualize this relationship.

## Dashboard
The dynamic dashboard includes all the above visuals and allows users to interact with the data through filters and slicers. Users can drill down into specific KPIs to gain deeper insights into employee retention factors.

## Conclusion
This Excel dashboard provides a comprehensive analysis of employee retention data, enabling better decision-making and insights into factors affecting employee attrition. The steps outlined above detail the process from data import to the final dashboard creation. Feel free to explore the visuals and gain insights from the data.
