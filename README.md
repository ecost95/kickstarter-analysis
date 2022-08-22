# An Analysis of Kickstarter Campaigns
# Kickstarting with Excel

## Overview of Project
This project will look at data from several Kickstarter campaigns to analyze trends about the success of crowdsourcing campaigns, with specific focus on campaigns related to theatre projects in the US. 
### Purpose
Louise is a playwright who would like to start a crowdfunding campaign to fund her new play, Fever. Louise estimates that she will need to raise $10,000. This project will determine the factors that will help Louise reach her desired fundraising goal.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
First, we looked at the funding outcomes of all 1,369 theatre-related Kickstarters based on the month that those campaigns were created. We described "outcomes" as either successful (campaign met funding goal), failed (campaign did not meet goal), or canceled (campaign was taken offline before goal was met). We created a pivot-table to give us the count of our all Kickstarter outcomes in our dataset per month, and filtered those results to only show the "theatre" campaigns. Next, we created a pivot chart to visualize the results:

### Analysis of Outcomes Based on Goals
Next, we looked at the outcomes of all theatre-related Kickstarters based on their stated fundraising goal. To group the Kickstarter goals, we created 12 categories, ranging from less than $1000 to more than $50,000. Next, we used the COUNTIFS function to find the nmber of successful, failed, and canceled campaigns in the "plays" subcategory based on their goal amount. We converted these counts into percentages and created a line graph to visualize the results:



### Challenges and Difficulties Encountered

## Results

What are two conclusions you can draw about the Outcomes based on Launch Date?
- There seems to be a spike in the number of successful theatre campaigns between April-May. We would suggest launching a kickstarter campaign during these months to maximize result.

- Avoid launching in November or December. There was an increase of failed campaigns and a decrease in successful campaigns.

What can you conclude about the Outcomes based on Goals?

- For plays, Kickstarters with a fundraising goal of $10,000 were only successful 54% of the time. Kickstarters in the next category down ($5,000-9$999) were successful 73% of the time, so Louise may want to ask for less money. 

- However, there was a increase in the percentage of successful campaigns with a goal between $30,000-$44,999, before a steep drop-off after $45,000. Louise might want to look closely at these successful campaigns to see if there are any similarities with her project.

What are some limitations of this dataset?

- It would be helpful to have more information about each project so we can determine whether or not their fundraising goals are realistic. Besides the category/subcategory for each Kickstarter, it would help to collect data more specific data about the projects' location (city, state) and whether rewards were offered for donating a certain amount.

What are some other possible tables and/or graphs that we could create?

-"Outcomes Based on Length of Campaign" table and line graph. Similar to the "Outcomes based on Goals" chart, we could create categories for how long each campaign was open (betweem 1 month - 2 years) based on their launch dates and end dates. This would help Louise find the length of the average theatre Kickstarter, and help her determine how long she should plan to fundraise. 
