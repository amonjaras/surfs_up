# **Shake n' Surf**
Python, SQLite, SQLAlchemy, Flask

## **INDEX**

[Overview](#overview)

[Resources](#resources)

[Results](#results)

[Summary](#summary)

## **Overview**
We are considering on opening a surf and ice cream shop in Oahu, Hawaii. W. Avy our possible investor, has requested to analyze the weather and temperature in this city; these are two key factors that will determine if the investment is feasible.

[:top: Go To Top](#index)

## **Resources**
Weather data stored in a SQLite database

- [Hawaii Weather](https://github.com/amonjaras/surfs_up/blob/main/hawaii.sqlite)


[:top: Go To Top](#index)

## **Results**
During the first part of the analysis, we were able to reflect the database into a table. With the table we designed a query to retrieve the last 12 months of precipitation. The next graphic shows the precipitation throughout the year, and it can be observed that during the months of August and April have more precipitation.

> *Figure 1: Precipitation by date*

![Precipitation by date](https://github.com/amonjaras/surfs_up/blob/main/Images/precipbydate.png)

To make sure that the information is accurate, we counted the number of weather stations available and determined the most active, giving as a result the station **USC00519281**

Whit this station we were able to obtain the lowest, highest and average temperature as described in the following table.

> *Table 1: Recorded temperatures*

| Description | Temperature Value (°F) |
| --- | ---|
| Lowest Temperature| 54.0 |
| Highgest Temperature | 85.0 |
| Average Temperature | 71.66 |

The following files are available as a result of the first part of the analysis:

- [Climate Analysis: ](https://github.com/amonjaras/surfs_up/blob/main/climate_analysis.ipynb) analysis created with jupyter notebook
- [Flask Application: ](https://github.com/amonjaras/surfs_up/blob/main/app.py) webpage presentation of the results.

W. Avy liked the analysis, but he wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

To complete the analysis we extracted the temperatures information for the months of June and December.

We observed that:

- The average temperature in June is 75°F vs 71°F in December
- The maximum temperature is similar in June (85°F) and December (83°F)
- The minimum temperature has the major difference with 64°F in June and 56°F in December

## **Summary**

Pattern within the temperature is similar in June and December, meaning that investment is suitable for Shake n' Surf shop.

Additional analysis was performed to reach final decision.

Comparing precipitation levels between June and December, we can conclude that December has 22% average rainfall than June with 14%

With this data we can conclude that Shake n' Surf will be an excellent investment.

Below the link to file.

[Surfs Up](https://github.com/amonjaras/surfs_up/blob/main/SurfsUp_Challenge.ipynb)





This work belongs to [^1].
Course [^2].
[^note]:
[^1]: Author: Audrey MONJARAS :mexico: :canada:
[^2]: Data Analytics: Unit 9 Advance Data Storage 🏄‍♂️
