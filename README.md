# An Analysis of Kickstarter Campaigns
Given multifaceted data on thousands of theatrical projects, analysis on multiple variables was performed to highlight different trends in order to help Louise make decisions on starting her own project. 

Louise stated that she is interested specifically in starting a theatrical play in the U.S. So, naturally, we'll first analyze how theater projects do compared to other categories of projects. 
![U.S. Based Project Outcomes](https://github.com/critter110/Kickstarter-analysis/blob/master/parent%20category%20real.png)
We can see from the farthest right bar, theatrical projects is the largest category. Investigating further, there are more successful projects than failed projects in the theater category. This is good news for Louise!

Next, we'll dive deeper, and explore exactly which types of theatrical projects are the most successful. Remember Louise is interested in doing a play.
![Subcategory Outcomes](https://github.com/critter110/Kickstarter-analysis/blob/master/Subcategory%20statistics.png)
Again, the subcategory that Louise is interested in has by far the most data points. The more data we have, the better the analysis we can give Louise. This time it's more good news! Over half of the plays are successful in the U.S.

Now we'll look at the dates that the theater kickstarter projects were started to see if they play any meaningful role in the success of the project.
![Outcomes Based on Dates](https://github.com/critter110/Kickstarter-analysis/blob/master/Outcomes%20based%20on%20dates.png)
There is a small bump in successful campaigns in February, but a massive spike in successful campaigns around the month of May. In general, we would recommend that Louise start her campaign in the summer time. As you get closer to Fall and Winter, the success rate of the campaigns declines. We advise Louise to avoid starting her campaign in the Winter. 

Another important aspect to look into is the goal fundraising amount and the actual amount pledged for successful and failed campaigns. This will give Louise an idea of how much money to ask for on Kickstarter. The mean and median of the fundraising goals and the amount pledged for successful and failed campaigns are tabulated below.

|           |Successful |	Failed 
|-----------|-----------|----------
|Mean Goal	|$5,048.88	|$10,554.21
|Median Goal|	$3,000.00	|$5,000.00

|           |Successful | Failed
|-----------|-----------|----------
|Mean Pledged| $5,601.55|	$558.65
|Median Pledged|	$3,167.50|	$103.00

In general, the campaigns that fail ask for almost double the amount of money that successful campaigns ask for. We would advise Louise to be conservative with her Kickstarter fundraising goals.  

Finally, Louise mentioned that she was specifically interested in the fundraising statistics of the musicals in Great Britain. Below we have a box and whisker chart for British musicals. The shaded box region represents the area between the upper and lower quartile of the data sets. The x in the box represents the mean, and the line in the box represents the median. 
![GB Box and Whisker chart](https://github.com/critter110/Kickstarter-analysis/blob/master/GreatBritain%20Musical%20statistics.png)
Here it becomes even more evident that the fundraising goals are often times a lot larger than the amount that will actually get pledged. Again, we can take from this that Louise should be conservative with her fundraising expectations and financial planning. 

### Challenge
In this challenge we were tasked with finding the number of successful, failed, and canceled theater plays, and comparing them to the goal fundraising amount. To do this, we created bins of goal amounts, less than $1000, $1000 to $4999, $5000 to $9999, etc. up to Greater than $50,000. Then, using the COUNTIFS() function, we tallied up the number of successful, failed, and canceled projects that fell into each bin. We then added up the total number of projects in each bin, and calculated the percentages for successful, failed, and canceled projects. Finally, we took these percentages and created a line chart to visualize the data.
![Percentage of Success](https://github.com/critter110/Kickstarter-analysis/blob/master/Percentage%20of%20success.png)
We can see from the chart that the highest percentage of successful projects come from the lower goal bins. In other words, the plays that ask for the least amount of money have the highest chance of being successful. As the goal amount gets higher, the successful percentage drops and the failed percentage rises. 

The second part of the weekly challenge was a repeat of an excersize in the module. The pivot chart and analysis of Theater outcomes based on launch date can be seen above. 
