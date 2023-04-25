# Data Professionals Survey Breakdown
This GitHub repository is dedicated to examining and breaking down the results of a survey conducted among professionals in the field of data analysis.


The project deliverables consist of a PowerBI .pbix file and a PDF document.

The following steps were executed to transform the data from "Initial Data.xlsx" to "Clean Data.xlsx". These steps were taken to prepare the data for visualization using Power BI:

1. Removed the columns "Browser", "OS City", "Country", and "Referer" since they were not needed for the analysis.
2. Used the "Split Column by Delimiter" function with "(" delimiter to unify all "Other" options into a single category called "Other" for the "Q1 - Which Title Best Fits your Current Role?" column.
3. Used the "Split Column by Delimiter" function with ":" delimiter to unify all "Other" options into a single category called "Other" for the "Q5 - Favorite Programming Language" column. The same process was done for the columns "Q4" and "Q11".
3. Created averages from the Yearly Salary ranges. The original column with ranges was kept, and a duplicate column was created to use for splitting. The column was split using the "-" delimiter, and the "k"s were removed using the "Replace Values" function. A new column was then created to calculate the averages.


The "Clean Data.xlsx" file was used to create the dashboard on PowerBI.