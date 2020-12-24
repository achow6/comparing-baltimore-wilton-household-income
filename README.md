# Comparing Household Income in Baltimore, MD and Wilton, CT

This project serves to compare household income in two cities, Baltimore, MD, and my hometown, Wilton, CT. Although these areas are only about a 5 hour drive apart, having lived in both places for some time, I noticed that they are incredibly different. Household income is explored as a differentiator between these two cities.

According to [research](https://pubmed.ncbi.nlm.nih.gov/20201871/), household income and socioeconomic status (SES) affect the economic environment, which determines the robustness of the area's business and economy. Therefore, more affluent areas have more robust businesses and economy. It would be helpful to understand what contributes to a socioeconomic status of an area, so parents socioeconomic status is explored as a possible contributor to child's household income. 

# Business Question
Which city supports a more robust business economy? How might parents' SES affect this?

# Data Question
How can parents' SES affect child's household income? 
How do household incomes in Baltimore, MD and Wilton, CT compare?

# Data Sources
**Opportunity Insights**: this is a research group that identifies and attempts to dissolve barriers to social mobility to help those living in poverty. The team developed [Opportunity Atlas](https://www.opportunityatlas.org), which uses childhood to mid-30's data from 20 million people to rate areas based on their social mobility.
This publically accessible data was used in this analysis.
1. Data showing household income in Baltimore, MD and Wilton, CT (data Baltimore - general & data Wilton - general)
2. Data showing household income given parents' income is in the top 25% (data Baltimore - high & data Wilton - high)
3. Data showing household income given parents' income is in the bottom 25% (data Baltimore - low & data Wilton - low)

# Data Analysis
Once the original data was downloaded, the location column (containing neighborhood, city, and state) was split into three separate columns for each (neighborhood, city, state). Cities outside of the scope were then filtered out. The VLOOKUP tool was then used to combine the datasets based on their "tract" number. The datasets from both cities were also combined to create a more cohesive analysis (both datasets shared the same column names and units of measurement). The data were analyzed through pivot charts and tables for numeric and visual results.

# Data Answer
![alt text](https://github.com/achow6/comparing-baltimore-wilton-household-income/blob/master/Picture1.png)
Here we can see a large difference between overall average income in both cities. There is a $48,440 difference in average household income.

![alt text](https://github.com/achow6/comparing-baltimore-wilton-household-income/blob/master/Picture2.png)
Here we see that the large difference between average income persists even when looking at children that came from high income and low income families. It should be noted however, in both cities, average household income is lower for those that came from low income families compared to high income ones. It is also interesting to see that average income of a child from a high income Baltimore family exceeds the overall household income average in Baltimore.

# Business Answer
This data suggests that Wilton, CT generally has higher household income compared to Baltimore, MD in all parent SES brackets. The data also suggest that parents' SES is positively related to child's household income. 

The aforementioned research found that socioeconomic status and household income influence the robustness of a city's businesseses and economy. Therefore, it can be inferenced from this data that Wilton could have a more robust business structure and economy than Baltimore because Wilton shows a higher household income across all categories than Baltimore. However, further research is needed to confirm this association.

To further explore the difference in income, data on children's type/length of employment and education level might be helpful. It would also be helpful to include data on the city's economies and businesses (ex. turnover rate, revenue).
