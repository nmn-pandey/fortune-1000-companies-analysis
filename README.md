# Analysis of Fortune 1000 Companies

## Introduction
Fortune, an American Business Magazine, publishes the Fortune 500 every year, which ranks the top 500 companies in terms of revenue. Instead of only the top 500, this dataset contains the whole Fortune 1000. This data can be used to answer questions about the gender distribution of CEOs, the financial performance of companies over time, and the industries that generate the most profit and revenue.

This project involves a detailed analysis of Fortune 1000 companies, focusing on the impact of CEO gender on company revenue and profits, as well as the distribution of male and female CEOs across various sectors. Utilizing a dataset that extends beyond the traditional Fortune 500, this analysis aims to uncover insights into gender diversity and financial performance among top-ranking companies.

# Fortune 1000 Dashboard

This repository contains a Tableau dashboard to answer specific research questions mentioned in the next section, offering a comparative analysis across CEO genders, sectors, and years within the Fortune 1000 companies.

<img width="900" alt="image" src="https://github.com/nmn-pandey/fortune-1000-companies-analysis/assets/20767834/931d5a2d-0099-4604-a912-7a4e5e4dbfdd">


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

![Donut Chart]<img width="700" alt="image" src="https://github.com/nmn-pandey/fortune-1000-companies-analysis/assets/20767834/0f98473b-8e89-4dbe-bd1f-89c36c21ac6f">
*Donut chart showing percentage of female CEOs by sector*

![Map]<img width="700" alt="image" src="https://github.com/nmn-pandey/fortune-1000-companies-analysis/assets/20767834/4ecdc3e3-f693-4fe4-bd1c-4f434bf82266">
*Map showing locations of companies colored by CEO gender*

![Boxplot]<img width="700" alt="image" src="https://github.com/nmn-pandey/fortune-1000-companies-analysis/assets/20767834/5999a138-3fe4-4f08-b15c-e9c6328194fc">
*Boxplots comparing average revenue by CEO gender* 

![Barchart]<img width="700" alt="image" src="https://github.com/nmn-pandey/fortune-1000-companies-analysis/assets/20767834/30745abe-f5c2-4711-b9df-cde851f1a171">
*Bar chart showing revenue trends over time by sector*

![Wordcloud]<img width="700" alt="image" src="https://github.com/nmn-pandey/fortune-1000-companies-analysis/assets/20767834/91a5b387-f05a-40d1-bcf0-e43220e02506">
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
