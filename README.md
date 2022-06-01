# Kickstarting with Excel

## Overview of Project

### Purpose
	The purpose of this project is to assist our client, Louise, in launching a successful Kickstarter campaign for her play, "Fever". Louise has a goal of $10,000, which is the budget necessary to create her play. In preparation for her Kickstarter campaign we are analyzing data gathered from other theater campaigns, we studied the goals, pledges, outcomes, and launch dates to find what makes a successful kickstarter campaign. To accomplish this goal we used filters, pivot charts, line graphs, box plots, stacked column charts, and various formulas to help organize, analyze and visualize the data. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
	The chart titled ![Theater_Outcomes_vs_Launch](AJDelgadillo/Kickstarter_Analysis/blob/main/Theater_Outcomes_vs_Launch.png) gives insight on how the success of a kickstarter campaign relates to the launch date of the campaign. The data used for this chart was sourced from the kickstarter sheet and organized into a pivot chart with dates created in the rows category, Outcomes in the columns, and count of the outcomes in the values. The pivot chart can be filtered by parent category and year. 
	Using this chart we can determine in which month the greatest amount of successful kickstarter campaigns are produced. To make this more useful for Louise we used the filters to focus only on theater campaigns. 

### Analysis of Outcomes Based on Goals
	The chart titled ![Outcomes_vs_Goals](AJDelgadillo/Kickstarter_Analysis/blob/main/Outcomes_vs_Goals.png) analyzes the monetary goal of kickstarter campaigns in the subcategory “plays” and determines what percentage of these campaigns are successful, failed, or canceled.
	The data used for this chart was organized by using the COUNTIFS formula to count only the kickstarter campaigns fulfilling certain criteria of goal, subcategory, and outcome. These values were used to calculate the percentages of successful, failed, and canceled campaigns within those goals. 

### Challenges and Difficulties Encountered
	When working on this challenge I found that it is common to make very small mistakes such as misspelling titles, using the wrong formulas, and selecting incorrect cells when typing out a formula. This was especially difficult for me when using the =COUNTIFS formula for the chart "Outcomes_vs_Goals". I found difficulty making this graph because I needed to cluster multiple datasets and criteria in one formula. 
For these smaller mistakes I learned to be more careful and deliberate while working. With some practice this process became easier to manage. After successfully applying the formula once it was easier to replicate the same formula for several other criteria, while double checking to make sure I was using the formula correctly. 
	Secondly, I found some difficulty when creating pivot charts. When I first started on this challenge I didn't understand which field to categorize as the filters, columns, rows and values. This was another issue that was able to work through with some practice. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
	From this chart ![Theater_Outcomes_vs_Launch](AJDelgadillo/Kickstarter_Analysis/blob/main/Theater_Outcomes_vs_Launch.png) we are able to see that the greatest amount of successful theater kickstarter campaigns were created in May. I also noticed that May has the greatest amount of failed theater kickstarter campaigns, and the greatest amount of total campaigns as well. 
	From this I would conclude that May has the greatest amount of successful theater campaigns simply because more campaigns are started in May compared to the other months. I don’t believe this gives Louise any guarantee that her kickstarter campaign will be successful based on the month it is created in. We need to consider other factors that could influence the success of her project.

- What can you conclude about the Outcomes based on Goals?
	By analyzing this data ![Outcomes_vs_Goals](AJDelgadillo/Kickstarter_Analysis/blob/main/Outcomes_vs_Goals.png) and the resulting chart we can visualize what range of monetary goal has the greatest percentage of successful campaigns. This chart is suggesting that campaigns having a goal less than $1,000 are more likely to be successful than those having higher goals. Those campaigns having a goal between $1,000 and $4,999 have the second highest percentage of success.
	When looking at the graph we can see a positive correlation between the rising monetary goal and higher percentage of failed campaigns. It appears to show that as the goal increases, the campaign is less likely to successfully reach that goal.

- What are some limitations of this dataset?
	There are some factors that we can’t study from this dataset.
I would be interested in whether or not the projects resulting from the kickstarter campaigns were successful. This could tell us if the failed campaigns didn’t reach their goal due to a lack of public interest. I would also like to study how much advertisement the kickstarter campaign received. It is possible that some campaigns failed due to not having enough exposure. 

- What are some other possible tables and/or graphs that we could create?
	Using this dataset we could create a chart comparing the percentage funded vs. the amount of time the campaign was live. From this we could see if there is a correlation between how long the campaign was live and what percentage of the goal was reached. 
