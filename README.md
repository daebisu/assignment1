# assignment1 - New York City Illegal Fireworks

## Urban Data Mapping - 2022 

### David Chang

**Map analysis**

By simply looking at the depth of color in the maps, we can see there's a close correlation between the number of
illegal fireworks and the 311 complaints in the zipcode. We have to make sure to be careful with compairing 
values to the 311 complaints map because it does not only consist of firework complaints, but other complaints as
well. I can generalize these areas with more complaints to be less regulated than other lighter colored areas.


**Trends**

Illegal fireworks make up a large amount of 311 complaints in the upper west side area of Manhattan. This can be
seen through the high percent of illegal fireworks from 311 complaints in the area along with the relative 
increased number of illegal fireworks in general. Given that there are more 311 complaints in the area in general,
we can say this area has a big illegal fireworks issue.

Staten Island has a relatively lower amount of 311 complaints, but there is a higher % value of these being illegal
fireworks. This shows there's relatively less other complaints relative to illegal fireworks.


**Improvements and Insights**

Using the Quantile classification for % 311 complaints being fireworks loses accuracy towards the top end.
It groups 4% values all the way up to 50% values together in one color. While compared to other data percentage
values, it is relatively high, the range of which this is categorized is too large. You wouldn't know if a value
is 4% or 49%. I would improve the map by spliting the values into at least 3 more categories. This would more
clearly convey how large the values are.

Additionally, the maps would be more insightful if there were more connections between the actual numerical values
and the percentage values. At the moment, the percent fireworks map is heavily weighted towards lower percentages.
The color scheme makes it seem it has more firework complaints than a place actually has, when in reality, the 
percentage value is actually low (<20%).
