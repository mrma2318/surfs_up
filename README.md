# surfs_up
## Overview: Analyzing weather data to get more temperature information trends to open a surf and ice cream shop.

### The purpose of this project is to get temperature information trends to see if a surf and ice cream shop business is sustainable year-round.

## Analysis
### June Summary Statistics
- Before I could start my analysis, I needed to reflect the reflect the tables into SQLAlchemy ORM, and create references to save each table. Then I wanted to see what the most active stations are. There are nine active stations. Now that I have this information I want to determine the summary statistics for the month of June. 

- First, I want to write a query that filters the Measurement table to retrieve the temperatures for the month of June. Once I've gathered the temperatures, I needed to turn the information into a list to make running analysis go smoother. 

- Now that I have the temperatures in a list, I can create a DataFrame from that list of temperatures for the month of June. Once I create my DataFrame, I can then use the 'describe' function to get the summary statistics of the temperatures for the month of June, Table 1.

#### Table 1: June Summary Statistics

![June Summary Statistics](https://github.com/mrma2318/surfs_up/blob/552e3e587c17d2823acd5f8a8213d0cff07ddf05/june_temp_summary.png)

### December Summary Statistics
- Then I wanted to get the summary statistics for the month of December as well. Just like I did for the month of June, I first wrote a query that filters the Measurement table to retrieve the temperatures for the month of December. Then I converted the temperatures to a list so that I could make a DataFrame. Once I had my DataFrame for temperatures for the month of December, then I could use the 'describe' function to get the December temperature summary statistics.

#### Table 2: December Summary Statistics

![December Summary Statistics](https://github.com/mrma2318/surfs_up/blob/552e3e587c17d2823acd5f8a8213d0cff07ddf05/dec_temp_summary.png)

[SurfsUp_Challenge](https://github.com/mrma2318/surfs_up/blob/36e496dd30e85c23d2d2534eae170cce86401708/SurfsUp_Challenge.ipynb)

## Results
- There are three major points we can draw from the two deliverables. The first point, is that before we could get the summary statistics for the months of June and December is that we needed to convert the month temperatures into a list so that we could create a DataFrame. 

- The second point is that on average, the temperatures in June gets around 75 degrees. 

![June Summary Statistics](https://github.com/mrma2318/surfs_up/blob/552e3e587c17d2823acd5f8a8213d0cff07ddf05/june_temp_summary.png)

- Where the average temperatures in December gets around 71 degrees. 

![December Summary Statistics](https://github.com/mrma2318/surfs_up/blob/552e3e587c17d2823acd5f8a8213d0cff07ddf05/dec_temp_summary.png)


- Therefore, the third point is that between the months of June and December the temperatures are fairly close. However, it does get slightly colder at times in December with a minimum temperature of 56 degrees, whereas June has a minimum temperature of 64 degrees. 

## Summary
- To conclude, the maximum temperatures for June and Decemeber are around the same temperature. However, June has a higher minimum temperature compared to December. The minimum temperatures in December get as low as 56 degrees, the average temperature get's around 71 degrees. Therefore, when deciding to open the surf and ice cream shop, so summer months might be a better fit. 
- There are two additional queries we could preform though to gather more weather data for June and December. The first one is to look at all 9 stations individually instead of just the overall temperature observations. Just because one station has more observations than others, doesn't mean it's the best station to open the surf and ice cream shop. By looking at all the stations we can look at more weather statistics for a more specific and best fit for the shop. By looking at the individual weather stations we can find the best fit to open the surf and ice cream shop for year round.
- The second query we could perform is to look at the precipitation information for June and December. We want to make sure that the place we open our surf and ice cream shop not only has high temperatures for June and December, but also has low preceipitation. 