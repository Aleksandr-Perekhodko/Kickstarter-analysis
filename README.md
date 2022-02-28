# Kickstarting with Excel

## Overview of Project
### Purpose
The purpose of this project was to show Theare outcome based by launch date, and the outcomes based on goals. The way that this all shown was by using excel to create tables, graphs, and formulas to show how data can be used.

### Analysis of Outcomes Based on Launch Date
 In this project there was a table that was created in *Theatre Outcomes By Launch Date* sheet in the excel project, and from that pivot table there was a pivot chart created to help visualize what that pivot table is trying to explain. The way the pivot table was created is by adding a years column and using **Year()** formula and adding the Date Created Conversion column date into the **Year()** formula, and then copying the data given in the *Kickstarter* sheet. And inserting it in a a pivot table and creating a new sheet which is called *Theatre Outcomes By Launch Date*. Then opening the pivotchart fields and adding Category and Years into Filters, outcomes into the Legend, Date Created Conversion into Axis and removing Years2 and Quarters, and outcomes into Values. After creating a pivotchart line graph and changing the colors of the line graph.<img width="382" alt="Theatre_Outcome_vs_Launch" src="https://user-images.githubusercontent.com/97326526/156063307-65c953d2-af5f-4359-9606-42abc236a316.png">
### Analysis of Outcomes Based on Goals
The second thing that was created from the Kickstarter project was the analysis of the outcomes based on goals, this would have the goals based on currency this was measured by creating a sheet called *Outcomes Based on Goals* and having a columns called Goal, Number Successful, Number Failed, Number Canceled, 
Total Projects, Percentage Successful, Percentage Failed, and Percentage Canceled. In the rows under would be an estimation of the amount that each of these kickstarter have a goal to create the plays the estimate would go by Less Than 1000, 1000 to 4999, 5000 to 9999, and going up by 4999 until it reaches 50,000 or More. Then to get retrieve the data from the *Kickstarter* sheet the use of the **COUNTIFS()** formula would be used this would be done for the Number Successful, Number Failed, and Number Canceled columns. The COUNTIFS formula would look like this *=COUNTIFS(Kickstarter!D:D,"<1000", Kickstarter!F:F,"successful", Kickstarter!R:R, "plays")*, *=COUNTIFS(Kickstarter!D:D,">=1000", Kickstarter!F:F,"successful",Kickstarter!D:D,"<=4999", Kickstarter!R:R, "plays")*, *=COUNTIFS(Kickstarter!D:D,">=50000", Kickstarter!F:F,"successful", Kickstarter!R:R, "plays")*, for the Number Successful column, and changing the formula based on if succeful, failed, or canceled. The for Total Projects would use the **SUM()** formula which would sum up the number of project from Number of Successful, Number Failed, and Number Canceled for each estimated around so for the first estimated amount of Less than 1000 it would look like *=SUM(B2,C2,D2)*. And for the percentages use a simple division formula for Percentage Successful I used Number Succeessful and divide that by Total Projects and then change the number format to percentage. The formula for that looks like this *=(B2/E2)*. For the the graph take the data and created a line graph and filter out everything except all the percentages and change the colors accordingly and add a chart title. 


<img width="496" alt="Outcomes_vs_Goals" src="https://user-images.githubusercontent.com/97326526/156068815-1a1f4d3c-12fb-4761-a4b5-2f58e5b37b12.png">

### Challenges and Difficulties Encountered

## Results
