# surfs_up
## Overview: Analyzing weather data to get more temperature information trends to open a surf and ice cream shop.

### The purpose of this project is to get temperature information trends to see if a surf and ice cream shop business is sustainable year-round.

## Analysis
- Before I could start my analysis, I needed to reflect the reflect the tables into SQLAlchemy ORM, and create references to save each table. Then I wanted to see what the most active stations are. There are nine active stations. Now that I have this information I want to determine the summary statistics for the month of June. 

- First, I want to write a query that filters the Measurement table to retrieve the temperatures for the month of June. Once I've gathered the temperatures, I needed to turn the information into a list to make running analysis go smoother. 

- Now that I have the temperatures in a list, I can create a DataFrame from that list of temperatures for the month of June. Once I create my DataFrame, I can then use the 'describe' function to get the summary statistics of the temperatures for the month of June. 

- Then I wanted to get the summary statistics for the month of December as well. Just like I did for the month of June, I first wrote a query that filters the Measurement table to retrieve the temperatures for the month of December. Then I converted the temperatures to a list so that I could make a DataFrame. Once I had my DataFrame for temperatures for the month of December, then I could use the 'describe' function to get the December temperature summary statistics.

[SurfsUp_Challenge]()

## Results
- two conclusions