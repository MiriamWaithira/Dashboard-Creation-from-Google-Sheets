# Dashboard-Creation-from-Google-Sheets
Creating a dashboard from data provided in a .xlsl file

# Steps to follow
1. Make a copy of the file. Open the file in Google Sheets. Go to File > Make a copy and save it to your preferred location.

2. Create scorecards for average majors, count of age, and average monthly expenses:

i. Average number of majors:
Select the column for majors. Click Insert > Charts > ScoreCards. Check the Aggregate box and Select Average.

ii. Count of age:
Select the column for Age. Click Insert > Charts > Scorecards. Check the Aggregate box and Select Count.

iii. Average of monthly expenses:
Highlight the last column in the sheet and add a column to the right. Click on the first row of the new column, Click Insert > Function > Sum. Write the columns to be added as sum of monthly expenditure and generate the sum for the whole column. Highlight that column then Check the Aggregate box and Select Average.

3. Create pivot tables (majors, year_in_school)

i. Select the data range. Go to Data > Pivot table.

ii. In the pivot table editor:
Add Majors in the Rows section. Add Year_in_school in the Columns section. Add appropriate values (e.g., Count of Majors, Sum/Avg of expenses, etc.) in the Values section.

iii. Create column charts
Highlight your pivot table. Go to Insert > Chart. In the chart editor, choose Column chart one for comparing years across majors and onother one for comparing majors across years.

4. Create pie chart

i. (preferred_payment_method)
Highlight the column for Preferred_payment_method. Go to Insert > Chart. In the chart editor, choose Pie chart.

ii. (gender)
Highlight the column for Gender. Go to Insert > Chart. In the chart editor, choose Pie chart.

The charts created from your data can be created and modified as you wish.