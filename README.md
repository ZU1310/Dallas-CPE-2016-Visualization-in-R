# Dallas-CPE-2016-Visualization-in-R
Data Loading and Preparation

First we load the dataset into R using the read.csv() function. We make sure to convert date columns into the Date format and time columns into the hh;mm;ss format. To ensure data quality, any missing or invalid rows are removed. Additionally we create columns to represent the month and month number, for analysis.

Libraries Used

To facilitate data manipulation, visualization, mapping and correlation analysis in R we utilize libraries such as tidyverse, ggplot2, dplyr, lubridate, corrplot, leaflet among others.

Exploratory Data Analysis

We begin by generating summary statistics that provide insights on counts based on variables like race and gender. Visualizations play a role in understanding the data distribution. For example;
 Bar plots are created to visualize incidents by month and race.
 A histogram displays the distribution of officer years of experience.
 A bar plot presents race against their description.
 Tile plots allow us to observe patterns between officer/subject race across months.
 Bar plots provide a comparison of force type by race and gender.
 Density plots illustrate district distributions based on descriptions.
 Boxplots reveal relationships between injuries, arrests, locations with respect to race.
 A scatterplot helps analyze the relationship between arrests and race.
 A correlation matrix is generated to explore connections among columns.
 Pie charts offer insights into divisions categorized by gender and race.

Mapping

Using Leaflet librarys capabilities in R programming language allows us to create a map displaying incident locations effectively.

Time Series Analysis

For analyzing incidents over time trends at intervals; a line chart is created to visualize these patterns accurately.

Conclusions

We summarize relationships observed through visualizations along with findings, from our analysis. It's essential to acknowledge any limitations encountered during this phase while emphasizing that further analysis is needed to understand the causes behind certain trends or patterns.
