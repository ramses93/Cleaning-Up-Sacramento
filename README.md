# Cleaning-Up-Sacramento

We found some dirty data on Sacramento home sales from 2008, and examined how the market changed over the course of a decade. We used Python, SQL, Pandas, and SQLalchemy to complete the ETL workload for this analysis.

## Extract
Our data came neatly packed in .csv files. We were able to leverage the power of Pandas to quickly and easily import these files into python

![2008 Data Sample](https://github.com/ramses93/Cleaning-Up-Sacramento/blob/main/Images/DataSample.PNG)

## Transform
We wanted to see the changes in home values from 2008 - 2018, we used the existing data to find the median price per zip code and compared it to the 2018 data.

![Transform Code Sample](https://github.com/ramses93/Cleaning-Up-Sacramento/blob/main/Images/transform.PNG)

## Load
We used the python SQLalchemy library to load our final table into pgAdmin4. Pandas was again leveraged to automatically generate the SQL table schema.

![Data Export](https://github.com/ramses93/Cleaning-Up-Sacramento/blob/main/Images/Loadtopg.PNG)

## Analysis

In November 2018, the number of homes sold increased by more than 140%, compared to May 2008. The median price paid for a home increased by 55%. The Sacramento real estate market has clearly recoverd from the 2008 housing bubble. Anyone who was able to buy a home during that period will have seen tremendous gains in property value.