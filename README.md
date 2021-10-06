# PyBer_Analysis

### Overview and Purpose of the Analysis: 

This analysis was conducted on data provided to the analysts from PyBer (a fictional ride-sharing company) in order to examine business trends in urban, suburban, and rural cities between 2019-01-01 and 2019-04-29, and additionally, to identify and address any disparities in ride-sharing data among the aforementioned city types. In order to carry out this analysis, a summary DataFrame was created in Jupyter Notebook using the pandas library. Said DataFrame was then indexed, and resampled in order to visualize the necessary data using matplotlib and pyplot.

### Results

When examining the results of the analysis in terms of both the Summary DataFrame (shown below) and the multi-line chart of weekly ride-sharing revenue in the three types of cities (shown further below), several trends and discrepancies become evident.

![PyBer_Summary_df](https://user-images.githubusercontent.com/85244439/136127066-6a35776d-fd92-430b-a8a7-47dd82cde3ab.PNG)

Looking at the PyBer Summary DataFrame screenshot above, perhaps the most clear observation would be the differences in ride revenue. As one might expect, urban cities yield the most revenue due to their greater population size, and within that population, the subset of people who do not own cars. Inherently, there is a higher demand in such cities. This is reflected in the drivers-to-rides ratio, as urban cities have more drivers available than rides completed. As such, the greater supply of drivers, likely in combination with the assumption that rides completed in urban areas usually cover shorter distances, yields a lower average fare per ride than rides completed in suburban and rural areas. However, this is not the case in suburban or rural areas, which have a driver-to-ride ratio below 1:1, and subsequently, higher average fares per ride and per driver relative to urban areas.

![PyBer_fare_summary](https://user-images.githubusercontent.com/85244439/136132901-a43d05a8-0107-479f-9953-9bfea18a052a.png)

The indexed and resampled DataFrame, visualized in the above line chart, presents the data as a time-series where the analyst and client may examine trends that occur in each city (or all three) between the months of January and April. Upon examination of this chart, it is evident that revenue in all three city types appears to spike and quickly drop off during the latter half of February, before either entering a period of volatility, or- in the case of suburban and rural areas- a period of stagnation in March. This seems to run contrarily to the assumption that ride-sharing services would be in higher demand following the beginning of March, as weather improves and propensity for travel or going out increases. 

### Summary:

Based on the observations above, the recommendations for improvement of Pyber's business operations and revenue flows are as follows:
1.) To increase revenue in suburban and rural areas, it might be prudent to offer sign-on incentives for new drivers in these areas, and advertise for said incentives as well. An influx of drivers would decrease wait times for rides and lower ride fares- both of which would be attractive to potential customers. The firm should seek to reach a 1:1 driver-to-ride ratio in each of the city types.
2.) As weather improves in the spring, and people look to socialize outside their homes or travel, a customer promotion (including discounted rides, increased rewards points per ride, etc.) might be prudent to implement in all three areas in order to maximize revenue and avoid any drop-offs or volatility going into March. Predictable revenue and profit margins allow firms to more accurately forecast their growth, which, in turn, allows them to form more robust plans for expansion of operations.
3.) An analysis spanning a longer observational period would be recommended in order to yield more robust trend analysis and recommendations. The reuslts and recommendations above apply only to the four-month period that has been examined by the resampled DataFrame, which is far too narrow a window of observation to generate any impactful recommendations for long-term revenue growth. Examination of the data spanning the entirety of 2019 would yield far more impactful results.
