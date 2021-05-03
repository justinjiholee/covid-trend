# COVID-19 Vaccinations Trend

## Background
The Covid-19 has impacted every aspect of people’s livelihood around the world. This pandemic has led to new cases and deaths every day for over an year. While this is a global pandemic, the number of cases and deaths differ for every country. In our previous project, we have decided to measure total cases, new cases, and total deaths in select countries to find a trend for the pandemic as well as to find an association with the government policies using Stringency Index.

This time, as many people around the world are getting vaccinated, we wanted to look at trends of people getting vaccinated for different countries. From the stakeholder’s point of view, we wanted to think about how the vaccinations should be distributed based on the trends. As Johns Hopkins provides vaccinations, we have decided to look at vaccination trends for five countries with the most international students at Hopkins and analyze how to distribute the vaccines. 
 
## Business Question
  _How should Hopkins think about getting students vaccinated?_
  
## Data Analysis
Extracting the data from [Our World in Data](https://ourworldindata.org/covid-vaccinations), we were able to analyze the current trends of vaccinations. Using groupby tool on python, we were able to look at the number of total cases and total vaccinations for the selected five countires. 

![alt text](https://github.com/justinjiholee/covid-trend/blob/main/Python%20Data.png)

From this table, it is shown that China and India had the most amount of vaccinations, but they also have a significantly high population, so we decided to look at total vaccinations per hundred in order to compare the percent of people getting vaccinated from their countries. 

## Data Visualization

In order to compare the percent of people getting vaccinated for different countries, we have first decided to make a bar graph using plotly as it provides effective comparison.

![alt text](https://github.com/justinjiholee/covid-trend/blob/main/Vaccinations%20per%20Population.png)

From this graph, we learned that Canada has the highest proportion of people who got vaccinated, followed by Turkey, China, India, and South Korea. In addition to the bar chart of the percentage of people who got vaccinated, we have also created a line graph of vaccination trends using scatter tool. 

![alt text](https://github.com/justinjiholee/covid-trend/blob/main/Vaccination%20Trend.png)

In this line chart, it shows the number of people getting vaccinated for different countries. This shows that number of people getting vaccinated fluctuates daily, but it is clearly shown that significantly higher number of people in China and India are getting vaccinated compared to other three countries. 

## Conclusion
In this project, we have decided to look at vaccination trends as the vaccines are not accessible to everyone yet and we wanted to think about how the vaccines should be distributed. We believe that students who are from countries with low accessibility to vaccines should be prioritized. We were able to look at the data of vaccinations for China, India, South Korea, Canana, and Turkey, as we have a lot of students from these countries at Johns Hopkins. 

Using various python tools, we were able to look at the number of total vaccinations and the proportion of people who got vaccinated. Using scatter, we were able to look at the general trends of number of people getting vaccinated for the selected countries by making a line chart. While the graph shows China and India has comparatively higher number of people getting vaccinated, we didn't take the number of population into account. Therefore, we created a bar graph of proportion of people who got vaccinated using scatter, which suggested that Canada and Turkey have the highest percentage.

Thus, in order to analyze the accessibility of vaccines, I believe that we have to consider the population of a country when looking at the number of people who got vaccinated. From this analysis, we were able to show that South Korea has the least accessibility to the vaccines. In our future research, it would be interesting to find and analyze methods of increasing accessibility to the vaccines. As a student from South Korea, I hope that more people from my country would get vaccinated in the near future.
