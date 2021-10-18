# An Analysis of Kickstarter Campaigns
Performing analysis on Kickstarter data to uncover trends.


# Kickstarting with Excel

## Overview of Project
Louise's play, Fever, is in the early stages of production. She had a fundraising goal, but the pledged money fell just short of that goal. What does this mean for her?

### Purpose
The purpose of this project is to support Louise for her play, Fever. To support her we combed through data of past theatrical productions and looked at any trends we could find, and what those trends meant for Fever.

## Analysis and Challenges
The analysis consisted of two main parts. Louise has data on Fever for fundraising goal and pledged amount. She also may know or may be looking to change what month the play will begin. So first, we looked at the outcomes based on launch date. Second, we looked at outcomes based on goals. In the context of the project, outcomes refers to if the play succeeded, failed, or was canceled. Due to previous experience with excel and mathematics, there were not too many challenges on this project. The two most difficult excel features were the texts to columns feature and the formulas for outcomes based on goals. They were not hard to figure out, but if one small bracket, apostraphe, or dollar sign was missing it affected multiple points of data. We overcame this by meticulously checking the formulas before applying them to other cells.


### Analysis of Outcomes Based on Launch Date
To analyze the outcomes based on launch date, we created a pivot table and line graph. We filtered out the type of production so that we are only looking at theatrical productions. We also sorted the data by partitioning all of the theatrical productions into the twelve months. Then we partitioned each month into successful, failed, and canceled producions. Based on the data post-filtered, we can draw a few theories. The best month to launch the play seems to be May. In May, we have the peak of successful plays for the year (111). Although the number of failed plays is also the highest of the other months (52), it has the lowest share of failed plays when compared to the total for the month (52/166 = 31.33%). This percentage is more important than just the gross total of failures because of the immense amount of plays produced in the month. We should also note that the percentage of successful plays in May is also the highest share of any month (111/166 = 66.87%). Using similar logic, December is likley the worst month for a play to release (49.33% success rate and 46.67% fail rate). We recommend Louise begin her play in the late spring or early summer months, which May being the best month and June a close second.


### Analysis of Outcomes Based on Goals
When also analyzed outcomes based on different goals. This time we partitioned the goal amounts into sections of about $5000. Our initial thoughts were that the graph looked strange the way it goes up and down when at $25,000 or higher. We expected to see more of a trend, but I think that the outcomes in those ranges should be taken with a grain of salt due to the small sample size (all are 12 or less). For the amounts under that, we see a strong linear trend where the higher the goal, the less successful the plays are. From this data we think that Louise should keep her goal low and it will hopefully give her a better chance at succeeding.

## Limitations and Lurking Variables
The data we have gives Louise a good idea of what can help her play succeed, but it is not everything. A particular lurking variable that comes to mind is a binary variable signifying if a play is centered around a season. The results by launch date showed us that plays in the winter seemed less successful, but we think that plays centered around the holidays may skew the data for other plays at the time. For example, someone may be more inclined to see 'A Christmas Story', than a popular play non-centered around Christmas like 'The Mousetrap'. This works both ways as well. Convential wisdom implies that a play centered around Hanukkah will be more successful in December, statistically the least successful month for plays, than in May, statistically the most successful month for plays. We also think that looking at exactly how successful the plays are with quantitative data could have a stronger correlation than using the qualitative data of success versus failure. I would recommend to Louise to do the exact same two analysis, except the outcome vairable would be determined by either profit, or attendance. Those variables were not included on the sheet but should not be impossible to obtain. As for extra graphs, I would reccomend a stacked bar graph to show the share of outcomes to the total as described in the outcomes based on launch date analysis.
