# 1896-2024 Summer Olympic Medals
 Olympic  Medals Over the years

<p align="center">
  <img width = "75%" src="https://github.com/user-attachments/assets/8b596eb0-00c7-4afd-bf22-3389d9492671">
</p>

## Overview

This project explores the historical data of Olympic medals from 1896 to 2024 to uncover patterns, trends, and insights related to national and continental performance. By analyzing this extensive dataset, the goal was to understand the factors influencing medal outcomes, such as age, medal types, and host country advantages. The project also seeks to identify trends in medal efficiency and the impact of hosting the Olympics on a country’s performance. The insights gained can offer valuable perspectives on how different nations and continents have evolved in their Olympic success over time.

## Data

The dataset used in this project is comprised of historical records of Olympic Medals from 1986-2024, including information on medal counts, participating countries, athlete details, and hosting countries. 

# *Methods*

### *Data Cleaning & Preprocessing:*
The dataset was cleaned using Pandas, prepared by handling missing values and ensuring consistency in the data, particularly focusing on standardizing country names and codes.

### *Feature Engineering:* 
Used Pandas and NumPy to create additional features and enhance the overall analysis.

- *Medal Efficiency:* A metric to evaluate the efficiency of countries in winning medals relative to their participation.

- *Host Advantage:* A measure to analyze the impact of hosting the Olympics on medal counts.

- *Continent Aggregation:* Creating a columnm that contains which continent each country is from.

- *Medal Trend:* The percentage change in total medals won by each country across different Olympic Games.

- *Most Common Medal:* Most common medal won by each country overall.

### *Visualizations:* 
Employed Seaborn, Matplotlib, and Plotly for various visualizations, including bar charts, pie charts, and line plots, that helped to illustrate key findings:

- Total Medals Awarded Each Year.
- Total Medals won United States.
- Most Common Medal Won By US Yearly.
- US Medal Trend
- Total Medals By Continents
- Total Medals Over Time

## *Visualizations*


### *Total Medals Awarded Each Year*

![Total Medals awarded each year 1896-2024](https://github.com/user-attachments/assets/a759f8d7-ab1e-4939-a2b9-f9bbc75c1157)


- The number of participants have varied throughout the years, due to some events being added or taken away.


### *Total medals won United States*

![Total Medals won Yearly by US](https://github.com/user-attachments/assets/80865257-8b0f-4bbc-8f3a-9750c5c678b6)

- This shows the total number of medals the US has been awarded over the years.


### *Most Common Medal Won By US Yearly*

![Most Common Medal Won By US Yearly](https://github.com/user-attachments/assets/0fca5b91-2be6-4e11-acf8-2c95052e78f4)

- This visualizes the monst common medal type awarded to the US through the years.

### *US Medal Trend*

![Medal Trend For US over the years](https://github.com/user-attachments/assets/f1392093-ea9c-4060-9bf4-175561f74985)

-This shows the increase or decrease in the number of medals won by the US compared to the previous year.

## *Total Medals By Continents*

![download](https://github.com/user-attachments/assets/9d6a9bdd-cab5-400f-b492-06fdac1e5d88)


- This shows us that Europe has dominated in total amount of medals won throughout the years of the Olympics.

## *Total Medals Over Time*

![download](https://github.com/user-attachments/assets/2cdec467-325f-4962-84a9-cac74eb7d1e4)

- This shows that the US has  pretty consistently dominated in total medals over the years.

### *Hypothesis Testing:* 

Several hypotheses were tested to validate assumptions, results for each of these are captured below:

*Medal Efficiency and Continent Performance:* Analyzing whether certain continents consistently outperform others.

<p align="center">
  <img src="https://github.com/user-attachments/assets/c826d929-ede0-4635-b897-dad9e94100ed" alt="Medal Eff HP">
</p>



*Host Advantage Hypothesis:* Testing if hosting the Olympics significantly impacts a country’s total medal count.

<p align="center">
  <img src="https://github.com/user-attachments/assets/8e6635aa-6497-4372-b260-f355795649c2" alt="Medal Eff by Country HP">
</p>

*Effect of Medal Type on Medal Efficiency:* Investigating if the type of medal won influences a country’s efficiency.

<p align="center">
  <img src="https://github.com/user-attachments/assets/c2e29787-2038-4b52-bf8d-e0ffc1330b6e" alt="Medal Eff and Medal Trend HP">
</p>

*Medal efficiency across different countries:* Looking for correlation between Medal efficiency and countries.

<p align="center">
  <img src="https://github.com/user-attachments/assets/137ac0e1-7448-4ead-b4dd-4a7973417e06" alt="Medal Eff by Country HP">
</p>


*Medal efficiency effects on medal trends:* Looking at medal efficiency correlation with medal trends.

<p align="center">
  <img src="https://github.com/user-attachments/assets/e9bcd13c-2827-4dea-8a2b-95905fe80999" alt="Medal Eff and Medal Trend HP">
</p>

*Host advantage effect on most common medal:* Looking for correlation between the host advantage and most common medal won when a country is hosting the Olympics.

<p align="center">
  <img src="https://github.com/user-attachments/assets/ec928518-bdc1-4771-bd2b-ddb8ede10895" alt="Host Advantage on Common Medal HP">
</p>

**Summary:**

This project uncovered key insights into medal trends and efficiency across different countries and continents in the Olympic Games from 1896 to 2024. The United States has consistently led in total medals awarded, holding the record for the most medals won in a single Olympics. However, Europe stands out as the dominant continent in terms of overall medal count. The analysis also revealed significant differences in medal efficiency between continents. Additionally, a clear host advantage was observed, with countries performing better when the Olympics are held in their own nation. This advantage extends to the most common medal won during these events as well.





