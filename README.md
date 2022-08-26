# surfs_up
## Purpose
The purpose of this analysis was to determine if weather would be a major problem for a potential surf and ice cream shop in Oahu, Hawaii. The investor wanted an anlysis the showed the precipitation and temperatures for the location for a year. To further assist the investor, the analysis also looks at the tempertures of June and December to determine if the weather is comparable.
This analysis was done using a sqlite database, "hawaii.sqlite". The datebase was imported to Jupyter Notebook to open and conduct queries to determine the needed weather patterns.To execute this analysis the following tools were used:
- Sqlite
- Sqlalchemy
- Flask
- Jupytier Notebook
- Python

## Results
the analysis done return temperatures for the months of June and December. 
Here are 3 key differences between the two months queried:
- The month of June had almost 200 more counts than the month of December. 
- The mininum read for June was 8 degrees higher than the minimum for December. 
- The month of June has more warmer days than the month of December.

![june_temp_stats](https://user-images.githubusercontent.com/105830665/186796298-ec662dc9-b9df-4053-a8b3-a262f2f0a468.png)

![dec_temps_stats](https://user-images.githubusercontent.com/105830665/186796005-8cdb341b-c674-4a39-b498-1ae5d185b28b.png)

## Summary
The results show the differences between the months queried. What the results also reveal
is that the temperatures are steady througout the year. 

Since the analysis revealed that temperatures can run a close range for the two months, here are 2 more queries that can be ran to help determine the weather for the surf shop 
could be:
1. Run the average temperstures for each year for June and December to establish temperature trends.
2. compare the daily temperatures to the precipitation for June and December to determine how often it rains a certain tempatures.
These additional analysis will help know the weather trends. 