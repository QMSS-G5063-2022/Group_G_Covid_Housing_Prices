# NYC COVID-19 and the Housing Market

### Group G Members
* Kum Hyun Lee (khl2139@columbia.edu)
* Mengying Xu (mx2238@columbia.edu)
* Yi Hyun Kim (yk2906@columbia.edu)

Click [here](https://2hyunie.github.io/qmss-dv-group-g/index.html) to view our website.

This project aims to explore how the Covid-19 pandemic has impacted the housing market by focusing on comparing the sales price across NYC. The project will track how the waves of Covid-19 cases affected the price fluctuations by conducting data analysis and illustrating the results.

Research Questions:
* How has Covid-19 affected the housing market via housing prices over time?
* How has COVID-19 affected the NYC housing market? Are there any regional variations in the housing price fluctuations?
* How has the overall perspective on Covid-19 changed over time?

## Part 1: Trends in Covid-19 and Sales Price

Part 1 examines Covid-19 rate and sales prices in all five boroughs in NYC from the 3rd quarter of 2020 to the 1st quarter of 2022. `ggplot2` and `ggplotly` in R is used to create the visualizations.

## Part 2: Geographical Variations

This section maps out the changes in the NYC Covid-19 case rates and housing prices by quarter using `ggplot2`. Specific neighborhoods are consulted from the analysis.

Two hypothesis are tested in this section:

1. The association between Covid-19 and housing prices is negative.
2. The association between Covid-19 and housing prices is positive.

## Part 3: Text Analysis

The final section studies the changes of perspective on Covid-19 over time (2020 Q3 vs. 2021 Q4) by conducting sentiment analysis and creating word clouds using Python.

## Data Sources

* Covid-19: [Case Rate by MODZCTA](https://github.com/nychealth/coronavirus-data/blob/master/trends/caserate-by-modzcta.csv)
* Housing: [NYC Housing Sales Data](https://www1.nyc.gov/site/finance/taxes/property-annualized-sales-update.page)
* Mapping: [Modified Zip Code Tabulation Areas (MODZCTA)](https://data.cityofnewyork.us/Health/Modified-Zip-Code-Tabulation-Areas-MODZCTA-/pri4-ifjk)
* Text Analysis: [Tweets](https://github.com/QMSS-G5063-2022/Group_G_Covid_Housing_Prices/tree/main/Part3)

Our process book that logs our work from start to end can be found [here](https://docs.google.com/document/d/1xeExYWJWVvAeyePif__lbE5q5tvxCoxBYs8WfAIuTLs/edit?usp=sharing)
- Note: this can only be viewed by LionMail
