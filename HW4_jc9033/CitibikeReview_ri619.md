Analysis of Citibike Assignment by jc9033 (Junjie Cai)


Comments/Suggestions on Notebook:

   1. The Null hypothesis was stated correctly and in a way that clearly defines the problem that Junjie is hoping to answer. The Null states that the duration of trips under 10 minutes is the same or lower than the trips above 10 minutes. Additionally, the mathematical equation defines the hypothesis symbolically. However, *short* and *long* are not defined in the mathematical equation. They should be defined as values like such: *short* < 10 minutes and *long* > 10 minutes.

   2. The data needed to answer this hypothesis is only the trip duration. Since the hypothesis does not look to analyze differences between days of the week or times in the day, the only column that is absolutely necessary to keep is trip duration. From the notebook, it is clear that this is what has been done. 

       The hypothesis mentions trip durations using minutes as the measure, but the Citibike data instead uses seconds. While through all the plots, Junjie uses 600 seconds as the cutoff, this could prove to be confusing in later analysis. Either the hypothesis should be changed to mention 600 seconds, or the trip duration data should be converted to minutes. 

   3. What type of test to use....
	Since the trip duration data is numeric and we are only comparing two groups, short and long trips, the best test to use would be a t-test. A simple two sample t-test will be achievable since we can get the sample mean, standard deviation and the data should follow a normal distribution. 

   4. The current question asks about trip duration for every person, everyday of the week. I think a more insightful question might be to look into the trends during weekends and weekdays, or night vs. day. The weekend and weekday data could vary quite a bit as much the weekday data is work commute and weekend data can show different trends. 
	
      Unfortunately, the legend and bar colors dont match on some of the plots, so I can't really tell but it might be that the number of short trips significantly changes during the weekends. I would make sure the plot legend and bar colors match just so that answers extrapolated from the data are correct.


