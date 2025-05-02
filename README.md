# Project background

I am very passionate about the environment and what we as humans can do to protect it. Research has shown that following a vegan diet causes less harm to the planet than a traditional meat and dairy-based diet, due to various factors such as less land space required for raising animals, less water required for processing meat and dairy, fewer CO2 emissions, etc. Studies have also shown an increase in the number of people globally following a vegan diet, which would lead to less harm to the environment should this trend continue. An increase in 'veganism' would suggest a decrease in the meat supply required given that fewer people are eating meat. But can this be predicted? This project will explore the hypothesis: 

### "Global meat supply has decreased over time with the increased prevalence of those following vegan diets, and future meat supply levels can be predicted to understand the potential impacts on the environment"

Being able to predict the meat supply required would lead to better comprehension of the harmful effects caused by raising and eating meat, and therefore better understanding of what state of the environment would be in after a certain amount of time.

## The Data

The data is collected by the Food and Agricutlure Organization of the United Nations - https://www.fao.org/faostat/en/#data/FBS , and processed by Our World in Data - https://ourworldindata.org/meat-production . Data of the meat supply by country from 1961 to 2022 is downloaded as an Excel file ready to be read into Python, and the value for the 'World' is selected as the data point for this analysis - individual countries are discarded.

The dataset consists of the meat supply globally in kgs per person per capita, plus the year in which that value is seen. The aim of this project is to build a time-series predictive model within Python with the intention of being able to predict future values of meat supply. 

## Exploratory Data Analysis

