# surfs_up

# Deliverable 3:

## Overview:

W. Avy wants information about temperature trends before opening his surf and ice-cream shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

## Results:

In order to extract the temperature data for the month of June, I wrote my code such that it would use the month '6' as a condition when retrieving the temperatures for June from the hawaii.sqlite dataset.  The June temperatures retrieved as follows:

<img width="534" alt="June temperatures" src="https://user-images.githubusercontent.com/95712234/165171642-4b491fa4-c538-43f5-8384-b2026d3ee22c.png">

Afterwards I ran my statistical analysis on the June temperatures. Here is what I gathered:

<img width="200" alt="June temp statistics" src="https://user-images.githubusercontent.com/95712234/165183003-87f1162c-ca16-4e71-863f-15fd14c17900.png">

According to the June temperature stats: 

#### *  The mean June temperature is 74.9°F, with a max of 85°F and min of 64°F. These numbers place Oahu in a favorable position for surfing and ice-cream        conditions.
#### *  The data was retrieved using 1700 data points over the span of 8 years and this was higher than the for December. It gives a balanced representation of the June temperatures in Oahu.
#### *  Standard deviation is 3.25 from the mean, which goes to say that the temperature results are pretty consistent. 

To retrieve the temperature data for December, I modified the previously mentioned code slightly.  This brought the following results:

<img width="510" alt="Dec temperatures" src="https://user-images.githubusercontent.com/95712234/165180627-cab06114-a9c9-4c65-be5c-79e9deec1db1.png">

Afterwards I ran my statistical analysis on the December temperatures. Here are the results: 

<img width="248" alt="Dec temp stats" src="https://user-images.githubusercontent.com/95712234/165181315-84fac870-2b9a-447a-8eef-3eb21474c448.png">

#### *  The mean December temperature is 71°F, with a max of 83°F and min of 56°F. This places Oahu in a favorable place for surfing and ice-cream conditions. This means that there isn't much fluctation between June and December dates.
#### *  The data was retrieved using 1517 data points over the span of 8 years. It gives a balanced representation of the December temperatures in Oahu.
#### *  Standard deviation is 3.74 from the mean, which goes to say that the temperature results are pretty consistent. Even in December, the temperature in Oahu is ideal for surfing and ice-cream!

## Summary:

W. Avy wants to learn further trends in Oahu's weather data patterns before opening his surf and ice-cream shop. I ran two additional queries, for June and December respectively, as those were the two months he was interested in. The two new queries focused on the precipitation measurements. I then ran a statistical analysis for both months.

#### Statistical analysis of June precipitation results:

<img width="202" alt="June Precipitation stats" src="https://user-images.githubusercontent.com/95712234/165218257-60423e7d-0cf9-46d9-aa61-2db200d74123.png">

##### * The mean amount of precipitation in June is 0.13 inches with an std deviation of 0.33, and this is great news for both surfing and ice-cream. 

#### Statistical analysis of December precipitation results:

<img width="241" alt="Dec Precipitation stats" src="https://user-images.githubusercontent.com/95712234/165218335-3ae8d44c-bb3e-42a7-b3f6-e61c60c6c815.png">

##### * The mean amount of precipitation in December is 0.13 inches with an std deviation of 0.54, which again is great news for the potential business to thrive. Although it seems to rain slighly more in December, nevertheless Oahu seems like an ideal spot for surfers. 

Based on all the queries for the temperature and precipitation measurements of the months of June and December, I believe W. Avy's business could thrive in a location such as Oahu where there is good weather year-round.

