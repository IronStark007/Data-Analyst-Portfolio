# Performing Analysis of Meteorological Data
## Introduction
So, We have started the project on Weather dataset. The dataset has hourly temperature recorded for last 10 years starting from 2006-04-01 00:00:00.000 +0200 to 2016-09-09 23:00:00.000 +0200. It corresponds to Finland, a country in the Northern Europe. [Dataset](https://www.kaggle.com/muthuj7/weather-dataset)

Our goal in this Project is to transform the raw data into information and then convert it into knowledge.

In this Project, we would be responsible for perform data cleaning, perform analysis for testing the (given) Hypothesis.

The Null Hypothesis H0 is _"__Has the Apparent temperature and humidity compared monthly across 10 years of the data indicate an increase due to Global warming__"_.

The H0 means we need to find whether the average Apparent temperature for the month of a month say April starting from 2006 to 2016 and the average humidity for the same period have increased or not. This monthly analysis has to be done for all 12 months over the 10 year period. So we are basically resampling your data from hourly to monthly, then comparing the same month over the 10 year period. Finally, Support our analysis by appropriate visualizations using matplotlib and seaborn library.

You can check the [analysis here](https://github.com/IronStark007/Data-Analyst-Portfolio/blob/master/Performing%20Analysis%20of%20Meteorological%20Data/Analysis.ipynb)

## Conclusion

After transforming the data, I have analysed and concluede the following results -  
- From the all insights, it is clear that the __apparent temperature increased over 10 years__ i.e. for 2006-2016 for the Finland due to the Global Warming.
- But __the humidity is remains constant over 10 years__.
- So the __null hypothesis has to be rejected__.
