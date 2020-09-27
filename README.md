# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of this project was to provide two different analyses for Louise since her play, Fever, came close to the fundraising goals in a short amount of time. The first analysis helps to visualize campaign outcomes ("successful," "failed," and "canceled") based on launch date, and the second helps visualize successful, failed, and canceled plays based on the funding goal amount. The [Kickstarter file](Kickstarter_Challenge.zip) has the original data set and corresponding charts for the analyses. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
To be able to analyze the outcomes based on launch date, it was first necesary to extract the year as a data point from "Date Created-Conversion." A pivot table was the best tool for this analysis, and then appropriate filtering was added to look specifically at "successful," "failed," and "canceled" in descending order so "successful" was first. There is also a filter for the pivot table based on "Parent Category" and "Years."

The [Theater Outcomes versus launch date line chart](resources/Theater_Outcomes_vs_Launch.png) was created to provide a visual representation of the three types of outcomes based on the launch date by month. 

### Analysis of Outcomes Based on Goals
The second analysis is to look at the percentage of successful, failed, and canceled plays based on the funding goal amount. This analysis required a new spreadsheet with a 12 ranges of goal levels. The number of successful, failed, and canceled plays were counted and summed allowing for percentages of each outcome to also be run. 

A [line chart](resources/Outcomes_vs_Goals.png) was created to provide a visualization of the results.

### Challenges and Difficulties Encountered
There were not any challenges that were encountered with either of the analyses. There are possible challenges or difficulties that could arise with working with the original Kickstarter file. Before performing a new analysis, it was critical to see what filters had been applied to the main spreadsheet. The best way to mitigate that situation is to clear all filters before beginning a new analysis or create a new chart or table such as Pivot Table. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
The [Theater Outcomes versus Launch line chart](resources/Theater_Outcomes_vs_Launch.png) provides a visualization of the relationship between the various outcomes and each specific launch month. The best and most ideal month during the year to have a successful theater is May, and the least ideal would be December. In general, theaters are more successful during the summer, and the number of successful theaters decreases and the outcome of failing increases during the fall months. The number of canceled theaters remained constant and did not have any spikes from month to month. 

- What can you conclude about the Outcomes based on Goals?
When looking at the [Outcomes based on Goals](resources/Outcomes_vs_Goals.png), plays with mid-range goals (from 24,999 to 34,999) do not do well. There is a lower percentage of success and higher percentage of failures in this range. Also, it is critical to note that plays with goals higher than 45000, have a little to no success with only slight changes in success rates as the goal moves closer to 50000. 

- What are some limitations of this dataset?
The Kickstarter dataset does not have current data. Per the "Years" column, the most recent data is from 2017. More current data could have an impact on the two analyses that were run or could yield very different results that would a great benefit to Louise. 

With the data being pulled from a variety of different counties and with all of the categories and subcategories, it could be possible that some of the data may not be accurate or consistent. Data validation of the variety of data elements would be useful. 

- What are some other possible tables and/or graphs that we could create?
There are several new tables and/or graphs that can be created. It would be valuable to look at the outcomes based on the number of backers or by amount pledged. It would be interesting to look specifically at play and goals by year and then by country to see if plays have done better more recently than in the past in the US. 

