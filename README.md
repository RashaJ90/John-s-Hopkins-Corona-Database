# John-s-Hopkins-Corona-Database
1. Data Preparation and Manipulation
  - load the Corona Confirmed Cases Narrow, the Corona Confirmed Deaths Narrow, and the Corona Confirmed Recovered Narrow datasets directly from the John’s Hopkins website.
  - Create new data-frames named cases.agg, deaths.agg, and recovered.agg which aggregate the sum of Corona cases, deaths, and recovered respectively over the different countries’ provinces. To do this, aggregate Value using only the country and date features, ignoring all other features .To achieve the aggregation use the aggregate function. In addition, order the data-frame first by Country and then by Date (increasing order). The columns of each of the two resulting data-frames should be Country.Region, Date, Value.
  - Using the last day of March as a reference, create a single stacked bar-plot that visualizes the top 10 countries in terms of their Corona cases, and their respected Corona deaths and recovered cases stacked on top of the current sick people in three different colors (each stack should add up to total cases). Make sure that the first stack shows the number of confirmed Corona sick people (sick = cases - deaths - recovered). Each stacked bar should represent a country. Use the barplot base R function to create this plot.
2. Analysis of Daily New Corona Cases and Deaths
  - The two datasets (Corona Cases and Deaths) register the value of cases and deaths, respectively, as a cumulative sum for each day.Add a new column named Diff to both the cases.agg and the deaths.agg data-frames. This new column should register the daily Value difference for each country. In other words, the Diff column shows how many new cases/deaths each country incurs every day.
  - Find the top 10 instances of country and date combinations with the greatest absolute number of new daily Corona cases and deaths (separately).
  - In one figure, plot Italy’s new daily Corona cases AND deaths as a function of Date.
  - plot ,on the logarithm scale, Italy’s new daily Corona cases AND deaths as a function of Date.

