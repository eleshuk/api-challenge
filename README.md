# api-challenge

# Conclusions at the bottom

**WeatherPy**
> Create a series of scatter plots to showcase the following relationships:
>> * Temperature (F) vs. Latitude
>> * Humidity (%) vs. Latitude
>> * Cloudiness (%) vs. Latitude
>> * Wind Speed (mph) vs. Latitude

After each plot add a sentence or too explaining what the code is and analyzing.

Run a linear regression on each relationship, only this time separating them into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):  

>> * Northern Hemisphere - Temperature (F) vs. Latitude
>> * Southern Hemisphere - Temperature (F) vs. Latitude
>> * Northern Hemisphere - Humidity (%) vs. Latitude
>> * Southern Hemisphere - Humidity (%) vs. Latitude
>> * Northern Hemisphere - Cloudiness (%) vs. Latitude
>> * Southern Hemisphere - Cloudiness (%) vs. Latitude
>> * Northern Hemisphere - Wind Speed (mph) vs. Latitude
>> * Southern Hemisphere - Wind Speed (mph) vs. Latitude

After each pair of plots explain what the linear regression is modeling such as any relationships you notice and any other analysis you may have.

**VacationPy**
Plan a future vacation.  
> * Create a heat map that displays the humidity for every city from the part I of the homework.
> * Narrow down the DataFrame to find your ideal weather condition. For example:

  >> * A max temperature lower than 80 degrees but higher than 70.
  >> * Wind speed less than 10 mph.
  >> * Zero cloudiness.
  >> * Drop any rows that don't contain all three conditions. You want to be sure the weather is ideal.  
  >> * Using Google Places API to find the first hotel for each city located within 5000 meters of your coordinates.  
>> * Plot the hotels on top of the humidity heatmap with each pin containing the **Hotel Name**, **City**, and **Country**.

# Conclusions

**General Conclusions**
>> * Temperature (F) vs. Latitude shows that on 11/24/2020 (Northern Hemisphere Winter/Southern Hemisphere Summer), the temperatures in the Southern Hemisphere are warmer, and the temperatures in the Northern Hemisphere are colder. 
>> * Humidity (%) vs. Latitude shows that the percent humidity across the world is pretty evenly distributed right now and that there are no major differences between humidity in the Northern and Southern Hemisphere. 
>> * Cloudiness (%) vs. Latitude is a mess and seems to show no distinct relation between cloudiness and latitutde. 
>> * Wind Speed (mph) vs. Latitude there seems to be weak to no correlation between wind speed and latitude. 

**Northern Hemisphere vs. Southern Hemisphere** 
>> * Northern Hemisphere - Temperature (F) vs. Latitude has a strong negative correlation. As one travels further north of the equator, maximum temperatures decrease, lower maximum temperatures are observed as it is winter.  
>> * Southern Hemisphere - Temperature (F) vs. Latitude has a moderate positive correlation indicating that as one travels closer to the equator, temperatures increase.  
>> * Northern Hemisphere - Humidity (%) vs. Latitude shows a weak positive correlation between percent humidity and latitude, indicating that it is possible that as one travels further north from the equator, one will observe a higher humidity percentage, but the prediction is not very reliable. 
>> * Southern Hemisphere - Humidity (%) vs. Latitude also shows a weak positive correlation, where as one travels closer to the equator, percent humidity increases.
>> * Northern Hemisphere - Cloudiness (%) vs. Latitude shows that, despite the messy graph, there is a moderate, positive correlation between cloudiness and latitude. As one travels further north of the equator, percent cloudiness increases.
>> * Southern Hemisphere - Cloudiness (%) vs. Latitude again looks a bit messy but shows a moderate to strong positive correlation between percent cloudiness and latitude. As one travels closer to the equator, cloudiness increases.
>> * Northern Hemisphere - Wind Speed (mph) vs. Latitude shows weak to no positive correlation between wind speed and latitude. 
>> * Southern Hemisphere - Wind Speed (mph) vs. Latitude shows a weak to moderate negative correlation between wind speed and latitude. This means that as one travels closer to the equator, wind speeds decrease.

**Set output_data file for image of hotels heatmap**
