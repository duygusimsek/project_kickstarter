# Kickstarter_Challenge

## Purpose Of The Analysis

The play “Fever” is nearly reached its fundraising goal in a short time. 

The customer wants to know about different campaigns processes in the context of their launch dates and their funding goals. 

## Analysis and Challenges

### Outcomes-Based on Launch Dates

To analyze the “Outcomes Based on Launch Dates”, a new column “Years” was created by using the “Date Created Conversion” column as the source. [kickstarter_challege.xlsx](https://github.com/duygusimsek/project_kickstarter/blob/main/Kickstarter_Challenge.xlsx.zip)

Based on the “Parent Category” and the “Years” columns from the “Kickstarter” worksheet, a pivot table was created and labeled as “Theater Outcomes by Launch Date”. 

Since the customer is interested in theater, the pivot table was rearranged to display only the data for “theater”. 

For this analysis visual presentation was added.[Theater_Outcomes_vs_Launchpng.png](https://github.com/duygusimsek/project_kickstarter/blob/main/Resources/Theater_Outcomes_vs_Launchpng.png)

### Outcomes-Based on Goals

Based on the campaign’s goals a new worksheet was created and labeled “Outcomes Based on Goals”.  In this worksheet, numbers of successful failed or canceled and percentages of successful failed or canceled were calculated. 

The data that had been sorted was filtered to the “play” subcategory on account of customer interest. 
 
For visual presentation to this analysis, a line chart was added.[Outcomes_vs_Goals.png](https://github.com/duygusimsek/project_kickstarter/blob/main/Resources/Outcomes_vs_Goals.png)

## Results

### Examining our findings

1. For “Outcomes-Based on Launch Dates”

- The “Theater Outcomes by Launch Date” line chart indicates that a greater number of successful campaigns had been launched in May. 
- The chart shows that most of the failed campaigns had been launched in October. Also, canceled campaigns line’s reveals that there is no canceled campaign in October.  


2. For “Outcomes-Based on Goals”

- The “Outcomes-Based on Goals” line chart indicates that the percentage of successful campaigns is the highest in the “Less than 1000” goal. 
- The goal range between  “15000 to 19999” is that the percentages of successful and failed campaigns are equal. 
- When we look at the chart, we can see the symmetric relationship between the “sum of percentage successful” and the “sum of percentage failed” because the “sum of percentage canceled” is zero.  

To create a more reliable analysis, new data sets are needed. 


