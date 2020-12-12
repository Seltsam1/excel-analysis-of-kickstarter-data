# excel-analysis-of-kickstarter-data
Excel analysis of Kickstarter data based on 4,000 past projects to uncover hidden trends

Part 1
--------------------

Sheet - Data

Column F includes conditional formatting – color highlighting: successful (green), failed (red), canceled (yellow), and live (gray)

Column O includes Percent Funded – formula showing % funded to initial goal

Column O includes conditional formatting – three color scale: 0% (red), 100% (green), and 200% (blue)

Column P includes Average Donation – formula showing average paid by backers

Column Q includes Category – formula to extract category from column N (left)

Column R includes Sub-Category – formula to extract sub category from column N (right)

Column S includes Date Created Conversion – formula to convert timestamp in column J to excel format

Column T includes Date Ended Conversion – formula to convert timestamp in column I to excel format


--------------------

Sheet – Category

Pivot table showing count of outcome(status) by category

Pivot chart (stacked column) showing count of outcome by category with country filter

--------------------

Sheet – Sub_Category

Pivot table showing count of outcome(status) by sub-category

Pivot chart (stacked column) showing count of outcome by sub-category with country and category filters


--------------------

Sheet – Date_Conversion

Pivot table showing count of outcome(status) by month with years and category filters

Pivot chart (line) showing count of outcome by month 


--------------------

Sheet – Bonus

Column B through D – formula with countifs to determine if campaigns within certain goal parameters based on status (B – Successful, C – Failed, D – Canceled)

Column E – total of values from columns B through D

Column F through H – formula for percentage outcome based on goal (F – successful, G – failed, H – canceled)

Line chart of percentage of outcome by goal amount



--------------------

Word Document includes insights
