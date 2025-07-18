# Creating Dynamic Dashboards in Excel
This dataset includes 100 mock employee records with key fields such as department, education, performance rating, attrition status, and more—ready for building  dashboard.


## Summary of steps to complete
Step 1: Open the Excel File
Open the HR_Attrition_Dashboard_Data.xlsx file in Excel.

Make sure the data is formatted as an Excel Table (if not: select the range → Insert → Table).

🔹 Step 2: Create Pivot Tables
Create these pivot tables on separate sheets or one sheet to start organizing your visuals.

1. Department-wise Employee Count
Insert Pivot Table → Choose Department (Rows) + EmployeeID (Values → Count).

Rename value as "Employee Count".

2. Attrition by Department
Rows: Department

Columns: Attrition

Values: Count of EmployeeID

3. Average Years at Company by Department
Rows: Department

Values: Average of YearsAtCompany

4. Gender Distribution
Rows: Gender

Values: Count of EmployeeID

5. Performance Rating Distribution
Rows: PerformanceRating

Values: Count of EmployeeID

6. Job Satisfaction Average
Rows: Department

Values: Average of JobSatisfaction

🔹 Step 3: Create Visual Charts
Use Pivot Charts to make visualizations:

Pie Chart: Gender Distribution

Column Chart: Employee Count by Department

Stacked Column: Attrition by Department

Line or Column Chart: Performance Rating Distribution

Bar Chart: Avg Job Satisfaction by Department

Customize chart titles, legends, and colors for clarity.

🔹 Step 4: Add Slicers for Interactivity
Click on any Pivot Table → Insert Slicer → Choose:

Department

Gender

SalaryBand

Education

These slicers will allow users to filter the dashboard dynamically.

🔹 Step 5: Create a Dashboard Sheet
Create a new worksheet → rename it “Dashboard”.

Copy and paste key Pivot Charts to this sheet.


## Create the Excel dashboard 

Step 6: Polish and Finalize



## Turn in your completed Excel dashboard

* Submit the file in Canvas.
[HR_Attrition_Dashboard_Data.xlsx](https://github.com/user-attachments/files/21308259/HR_Attrition_Dashboard_Data.xlsx)
