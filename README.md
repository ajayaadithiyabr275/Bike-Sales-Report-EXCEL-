# Bike-Sales-Report(Interactive Dashboard Creation using MS EXCEL)

Research Questions: 
i. What is the average income of those who purchased bikes and those who did not, based on their gender?
ii. Does the commute distance affect the purchases of bikes?
iii. What age groups make the most bike purchases?

Data Cleaning and Preprocessing:
The data looked clean to an extent but I had to still check for some quality issues.
Checked for duplicates (26 duplicates were found and removed leaving 1000 unique values using the Remove duplicates feature), missing values but there were none.
Scanned through each of the columns one by one, replaced M with Married and S with Single in the Marital Status column, replaced M with Male and F with Female in the Gender column, using the Find and Replace feature.
Created a new column named “Age group” from the Age column using the Nested If statement in the formula:
=IF(L2>54,”Old (55+)”,IF(L2>=31,”Middle Aged (31–54)”,IF(L2< 31,”Adolescent (18–30)”,”Invalid”)))
- Converted the format in the Income column from Custom to Currency.

Data Visualization:
1.Created Pivot tables and visualized the tables with recommended charts
To create Pivot tables: Insert tab — Pivot Table — From Table/Range
2. Created Slicers — easy-to-use buttons or filters in a report or chart that help you quickly narrow down the information you want to see. 4 slicers were created; Marital Status, Education, Occupation, Region
3. Built an Interactive dashboard

Summary:
Income and Bike Purchase: People with higher incomes tend to purchase bikes. This suggests targeting higher-income individuals in marketing.
Commute Distance and Bike Purchase: Bike purchases peak for short commutes (0–1 mile and 2–5 miles). Promoting biking as a convenient short-distance solution is recommended.
Age Group and Bike Purchase: Middle-aged customers show the highest bike purchases. Marketing emphasizing health and leisure benefits for this group is advised.

