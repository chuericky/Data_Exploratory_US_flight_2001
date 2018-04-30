# Data_Exploratory_US_flight_2001

This is a dataset for the delay record of all the commercial flights in the US in 2001.  There are a couple of interesting directions to explore in this dataset, especially the 9-11 incident has happened.

1. How had the delay time changed before and after the incident 
- As shown in the probability distribution function histogram, the delay time distribution after the incident is slightly more right skewed than that of before the incident.  However, a careful hypothesis testing is required to quantity the significance of difference.

2. Correlation analyses
- Is the arrival delay time correlated with days of week / year?  The boxplot of delay time versus day of week provides us some hints how has the arrival delay time vary with days of week.  It seems like the delay time is consistent throughout every day of the week, with 1-standard deviation around -10 to 10 minutes (Negative means earlier arrival).  In principle, we can repeat the same exercise for months throughout many years and at different locations.  In some areas such as Chicago, the delay time during the winter might be significantly larger than in the other seasons as the weather might prohibit flights to depart or arrive.  This requires further inspection.

- Correlation analyses can be done to see which features (taxi time, security check time, carrier check time, etc) could correlate strongly with flight delay time.  Also, the correlation analysis would be a good way to provide the passengers hints of which airport would they likely to encounter flight delays.

- Which pairs of airports (departure and arrival) would likely to have flight delay issues.

3. Time-series analysis
- Data sets from different years can be combined to explore interesting data patterns, such as if the delay time has been shortened because of the advance in aviation technology?  Or if it has become more serious because there is an increasing demand of flight travels?
