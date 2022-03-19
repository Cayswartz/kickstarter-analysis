# kickstarter-analysis


# Kickstarting with Excel

## Overview of Project

Louise is a playwriter who wants to fundraise for a play named _Fever_. Not only is Louise a fanatastic playwriter but she has had an analytic savvy mind and wants to ensure she is using all the information available to help her play be successful. _Fever's_ budget is $10,000 and she wants to take a deeper dive into how similar campaigns performed specifically looking at what their funding goal was and what day they launched their campaign. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
When taking a closer look at launch date there is one month that stands above the rest and that month is May with the largest numver of successful campaigns while the failed campaigns stay in line with the number of failed campaign both the month prior and the month after. The months following May continue to perform higher well, though not as high as May itself. By August the number of approvals are back down to what they looked at prior to the May spike. Looking closely at failed campaigns we see a spike in October with 72 campaigns failures. Overall, I would suggest launching in May is possible. If this is not possible, the two months following May still saw higher success rates but whatever you do stay away from a October launch. 


### Analysis of Outcomes Based on Goals
When looking at data like this you may assume that as the goal gets larger we may see the sucess rate decrease however this is not the case. We did see the  highest sucess rate between 1000 to 4999 however after that we saw a drop of in success rate until we reached 35000-39999 and 40000 to 44999 where we saw a 67% succcess rate for both. The largest outlier displayed by the chart was a spike in failures from 45000 to 49999 with 100% failures. That being said, the total number of projects was only 1 which when looking at rates can paint a incorrect picture of where drops and increases are seen. A larger data set size could help better portray this or looking at the true number of increases and decreases instead of the rate.

### Challenges and Difficulties Encountered
I ran into some issues with developing the COUNTIFS statements. While the statements themselves are fairly straight forward I found myself making mistakes like only doing larger and smaller statements rather than larger or equal to. I overcame this by slowing down and paying close attention to each piece of the equation that I wrote. Once I was able to slow down instead of rushing through all the equations I needed to write I was able to start producing the correct numbers in the table. 

## Results

### What are two conclusions you can draw about the Outcomes based on Launch Date?
1. May saw the strongest performance in terms of successfully launched campaigns
2. October saw a large spike in failed campaigns with 50 failed campaigns.

### What can you conclude about the Outcomes based on Goals?
Looking at the outcomes based on goals we saw the highest sucess rate between 1000 to 4999 however 35000-39999 and 40000 to 44999 were close seconds with a 67% success rate for both.

### What are some limitations of this dataset?
I think this data set is fairly small and when breaking it down even more to campaigns that just occured in the United States it is cutting the number of rows down even further. We can see this throwing off the metrics and providing misleading chart results in the Outcomes based on goal.

### What are some other possible tables and/or graphs that we could create?
I believe that often in order to paint the full picture of a smaller data set like this you must include both the percentage and totals. While both metrics are useful when there are situations where there may only be one success or failure that can cause a rate seem like an outlier when really it is just so large cause of the smaller sample size. 

Additionally, we have YoY metrics available and I think that it could be interesting to take a look how months perform by year. Are the spikes that we are seeing caused by one year while the rest of the years a fairly stagnant? If that is the case, could there have been something that occured that year to cause the increase? Looking at the data year over year helps validate that these trends would be safe to use and make assumptions off of for the next year rather then assuming they properly represent trends when they might actually be thrown off by an anomoaly that occured one year.

I believe it would be interesting to take a look at the number of backers and the average amount donated by each backer to see if there are any trends that can be seen with that and the total goal.
