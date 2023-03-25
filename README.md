# Zip Code Analysis

Summary

1. Merge and analyze two different publicly available data sets containing zip code information.
2. Determine states with most zip codes as well as which zip codes are most Northern, Eastern, and Western.
3. Analyze population density by zip code after removing duplicate zip code - state pairings.
4. Perform statistical analysis to compare distribution of zip codes at the 3-digit and 5-digit level.


### Exploratory Data Analysis:

![image](https://github.com/Richard-Shimada/US-Zip-Code-Analysis/blob/main/Data/boxplots.png)

1. As expected, there is a higher mean population for 3-digit zips as they are a combination of many different 5-digit zip codes. On average, there are 37 5-digit zip codes per 3-digit zip (32,972/891).

2. In both cases, outliers are skewed towards higher values but that is due to nature of the data with the floor of an observation value being 0. There are more outliers on the 5-digit zip plot but also more observations. 

3. 5-digit zip populations are more positively skewed as the median is comparatively closer to the bottom of the IQR. 

4. There is a wider range of population values at the 3-digit zip level as the whiskers are longer than the ones for the 5-digit plot. </br></br>



![image](https://github.com/Richard-Shimada/US-Zip-Code-Analysis/blob/main/Data/lmplot.png)


Generally speaking, it is assumed that there would be a positive relationship between population size and the number of housing units needed. </br></br>This is confirmed by the above plot.
