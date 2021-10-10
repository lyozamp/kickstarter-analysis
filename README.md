# kickstarter-analysis
Performing analysis on Kickstarter data to uncover trends
# Kickstarting with Excel 

## Overview of Project

### The purpose of this Analysis was to organize data for Louise from different Theater play’s. Specifically, we wanted to research and display the data from the launch date (January through December) and research if the outcome was successful, failed or canceled based on the funding goal amount.

## Analysis and Challenges 

### As seen in the “Theater Outcomes Based on Launch Date” line graph a majority of the successful theater plays occurred in the month of May. When comparing the amount of failed theater play’s to the successful, the month of May is significantly lower than other months. For example, the amount of successful was 111 and failed was 52 in May but in December there was 37 successful and 35 failed. The margin of error between the two were a lot closer in count than in May. I can conclude from this line graph and the data that the best time for Louise to launch a play would be during the month of May. 

### As seen in the “Outcomes Based on Goal” line graph it reflected that the lower the funding goal the easier it was to meet that goal. At less than $1,000 the percentage successful was about 75% which is the highest on the graph. However, between $35,000 to $44,999 the graph spiked in successful goals to about 65%. The highest percentage failed was from $45,000 to $49,000 at approximately 80% failed. 

## Challenges and Difficulties Encountered

### Starting with examining the theater outcomes by launch date, I filtered a pivot table based on “parent category” and “years” and adding the count for the “successful”, “failed” and “canceled” outcomes. After pulling in the data to this table I was able to create a line graph to show the count of successful, failed and canceled plays during each month from January to December. I didn’t run in to any challenges but a possible challenge that could be encountered would be if the incorrect fields were selected for columns and rows during the pivot table set up. 
### For the outcomes based on goals analysis, in a table I created a formula using COUNTIFS() to find the number successful, failed and canceled based on different goal amounts. Then I added the number successful, failed and canceled together to equal the total projects column. Using the number successful divided by the total project I got the total percentage successful, I did this for each of the categories (failed & canceled). Using the COUNTIFS formula in Excel challenged me as I had a difficult time figuring out the criteria and range to input and communicate from the Kickstarter data. 

## Results

The conclusions I can make about the Theater Outcomes by Launch Date is that the best month to launch a play in would be in the month of May and the worse month to launch a play in would be in the month of October. I can conclude that having a goal of $1,000 or less would have the highest percentage of success with the lowest percent of failed funds. A limitation of this dataset would be a culture bias of the storyline of a play that will be performed because a certain storyline might be more popular and have a greater goal outcome if it is more popular then storylines in others. I would recommend creating a table and chart on the true and false comparison on staff pick’s because that would give an insight on what plays staff enjoy. Also, creating a pivot table pulling out the data from successful outcomes with the highest number of backers could lead us to find a popular opinion of the audience to perform to. 
![image](https://user-images.githubusercontent.com/90981906/136711022-99131752-a82f-48dd-a125-b28580628073.png)
