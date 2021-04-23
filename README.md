# Kickstarting with Excel

## Overview of Project

### The purpose of this project is to compare how Louise’s kickstarter for her play “Fever” did in relation to other similar campaigns. Additionally, the analysis provides context and potential reasons for why her campaign did better or worse compared to the others. Specifically, the analysis examines launch dates and campaign goals to see if patterns emerge as to why some campaigns are more successful than others. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

#### This analysis compares successful, failed, and canceled campaigns over time to see if there are any patterns or times of year that campaigns do better than others. To do this, I filtered to only show theater campaigns and created a line chart that had the months on the x-axis, number of campaigns on the y-axis, and three lines showing the successful, failed, and canceled campaigns. ![Theater_Outcomes_vs_Launch] (https://github.com/awolfe95/Kickstarter-Analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png). 

### Analysis of Outcomes Based on Goals

#### This analysis compares the outcomes of campaigns based on their fundraising goal to see if there are patterns related to how low or high a campaign's goal is and its outcome. I did this by creating goal ranges and then finding the number of campaigns that matched the criteria I was looking for (i.e. outcome, goal range, plays). I then determined the total projects for each goal range and used that to find a percentage successful, failed, and canceled for each goal range. Finally, I transformed this data into a line chart, with the goal range on the x-axis, percentage on the y-axis, and the campaign outcomes as three lines. ![Outcomes_vs_Goals] (https://github.com/awolfe95/Kickstarter-Analysis/blob/main/Resources/Outcomes_vs_Goals.png).

### Challenges and Difficulties Encountered

#### The main challenge I had with this project was mainly with the second analysis “Outcomes Based on Goal.” It took some time to figure out the best way to execute the “countifs” equation to properly calculate how many campaigns accurately fell into the defined parameters. To overcome this challenge, I used the additional resources provided to me in the module and challenge explaining the formula, tested my formulas, and then validated the results I got by manually checking a couple of the outputs. 

## Results

### One conclusion from the “Outcomes Based on Launch Date” analysis, is that a lot of the successful campaigns are launched in the early summer months, specifically with a significant spike seen in May. Additionally, December appears to be the worst month to launch a play as it has the least number of successful campaigns. There doesn’t seem to be a specific pattern with regards to canceled campaigns and the months of the year.  

### One conclusion from the “Outcomes Based on Goals” analysis is that campaigns with goals $45,000 and higher are much less successful than campaigns with lower goal amounts. 

### One limitation of the dataset is that there isn’t a variable or way of knowing the amount or kind of advertising each campaign did. I’d think that the amount and type of advertising would have a large impact on the success of these campaigns, because those determine who and how many people and potential donors see and know about the campaign. Another limitation is that the data doesn’t further sub-divide the categories of campaigns, such as dividing plays into different genres like drama or comedy. The data is good for very broad insights but doesn’t completely capture some of the nuances that could be affecting the outcomes of these campaigns. 

### Another graph we could’ve created would be a bar chart comparing percent of successful campaigns by country so that our client could also have that context when looking at the other charts we provided. Additionally, we could’ve created a column in the data to calculate time in-between launch date and the deadline date to understand if there’s a pattern between the length of time that a campaign is live and the outcomes of those campaigns. 
