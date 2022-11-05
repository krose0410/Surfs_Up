# Surfs_up
## Overview
The purpose of this analysis was to determine summary statistics for temperature and precipitation on the island of Oahu in Hawaii using Python and SQLite in order to determine if a surf and ice cream shop business is sustainable year-round. More specific summary statistics were then filtered and found for the months of June and December.

## Results
- The average temperature during the month of June is ~75 degrees fahrenheit with a minimum of 64 and a maximum of 85 degrees.
<img width="149" alt="June Temps" src="https://user-images.githubusercontent.com/109715441/200142772-060e7ccd-da8d-4974-8593-cb1079e48e7f.png">

- The average temperature during the month of December is ~71 degrees fahrenheit with a minimum of 56 and a maximum of 83 degrees.
<img width="179" alt="December Temps" src="https://user-images.githubusercontent.com/109715441/200143043-e85edcdf-5287-4192-90db-c1d19f15d581.png">

- The standard deviation is relatively low for both the month of June and December at only ~3.5 degrees fahrenheit.

## Summary
Given that the standard deviation for both the month of June and December is only ~3.5 degrees fahrenheit, it is likely that a surf and ice cream shop business can operate successfully year-round, with just a few scattered days during the winter months likely to see less business due to colder days.

Additionally, the average amount of precipitation per month is both relatively stable and low at around ~0.15in. Seen in the figure below, precipitation is higher during the later parts of the year, but the change is only about ~0.05in.
<img width="642" alt="Average Percipitation" src="https://user-images.githubusercontent.com/109715441/200143240-3fb84d15-0705-4406-8613-4d41b3244984.png">

Lastly, it should be noted that the standard deviation for precipitation during the months of June and December are higher than those for temperature, with standard deviations of 0.33in and 0.54in respectively. This follows the large difference between the minimum and maximum and even the large difference between the 75% percentile and the maximum. Where the 75% percentile for June and December are 0.12in and 0.15in respectively, the maximum precipitation values for these months are 4.43in and 6.42in.
