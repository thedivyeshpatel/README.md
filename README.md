**1. Business Problem Analyzed**
The objective of this analysis is to evaluate the distribution of global sales and average critic scores for Sports and Shooter video games to understand market performance and frequency distributions.

**2. Key Insights Found**
Sales Distribution: The histogram visualization revealed an extreme right-skew in global sales. The vast majority of both Sports and Shooter games sell between 0 and 1 million copies. It is highly uncommon for games in these genres to exceed 7 million global sales.

Critic Scores: Sports games have a marginally higher average critic score (71.96) compared to Shooter games (70.17), indicating slightly more favorable critical reception on average.

**3. Directory Structure**
data/: Contains documentation on the raw data source (Video_Games_Sales_as_at_22_Dec_2016.csv) and retrieval instructions.

munge/: Contains documentation of the data cleaning and transformation processes (Module 4).

src/: Contains documentation of the Hive aggregations used to group and count the data (Module 5).

reports/: Contains the final Excel dashboard (.xlsx) featuring a side-by-side histogram and average score pie chart (Module 6).
