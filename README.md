# India_CPI_Inflation
## Overview																				
In India, the Consumer Price Index (CPI) is used to measure inflation, and it involves a fixed basket of goods and services. This basket is comprehensive and includes a wide array of items that an average Indian consumer uses. These items are not limited to just food and clothing but extend to transportation, medical care, electricity, education, and almost every other category that involves expenditure of money. The CPI is calculated by comparing the general price level in the markets during a particular time period with a base year. The items in the CPI basket are classified across various categories like food and beverages, clothing, housing, fuel and light, and recreation, among others.		

## Dataset
<a href="https://github.com/guntassinghgs/India_CPI_Inflation/blob/main/Raw%20Inflation%20data.csv">Dataset</a>

## Problem Statement																				
																				
You are working with the National Statistical Office which is equipped to release inflation numbers in India. As an analyst, you are provided with CPI data and are equipped find out insights from the data. Your senior wants you to find key trends and deep dive into the data to answer the following questions -   																				

1. Based on the latest month’s data, identify the contribution of different sectors (food, energy, transportation, education, etc.) towards the CPI basket																				
Which sector has the highest weightage towards CPI calculation 																				
 																				
2. A trend of Y-o-Y increase in CPI (rural + urban) inflation starting 2017 for the entire basket of products																				
Create a bar graph depicting the growth rate Y-o-Y and identify the year with highest inflation rate  																				
																				
3. With India's retail inflation reaching a 3-month high of 5.55% in November 2023, largely due to a sharp rise in food prices. Analyze which specific food items have contributed the most to this increase at month-on-month basis for 12 months ending May’2023   																				
Investigate trends in the prices of vegetables, fruits, and pulses, (broader food bucket) and compare month-on-month changes 																				
Identify the absolute changes in prices over 12 months and identify the biggest contributor towards inflation																				
																				
4. Investigate how the onset and progression of the COVID-19 pandemic affected inflation rates in India. Analyze the correlation between key pandemic milestones (e.g., lockdowns, vaccination drives) and changes in the consumer price index, particularly focusing on sectors like healthcare, food, and essential services.																				
					
5. Investigate how major global economic events (like oil price fluctuations, international trade policies during the pandemic) have influenced India's inflation. This can include an analysis of imported goods and their price trends. 																				
																				
For the purpose of this analysis, focus only on the oil price fluctuations for years 2021 to 2023 																				
Identify trends in oil price change with change in inflation – identify sector that strongly correlates with fluctuations in oil price

# Data Analysis Steps

1.	Objective Setting: As outlined above.
2.	Data Acquisition: We have the CPI data file. Load and inspect this data in excel
3.	Data Cleaning: Identify and rectify any inconsistencies or missing data.
4.	Exploratory Data Analysis (EDA): Conduct initial exploration to understand data distribution, correlations, and patterns.
5.	In-Depth Analysis: Answer specific questions from the problem statement.
6.	Visualization: Create visualizations to represent our findings.
7.	Communication: Summarize and present the insights.

## Analysis 
<a href="https://github.com/guntassinghgs/India_CPI_Inflation/blob/main/CPI%20Inflation%20project.xlsx">Project file</a>


# Key Insights: 

1) Sector Contribution Analysis

●	The Food segment has the highest contribution to the CPI basket, accounting for almost half of the CPI.
●	Miscellaneous, which includes sectors like Pan, tobacco, and intoxicants, and household goods and services, also has a significant contribution.
●	Clothing and Footwear and Health and Personal Care are other major contributors.
 Highest Weightage Segment
●	The segment with the highest weightage in the CPI calculation is Food, with a contribution of approximately 46.9% to the CPI basket.

2) Y-o-Y increase 

●	The rural, urban and rural+urban inflation follow same pattern with rural inflation being higher compared to urban 
YoY Inflation Trend 
●	We have taken data for March year every year to calculate general inflation trend as the data is not available for April & May. Also, for 2023 we have data till May, therefore to include 
●	The highest year-on-year growth rate was observed in 2022 at 6.60%.
●	The growth rate seems to have peaked in 2022 and then declined slightly in 2023.

3) Month-on-Month Growth Rate Analysis for Vegetables, Fruits, and Pulses (June 2022 - May 2023)

The month-on-month growth rates for vegetables, fruits, and pulses are as follows for the period from June 2022 to May 2023:

●	Vegetables: Exhibited significant fluctuations. We see periods of both sharp increases and decreases. For instance, there was a notable increase in February 2023 and a decrease in March 2023.
●	Fruits: Also showed fluctuations but less extreme than vegetables. There were periods of growth (e.g., February 2023) and periods of decline (e.g., May 2023).
●	Pulses and Products: Demonstrated relatively smaller fluctuations compared to vegetables and fruits. The changes are mostly within a narrow range.

Key Insights
●	Vegetables show the most volatility in terms of month-on-month growth rates, indicating a significant contribution to fluctuations in food inflation.
●	Fruits also contribute to inflation variability, but with less severity than vegetables.
●	Pulses are relatively more stable, suggesting a smaller contribution to the overall volatility in food inflation.
Looking at individual items within the food bucket gives an idea of volatility but doesn’t show the overall picture. Looking at food bucket as a whole and calculating the MoM change.

4) Impact of COVID-19 Pandemic on Inflation

For this analysis, we'll look at the data from the onset of the pandemic (early 2020) and compare it to the preceding and following years. We'll focus on sectors that were directly impacted by the pandemic, such as healthcare, food, and essential services.
Let's start with the analysis of the COVID-19 pandemic's impact on inflation. We'll compare the relevant sectors' CPI before, during, and after the onset of the pandemic. We calculate yearly change based on march data from n-1 year and comparing it with nth year. Ex: for 2018 to 2019 we see the sum of prices in March 2019 and look at the delta from March 2018. This is because Covid was introduced in March 2020 
 
 Key Insights

●	Healthcare (Health): There is a noticeable increase in the CPI for healthcare each year, with a significant jump from 2019 to 2021. This suggests a substantial impact of the pandemic on healthcare costs.
●	Food and Beverages: The CPI for food and beverages also shows a steady increase over these years, reflecting the heightened importance and possibly disrupted supply chains of food items during the pandemic.
●	Household Goods and Services: This sector also experienced a consistent rise in the CPI, indicating increased costs for essential household items during the pandemic period.
Global Economic Events Impact
We'll examine the correlation between oil price changes and inflation rates. This analysis will involve looking at how fluctuations in oil prices from 2021 to 2023 influenced India's inflation, focusing on sectors like transport and energy.(Sector Selection) 

5) Steps for Analyzing the Impact of Oil Price Fluctuations on Inflation:

1.	Identify Relevant Sectors: Focus on all sectors at the beginning to of any area (maybe start by looking at correlation of urban+rural fluctuations
2.	Time Period Focus: Concentrate on the period from 2021 to 2023, aligning with significant global economic events.
3.	Correlation Analysis: Examine the correlation between the changes in these sectors' CPI and the fluctuations in oil prices. Oil Price data can be downloaded from here : https://ppac.gov.in/prices/international-prices-of-crude-oil
4.	Identify Sectors with highest correlation

Key Observations
●	Transport and Communication: There is a steady increase in the CPI for this sector over the years, which correlate with rising oil prices (84%), as transport costs are directly affected by fuel prices.
●	Fuel and Light: This sector shows a more pronounced increase in the CPI, especially from 2021 to 2022, and then again into 2023. This trend is indicative of the impact of fluctuating oil prices on energy costs.
●	Other food sub-buckets: Meat & Fish, Oil & fats show a sharp correlation with oil prices but the overall food bucket correlation is 65%.  



