### Surfs_Up!
## Modulle 9 Challenge

## Overview of the analysis: 
# Explanation of the purpose of this analysis

A friend, W. Avy, has asked that we conduct and analysis in order to determine the viability of opening up a Surf and Shake shop which will market surfing gear and ice cream in Hawaii. 
He likes a previously conducted analysis based on climate data in which rainfall and some temperature trends were described. However, before opening the surf shop, information about temperature trends were further analyzed using SQLite and SQLAlchemy local database query tools.   Specifically, temperature data for the months of June and December in Oahu, were extracted and analyzed to determine if the surf and ice cream shop business is sustainable year-round.

## Results:

Summary tables for the comparison of the statistical description of Temperature data for Oahu for the months of June and December is shown in the following figure

!https://github.com/AnaMMoreira/surfs_up/blob/main/June_vs_Dec.png

	* It can be observed that the Mean Temperatures differ by only 4 degrees between June and December.  This suggests that there isn't an extreme change in temperature between Summer months and Winter months in Oahu

	*  Although there is about a 200 datapoint difference the overall standard deviations are fairly close further demonstrating the temperatures do not sway very much about the mean and the time of year. 

	*  The lowest or minimum temperatures are a bit more different between the 2 months and could possibly impact sales specifically in December, with a temperature of 56 degrees.

	*  The percentiles indicate that although the lowest temperatures may indicate that possibly December may not do so well in ice cream sales it can be seen that only 25% of the time the temperatures are below 71 degrees.  This is not very different from June temperatures of 73 degrees.  Furthermore, the temperatures are overall in the low to mid 70's for both months for 50% of the time yet still below 80 degrees for 75% of the time.

	*  Lastly, maximum temperatures, are 85 and 83 degrees respectively for the months of June and December.  Further demonstrating that the seasonal variation in temperature is not as extreme as for example New York or other states, making Oahu a good place for this type of shop.

## Summary: 

In conclusion, the seasonal variation in temperature in Oahu is most likely not going to affect sales for both surfing gear and ice cream.  The mild temperatures are supportive of activities such as surfing and eating ice cream and would therefore indicate a successful business venture.  It would be interesting however to make sure that this analysis is comparing two good representing months so looking at the stats of all 12 months in order to determine which month might contain the lowest temperatures and/or find an average-month statistics might be helpful.  Another analysis might look at hourly data on a seasonal basis and compare them to open business hours and/or beach access hours.



