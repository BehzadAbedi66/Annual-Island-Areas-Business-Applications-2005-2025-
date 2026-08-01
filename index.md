# Predicting Future Business Applications Across U.S. Island Areas

<img width="1029" height="720" alt="Header_Picture" src="https://github.com/user-attachments/assets/b3de3402-a4ca-4025-a3c7-e1e1bbd78cf4" />


## Why This Matters

Business applications are often viewed as an early indicator of economic activity and entrepreneurial growth. By examining historical business application data across U.S. island areas, we can better understand how business activity has evolved over time and explore whether past trends can help estimate future application volumes.

This analysis uses data from the U.S. Census Bureau's Business Formation Statistics program covering the years 2005 to 2025.

## Questions of Interest
1. How have business application volumes changed over time across different island areas?
2. What does the distribution of business application volumes look like?
3. Can historical business application data help predict future application volumes?


### Question 1: Business Application Trends Over Time

<img width="1376" height="696" alt="Q1" src="https://github.com/user-attachments/assets/1958fe82-f14d-451a-b070-6a825d6f5c18" />

Findings: The analysis shows that business application activity has changed considerably over time and differs across island areas. Some regions consistently report higher application volumes than others, suggesting varying levels of entrepreneurial activity and economic development.
The results indicate that both geographic location and historical trends play an important role in understanding business formation patterns.



### Question 2: Distribution of Business Applications

<img width="919" height="540" alt="Q2" src="https://github.com/user-attachments/assets/525741d8-0aad-4271-bca0-edc1591cd449" />

Findings: Most observations are concentrated at the lower end of the scale, while a smaller number of observations have substantially higher business application volumes. This creates a right-skewed distribution.
In practical terms, this means that extremely high numbers of business applications are relatively uncommon, while lower and moderate application volumes occur much more frequently.



### Question 3: Predicting Future Business Applications

<img width="632" height="70" alt="Q3" src="https://github.com/user-attachments/assets/d6eb36b0-305a-479a-b388-4badccd4c618" />

<img width="480" height="55" alt="Q3_1" src="https://github.com/user-attachments/assets/8889d6e4-5bcb-4815-a001-7107cca9abfa" />

Findings: Historical business application data proved useful for estimating future application volumes. By analyzing trends across years and locations, the machine learning model was able to identify patterns and generate predictions for future periods.
The model accepts user-defined inputs, such as a state abbreviation and a future year, and produces an estimated number of business applications for that scenario. This allows users to explore potential future outcomes for different locations based on historical trends.
The evaluation results indicate a high level of predictive accuracy, suggesting that the model is able to explain a substantial portion of the variation in business application volumes. While no prediction can be guaranteed to be perfectly accurate, the results demonstrate that meaningful forecasts can be derived from historical observations and used to support planning and decision-making activities.


## Key Takeaways
Business application activity varies significantly across island areas.
Most business application volumes fall within a relatively low to moderate range.
Historical data contains useful information for forecasting future business activity.
Predictive analytics can help provide insights into future business formation trends.

## Data Source

U.S. Census Bureau - Business Formation Statistics (BFS)
