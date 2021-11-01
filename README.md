# Kickstarting with Excel

## Overview of Project

### Purpose
Louise wants to start a crowdfunding campaign to fund a play and would like to determine how to successfully launch one with help.  This project is designed to take data collected about existing campaigns, organize that data, and determine what kinds of trends or factors can exist that would result in a successful campaign.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

![Theater_Outcomes_vs_Launch.png](https://github.com/mathur-nikita/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)

The lines for successful campaigns and failed campaigns for the most part seem to increase and decrease in slope at the same time per month, but not necessarily by the same amount.  There is an increase from January to April, with a noticeable increase for the month of May.  After that there is a decline in both the number of successful and failed campaigns until the month of October which shows a small increase.  

After this there's a slight deviation: for successful campaigns there's steady decline to the end of the year, while for failed campaigns there's a decrease in amount for November but a small increase towards December.  In December both the number of successful and failed campaigns seem to be about the same.

The number of canceled campaigns remains mostly steady throughout the year (less than 10) except for a break in the month of October.

### Analysis of Outcomes Based on Goals

![Outcomes_vs_Goals](https://github.com/mathur-nikita/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png)


For percentages of successful campaigns: As the ranges of the goals increase, the percentage of successfully funded campaigns tend to decrease. This is represented by the slope of the line being mostly negative (save for two points). 

For percentages of failed campaigns: As the ranges of the goals increase, the percentage of failed campaigns tend to increase.  This is represented by the slope of the line being mostly positive (save for two points). 

For percentages of canceled campaigns: This line has a slope of zero.  It remained at 0% consistently because a canceled campaign always results in zero funding, so that was represented as solid line along the x-axis.  

Something noticeable about this particular chart is its horizontal symmetry.  "Successful" and "failed" campaign outcomes will "mirror" each other around the median (50%) because there are only two values to add up to 100% at each range.


### Challenges and Difficulties Encountered
The most challenging thing I encountered throughout this project was actually making sense of the data that was being collected.  To an extent I understood how to produce certain results, but I wasn't always sure of why I was getting them and what they meant.  

## Results

What are two conclusions you can draw about the Outcomes based on Launch Date?

1) The highest amount of successful campaigns occurs for campaigns that are launched in the month of May, so it would seem if Louise were to also launch her campaign in May she would most likely run a successful crowdfunding campaign.  The highest amount of failed campaigns also occurs in May, but it's a much smaller amount total.

2) In December the amount of successful campaigns and failed campaigns are almost the same, so it would seem if Louise were to also launch her campaign in December she'd have a 50-50 chance at running a successful crowdfunding campaign.

What can you conclude about the Outcomes based on Goals?

1) The line representing the percentage of successful campaigns decreases as the goals increase, so it would seem that patrons are more likely to pledge for campaigns that are cheap (have really small financial goals).

2) It seems that most patrons are willing to pledge for campaigns that have up to a funding goal of 20000, as indicated by the sharp decline of successful campaigns at the "20000 - 24999" range overtaken by the sharp increase of failed campaigns at the same range.  

What are some limitations of this dataset?

1) There is some missing information.  In the "Outcomes Based on Launch Date" line graph you can see that the line for canceled campaigns breaks for the month of October, and that is also confirmed by looking at the table corresponding to this chart.  We would need to collect that data for completion.

2) There are some outliers.  In the "Outcomes Based on Goals" line graph there is a spike in successful campaigns at the "35000 - 39999" range which continues through to the "40000 - 44999" range. When looking at the table associated with this chart for both of the aforementioned ranges, it can be seen that the total number of campaigns for each range is small but the number of successful campaigns is twice the number of failed campaigns.  If this spike didn't exist we'd most likely see a steady decline in successful campaigns as the ranges increase.  

What are some other possible tables and/or graphs that we could create?

We have the start and end dates of all campaigns provided, but no calculations were done to record the number of days the campaigns lasted.  It might be a good idea to include this information in our analysis so we have an idea of how long Louise should run her campaign to maximize chances of success.  If it's too short it may not reach enough potential pledgers in time, but if it's too long any existing pledgers might lose interest or assume that their pledges aren't enough to fund the campaign and withdraw support.  An additional table/graph of outcomes could be created called "Outcomes Based on Campaign Duration".  Along the x-axis would be different campaign durations by week, on the y-axis there would be percentages, and there would 3 different lines to represent each type of campaign outcome (successful, failed, canceled).  
