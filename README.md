# fortune-1000-companies-analysis
Analysis of Fortune 1000 companies, focusing on CEO gender's impact on performance. Includes Tableau visualizations and detailed insights derived from extensive data exploration and analysis.

# Analysis of Fortune 1000 Companies

## Introduction
Fortune, an American Business Magazine, publishes the Fortune 500 every year, which ranks the top 500 companies in terms of revenue. Instead of only the top 500, this dataset contains the whole Fortune 1000. This data can be used to answer questions about the gender distribution of CEOs, the financial performance of companies over time, and the industries that generate the most profit and revenue.

# Fortune 1000 Dashboard

This repository contains a Tableau dashboard analyzing Fortune 1000 companies data from 2019-2021.

![Dashboard](images/dashboard.png)

*Dashboard providing insights into gender diversity and financial performance of Fortune 1000 companies*

The dashboard answers research questions around:

- Gender distribution of CEOs across sectors
- Correlations between gender, location and financial performance
- Performance trends of sectors from 2019-2021

## Research Questions

1. How does the gender of a company’s CEO and its distribution across sectors, impact its revenue and profits? How does its location correlate with the state’s male-to-female ratio?

2. How has the performance of sectors within the top 1000 companies changed from 2019-2021 in terms of revenue, profits, and employee count?

## Dashboard Contents 

The dashboard contains 5 sheets:

1. Donut chart showing sector-wise proportion of female leadership  
2. Map showing companies' locations colored by CEO gender and sized by performance metric
3. Boxplots comparing performance metrics by CEO gender 
4. Bar charts showing performance trends of sectors over time
5. Word cloud of top companies by performance metric

### Screenshots 

![Donut Chart](images/donut.png)

*Donut chart showing percentage of female CEOs by sector*

![Map](images/map.png)

*Map showing locations of companies colored by CEO gender*

![Boxplot](images/boxplot.png) 

*Boxplots comparing average revenue by CEO gender* 

![Barchart](images/barchart.png)

*Bar chart showing revenue trends over time by sector*

![Wordcloud](images/wordcloud.png)

*Word cloud showing top companies clustered by growth rates*


## Implementation

The dashboard uses parameters, filters, calculated fields, custom visualizations, and actions to allow interactive data exploration. 

Key implementation details:

- Parameter for selecting performance metric
- Calculated field for dynamic performance metric  
- Dual axis donut chart using table calc
- Symbol map with background polygon layer    
- Boxplots with colors encoded by CEO gender
- Bar charts with columns for sector and color encoded years   
- Word cloud with clustering and tooltips

## Dashboard Walkthrough  

The dashboard can be used to:

- Compare CEO gender distribution across sectors over time
- Identify correlations between gender, location and financial performance  
- Analyze performance trends of sectors from 2019-2021
- Identify top companies and growth patterns   

Users can filter by year, sector, CEO gender and select different performance metrics to interactively explore the data. Actions allow highlighting insights across different sheets.

This dashboard provides interactive visualization capabilities to gain insights from the Fortune 1000 dataset.

## Summary of Insights

- There are gender disparities in CEO representation across sectors  
- Some sectors have higher proportions of female CEOs than others
- Technology and healthcare sectors increased female leadership over time
- CEO gender impacts financial performance within some sectors 
- Performance of sectors has been varied from 2019-2021
- Technology and retailing sectors have seen growth recently

## References
- Data Source: Fortune 1000 Companies Dataset
- Visualization Tool: Tableau
