# Kickstarting with Excel

## Overview of Project
- Louise's play Fever was almost able to achieve her fundraising goals within a short period of time. 
She therefore wants to understand how different campaings fared in relation to the date they were lunched.

### Purpose
- To visualize campaign outcomes based on their lunch dates and their funding goals

## Analysis and Challenges
- To perform this analysis, I used the kickstarter data provided. I converted the unix timestamped launched_at information into a human date, Adeded the column years and brokedown the category and subcategory into a parent and child  columns.For the theater outcomes by lunch date, I created a pivot table with the data in Kickstarted worksheet and filtered by the parent category to theater, assigned the various columns, rows and values their respective parameters.Filtered the outcomes to see the trends for successful, failed and canceled outcomes.
For the outcomes based on Goals, I had yto use the COUNTIF formula to generate the number of successful,failed and canceled projects find their percentage and plotted a line chart using the information on the goals against their respective percentages. The challanges I encounted was using the COUNTIF formula but watching various utube videos helped me to overcome that challenge.   

### Analysis of Outcomes Based on Launch Date
- For the successful outcomes, the observations saw an increase in successful fundraised between january and February, march fundraised dropped but march to may saw a raise in the peaking in june.There was a decline in successful fundraised between May to december with december being the worst performaing month eventhough about the same number of campaings both succeded and failed. The failed campaings also followed a similar trend as the successful campaingns witht eh month of may being the month with the most failure. By comparing those two graphs, one can observe a very wide gab between Successful and failed outcomes for the month of May which shows as compared to the other months.This still shows tha the month of May is the best month to campaing for funds follwoed by June and July.Also the chart shows that in all months fewer campaings got canceled while between september and November, none was cancelled.
![image_Theater_Outcomes_vs_Launch]("D:\WASHU DATA Analytics\WUSTL-VIRT-DATA-PT-08-2022-U-B-main\01-Excel\Module 1 Challenge\Resources\Theater_Outcomes_vs_Launch.png")
 
### Analysis of Outcomes Based on Goals
- Outcomes based on goals showed that for campaings with goles of $4999 were the most successful with over 70% success rate.Campaings with goals in the range of 45000 to $49999 were the least successful. Also Campaings with the goals in the range of $15000 to $19999 have a 50% chance of success.
![image_Outcomes_vs_Goals]("D:\WASHU DATA Analytics\WUSTL-VIRT-DATA-PT-08-2022-U-B-main\01-Excel\Module 1 Challenge\Resources\Outcomes_vs_Goals.png")

### Challenges and Difficulties Encountered
- The challanges I encounted was using the COUNTIF formula for outcome based on goals but watching various you tube videos helped me to overcome that challenge. Knowing what information to put in teh columns and rows within the pivot table was confusing but since that information immeditly shows on the pivot table helped me to know what right looks like.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
1. Campaings lunched between May and June are the most successful
2. A total of 839 campaings succeded as against 493,

- What can you conclude about the Outcomes based on Goals?
1. Goals below $4999 has the most rate of success.
2. The is a 50% rate of success if the goal is between $15000 and $19999 

- What are some limitations of this dataset?
There was an outlier in the dataset that has the ability to skew the data.

- What are some other possible tables and/or graphs that we could create?
1. Successful outcome v Country chart to find out which countries have the highes rate of success in fundraiser campaings
2. Impact of duration on the success or failure of a campaing.



