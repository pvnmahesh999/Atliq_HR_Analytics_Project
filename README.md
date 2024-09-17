# HR_Analytics

🚀 Project Overview
This project tackles the HR challenges at ATLIQ Hardware by analyzing employee attendance patterns, work-from-home (WFH) preferences, sick leave frequencies, and other key metrics. Using Power Query and DAX formulas, we developed an insightful dashboard to support data-driven workforce management decisions.

🎯 Problem Statement
The HR team at ATLIQ Hardware faced difficulty in:

Tracking employee preferences between WFH and office attendance.
Understanding reasons behind these choices.
Monitoring the frequency of sick leave and overall leave days.
Providing insights into WFH and sick leave percentages to better manage employee presence.

💡 Solution Approach
The provided data was spread across multiple Excel sheets—one for each month, with daily columns indicating whether an employee was working from home, in the office, on leave, or sick. To transform this scattered data into actionable insights:

Data Integration:

Merged multiple Excel sheets into a single file using Power Query.
Consolidated daily data into a unified Date column for all months, ensuring a streamlined structure.

Data Transformation:

Used advanced transformations like pivoting data, creating parameters, and invoking functions across multiple datasets to ensure consistency and accuracy.
Reformatted the data to track employee attendance and leave trends, removing inconsistencies and redundancies.

Metrics Creation:

Utilized DAX formulas to create metrics for tracking employee attendance patterns:
Employee Presence Trends (In-office vs. WFH).
Sick Leave Percentages.
Work-from-Home Patterns.

These metrics provide HR with critical insights to optimize workforce management.

🛠 Technologies & Tools Used
Power Query: Data cleaning, merging, and transformation.
DAX (Data Analysis Expressions): Metric creation and calculation.
Power BI: Dashboard design and data visualization.

📊 Key Insights
Consolidated multiple date columns into a single date structure to streamline analysis.
Utilized pivot tables and other Power Query functionalities for effective data transformation.
Identified trends in employee behavior, enabling HR to make informed decisions on workforce management.

📝 Learnings and Takeaways
Data Consistency: Always ensure a single date column for easier time-series analysis.
Advanced Power Query Functions: Mastery of pivoting, parameter management, and function invocation helped handle large datasets efficiently.
Data Validation: Regularly verify data formats after transformations to avoid discrepancies during analysis.


🚀 How to Use This Project
Download the data files from the data/ directory.
Open the Power BI file in the dashboard/ directory to explore the dashboard.
Review the Power Query scripts in the scripts/ folder to understand the data cleaning and transformation process.
Feel free to modify the DAX formulas to create additional insights as needed.

🔗 Links

Full project documentation: GitHub Repository

