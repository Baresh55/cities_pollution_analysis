
1.	WHAT IS THE STATISTICAL SUMMARY OF AIR QUALITY AND WATER POLLUTION?

This required me to use the summary function and to run it separately for both air quality and water pollution. The objective being to establish the central tendency and spread of both data sets.

2.	WHAT CITIES HAVE AIR QUALITY ABOVE 99 AND WATER POLLUTION BELOW 1? 

To perform this analysis, I loaded the ‘dplyr’ package which contains the pipe function. Subsequently, I created a new data frame titled, ‘city pollution_v1’ from the city pollution data frame. At the end of the first command line, I applied the pipe operator so it to execute commands sequentially. I then filtered the new data frame to include only rows where air quality index is above 99 and water pollution index is below1. Lastly, to limit the output, I applied the view function.

3.	WHAT IS THE CORRELATION CO-EFFICIENT BETWEEN WATER POLLUTION AND AIR QUALITY?

To measure the strength and direction of the linear relationship between water pollution and air quality, I used the ‘cor’ function ensuring to reference the city pollution data frame. This was due to the existence of a different data frame with air quality and water pollution columns

4.	WHAT IS THE STANDARD DEVIATION OF AIR QUALITY AND OF WATER POLLUTION?

To establish the standard deviation for both air quality and water pollution, I run the ‘sd’ function on both metrics separately since I needed to know to what extent they both deviate from the mean

