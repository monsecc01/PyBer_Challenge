# PyBer Analysis Challenge

## Resources
Data Source: [city_data.csv](https://github.com/monsecc01/PyBer_Challenge/blob/main/city_data.csv) and [ride_data.csv](https://github.com/monsecc01/PyBer_Challenge/blob/main/ride_data.csv)

Code: [PyBer_Challenge](https://github.com/monsecc01/PyBer_Challenge/blob/d8d01a329dbf5fda6bcb81774c3e412f6b3fe4d9/PyBer_Challenge.ipynb)

Software: Python 3.9, Jupyter Notebook

## Overview of the analysis

The purpose of the PyBer analysis is to evaluate ride-sharing data across three different city types: urban, suburban, and rural. We will provide a summary of the ride-sharing data by city types by creating a summary DataFrame. A multiple-line graph will also be presented to visualize the total weekly fares between January 01, 2019 and April 29, 2019 for each city type. The analysis will help identify discrepancies by city type and will be used to provide business recommendations to the PyBer CEO. 

## Results

The PyBer summary DataFrame shows that rural areas have the lowest total rides, 125 total rides. It is observed that the total number of drivers is also significantly lower than urbanized areas; 78 total drivers in rural areas compared to 2,405 total drivers in urban cities. The lower ride and driver totals may be due to the lower populations in rural areas, which may limit the access of PyBer services to both drivers and riders. We can also see from the summary DataFrame that rural areas have higher fares per ride and per driver. While the total fares show that rural areas do not bring the most money, drivers seem to be making larger a profit compared to urban drivers. 

 ![pyBer_summary](https://user-images.githubusercontent.com/81447450/116019167-3b048300-a609-11eb-817e-e8461ef99bf5.png)

The Total Fare by City Type graph shows us that the three city types follow the same trends throughout the year. All three have a high total fare amount towards the end of February and maintain constant highs and lows throughout the spring months. One difference to note is towards the end of April when fare totals dip for rural and urban areas, but not for suburban cities. It is observed that fare totals for suburban cities increases significantly around that time. 

![PyBer_fare_summary](https://user-images.githubusercontent.com/81447450/116019182-42c42780-a609-11eb-98e7-ac41bb3651dd.png)

# Summary

After analyzing the data for urban, suburban and rural ride-sharing data, we are providing the following recommendations:

1. Although rural drivers seem to be profiting the most due to low supply, fares are drastically higher for riders compared to urban and suburban cities. This may also be a turn-off for riders. To offset the high average fare and increase access to riders, the company may want to allocate more drivers in urban areas.

2. To further maximize profits in rural areas, in addition to allocating more drivers, the company could invest in advertising for PyBer to promote ride-sharing services.

3. Towards the end of April, suburban cities show a hike in fare totals whereas rural and urban areas show a decrease in fare totals. The company may want to investigate the fare increase as it may be an opportunity to make a larger profit during those dates. 
