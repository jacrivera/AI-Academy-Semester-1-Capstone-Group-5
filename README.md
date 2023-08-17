# AI-Academy-Semester-1-Capstone-Group-5


# Overview:



# Business Understanding:


# Data Understanding and Analysis:


## Source of Data:


## Description of data:


## Three visualizations:


# Statistical Communication:
Followinig our exploratory data analysis of profit percentage (total profit/production budget * 100) we found that the means of 5 genres seemingly were higher than the population mean, so we decided to run statistical testing to see if this change is significant. 
Because we are taking samples of the population (the 5 genres) and comparing it to the total population in our dataset (overall movies), we decided on running one tail t-tests to determine if these result were significant.

## Results:
Population Profit Average: 	397.5%
Horror Profit% Average: 	1233.1%  T-stat: 3.54 (p<0.001)	Confidence Interval: -100% - 7744.7% 
Mystery Profit% Average:	1047.7%  T-stat: 2.01 (p<0.05)	Confidence Interval: -100% - 8414.8%
Sport Profit% Average:		1093.1%  T-stat: 2.25 (p<0.05)	Confidence Interval: -100% - 5243.5% 
Thriller Profit% Average:	733.7%   T-stat: 2.27 (p<0.05)	Confidence Interval: -100% - 5855.7% 
Romance Profit% Average: 	566.8%   T-stat: 2.44 (p<0.05)	Confidence Interval: -100% - 2525.8%


## Interpretation:
Our null hypothesis for each test was that each genre's average profit percentage was less than or equal to the population mean.
Our alternate hypothesis for each test was that each genre's average profit percentage was greater than the population mean. 
In all of our statistical testing we found that the results were significant at an alpha threshold of 0.05. We settled on this alpha threshold to limit the amount of possible type I or type II errors that we could encounter.

These results allow us to reject our null hypothesis and say that these five genres have a significantly higher average profit percentage as compared to the general population of movies. 

The range in which we believe these true value of these genre's average profit percentage is listed in the above confidence intervals. 


# Conclusion: