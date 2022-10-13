# Kickstarting with Excel

## Overview of Project
Louise is about to launch a Kickstarter Fundraising campaign for her play Fever. There is a tremendous amount of data available from Kickstarter for various projects and different categories ranging from food and games to music and video. Each category has multiple subcategories as well and the data includes a lot of information from fundraising goal, outcome of the fundraising, date of the launch, and more. With all this data avaialble on excel, we are able to organize and deliver information to Louise so that she can understand how to best go about starting her fundraising campaing for her play. 

### Purpose
Because Louise is raising for a play, two important questions she must analyze are how fundraising outcomes for theater related projects were based on their launch date and the fundraising outcomes for plays based on their initial fundraising goal. We were able to use excel to create two easy to read charts that can assist Louise with knowing what amount of money she should try to raise so she can successfully complete fundraising along with letting her know the best time to launch to increase her likelihood of reaching her fundraising goals. 

## Analysis and Challenges
With over 4000 projects worth of fundraising data to analyze from, there is a tremendous amount of data that needs to be sorted and organized so that we can get Louise the two deliverables described above. Two challenges that needed to be addressed were filtering the data to analyze projects of the relevant category and also converting the Unix timestamps provided into a readable date format. Of the 4113 Fundraising Projects, 1369 of them were for theater related projects of which 1066 were for plays, the specific subcategory that pertains to Louise's project. After filtering for information in this category, an analysis can then be performed to see the outcome of each play fundraising project depending on how much their goal was. 

The initial data for the dates were provided in the difficult to read Unix timestamp so for us to deliver Louise with good information on when to launch her campaign, that data needed to be converted to a readable format. After converting the date timestamps, an easy to read pivot chart and line graph was created to show Louise the optimal time to launch a theater related fundraising campaign. 

### Analysis of Outcomes Based on Launch Date
After converting all of the data timestamps, we created a pivot chart to show all of the months projects have launched in and the outcome for that specific month (successful, failed, or canceled). Of the 1369 theater projects analyzed, 839 were successful while 493 failed, so over 60% of these projects reached their fundraising goals. When visualizing this data on a line chart, it is clear to see May and June are the best times to launch a campaign to optimize for success. Both months had 66% and 65% success rates, above the mean of the entire dataset, and they also contained the two highest absolute total of successful campaigns, 111 and 100 respectively. The changing of the seasons with Spring in full bloom into Summer are a great time for Louise to receive accommodating fundraising from others. The data and chart show as launches approach the late fall and end of the year, there is a huge reduction in the amount of successful launches and that the month of December should likely be avoided as the amount of successful projects is less than the amount of failed plus canceled projects. 

### Analysis of Outcomes Based on Goals
After sorting the fundrasing goals to different ranges, we are able to find the amount of successful, failed and canceled plays for each range. Once finding these data points, we calculated the percentage of of each in relation to the total amount of projects. The line chart shows that projects with less than $10,000 goals are much more likely to succeed, and up to $15,000 the chance of success is higher than failure. After the $15000 mark plays are more likely to fail their fundraising goals. From the $35,000 to $45,000 range we see the success rate pass the failure rate again, but it is important to note this data set is heavily skewed to the right and only 22 of the 1043 data points are in this range or greater. In the $50,000 or more range we see much more failures with the failure rate being 5x the success rate. 

### Challenges and Difficulties Encountered
The biggest challenge with this analysis was making sure that we are filtering the correct data and extrapolating the information correctly. If the data is not filtered correctly from the beginning, our analysis will be based on false pretenses. Various functions need to be used to pull information from one sheet onto another. With regards to the Outcomes Based on Goals analysis, we had to make sure the Count If function was pulling in information for the correct ranges, outcomes, and subcategory (plays) from another sheet. It is very easy to mismatch columns and categories which will give incorrect information. This incorrect information would then be a foundation for a false analysis which would likely do more harm than good for Louise. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
1) Louise should optimize for a May or June launch for her campaign to maximize her chance for success.
2) Louise should avoid the end of the year, where success numbers plummet heavily and approach failures.

- What can you conclude about the Outcomes based on Goals?
Louise should not try to raise more than $10000 for her play if she wants to optimize for a successful fundraise. If she can successfully run her project for under $5000, then her likelihood of successfully completing fundraising rises from 55% to 73%.

- What are some limitations of this dataset?
This data set is tremendously skewed to the right as most data points come from projects trying to raise less than $15000. Though it is important to understand what happened to more ambitious projects with higher fundraising targets, there should be more ranges under $15000, probably in $2500 or $1000 increments as that affects and pertains to Louise much more as she is trying to fundraise at most $10000. 

- What are some other possible tables and/or graphs that we could create?
If Louise knows what country she would like to fundraise in, we could filter both charts wtih regards to country. We could also create a barchart that shows the outcomes comparing the other subcategories of theater incase Louise wants to pivot from a play to a musical or a spaces. We could also do a line chart focusing on play outcomes by launchdate instead of just theater. 