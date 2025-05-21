# Forecasting Protest Onset in the Western Balkans

This project develops an early warning system to forecast protest onset across six Western Balkan countries using Google Trends data and macroeconomic indicators. The work was completed as part of a graduate-level policy analytics project at the Barcelona School of Economics.

##  Objective
To identify whether search behavior related to key political terms (e.g. "protest," "Putin," "sanctions") can help predict the likelihood of protest events in advance, allowing for improved policy communication and early response.

##  Methods & Tools
- **Data**: Google Trends (normalized monthly search volume), panel data on protest events, macro indicators
- **Tools**: R (tidyverse, caret, plm, ggplot2)
- **Modeling**: Logistic regression with rolling panel cross-validation
- **Metrics**: AUC, precision-recall curves

##  Key Outcomes
- Significant correlation found between spikes in Google Trends data and protest onset across multiple countries
- Rolling panel models showed predictive power beyond macro baseline models
- Visualizations used to align spikes in search interest with protest timing

##  Files
- `Forecasting_&_Policy_Analytics.ipynb`: Full notebook with code, modeling, and discussion
