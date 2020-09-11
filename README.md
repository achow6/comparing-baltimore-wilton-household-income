# Comparing Household Income in Baltimore, MD and Wilton, CT

This project serves to compare two cities, Baltimore, MD, and my hometown, Wilton, CT. Although these areas are only about a 5 hour drive apart, having lived in both places for some time, I noticed that they are incredibly different. Household income is explored in this project as a possible difference between these two areas.

# Business Question
Which city encourages more social mobility?

# Data Sources
**Opportunity Insights**: this is a research group that identifies and attempts to dissolve barriers to social mobility to help those living in poverty. The team developed Opportunity Atlas (https://www.opportunityatlas.org/), which uses childhood to mid-30's data from 20 million people to rate areas based on their social mobility.
This publically accessible data was used in this data.
1. Data showing household income in Baltimore, MD and Wilton, CT (data Baltimore - general & data Wilton - general)
2. Data showing household income given parents' income is in the top 25% (data Baltimore - high & data Wilton - high)
3. Data showing household income given parents' income is in the bottom 25% (data Baltimore - low & data Wilton - low)

# Data Analysis
Once the original data was downloaded, the location column (containing neighborhood, city, and state) was split into three separate columns for each (neighborhood, city, state). Cities outside of the scope were then filtered out. The VLOOKUP tool was then used to combine the datasets based on their "tract" number. The datasets from both cities were also combined to create a more cohesive analysis. This was simple because the two cities' datasets shared the same column names and units of measurement. The data were analyzed through pivot charts and tables for numeric and visual results.

# Data Answer
*insert visual 1*
Here we can see a large difference between overall average income in both cities. There is a $48,440 difference in average household income.

*insert visual 2*
Here we see that the large difference between average income persists even when looking at children that came from high income and low income families. It should be noted however, in both cities, average household income is lower for those that came from low income families compared to high income ones. It is also interesting to see that average income of a child from a high income Baltimore family exceeds the overall household income average in Baltimore.

These numerical findings show that Wilton, CT encourages more social mobility than Baltimore, MD. To further explore the difference in income, data on type/length of employment and education level might be helpful.
