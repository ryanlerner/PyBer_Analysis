# PyBer Analysis

## Overview 
The purpose of this analysis was to compare and contrast PyBer fare data between urban, suburban, and rural locations. In order to tell the full story, we needed to separate the data by the "city type" and calculate the total fares for each city type, as well as the average fare per ride and the average fare per driver. This analysis should assist V. Isualize on how to properly adjust their metrics to account for the differences in city-types. 

## Results
As shown in the below dataframe, there are numerous differences between the various city types. The urban cities have significantly more total drivers and rides than the rural and suburban areas. We can generally see that how populated a city is affects the total number number of rides, which creates a higher demand for total drivers, and subsequently increases total fares. Even though these sum statistics increase for more urbanized areas, the average fare per ride and average fare per driver decreases for these areas. This would likely be explained by the fact that there are fewer drivers in rural areas. Even though there may be a lower total demand in rural places, the average fare would increase because there is simply a lower supply as well, and possibly less competition from other transporation options. More urbanized areas will often have trains and buses, while rural and suburban places would not be as easily able to rely on public transportation. 

![analysis/pyber_summary](analysis/pyber_summary.png)

The multiple-line chart below shows the differences in total fare by city type over the span of five months. We can see that urban cities have the highest total fare, and that the trends for total fare per week remain relatively similar for all three of these lines. However, there are spikes just before March for all three city types, as well as a big increase in the beginning of April for rural areas, while there is a another increase at the end of April in just suburban cities. 

![analysis/Fig8](analysis/Fig8.png)

## Summary
Given that the toal fare increases at the end of February for all cities, and in April for suburban cities, PyBer should investigate what causes these spikes. While total fare is increasing, it might be worth incentivizing more drivers to be available during this time, or incentivizing more passengers to use PyBer during periods of higher demand. 

As mentioned earlier in this analysis, the availability of other forms of public transportation most likely has an inverse relationship with the average fare per ride/driver. And since most of the revenue comes from urban areas, it could be beneficial to determine which large cities do not have metro systems (i.e. Miami, FL). Since ride-sharing services would be important in these areas, PyBer should increase their influence in these areas by hiring more drivers and attracting more customers.

Finally, since the average fare per driver is higher in rural areas, and there are significantly fewer drivers, it could be advisable for the company to increase their drivers in rural areas in order to maximize profits. 
