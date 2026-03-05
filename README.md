**Video Game Sales Analysis Project**


**1. Business Problem Analyzed**
The objective of this analysis is to evaluate the distribution of global sales and average critic scores for Sports and Shooter video games to understand market performance and frequency distributions.

**2. Key Insights Found**

**Data Quality Matters:** By explicitly filtering out games with missing or zero critic scores and rounding the global sales data, the dataset provided a much more accurate representation of true market performance without the skew of unrated titles.

**Sales Distribution:** The visualization revealed a strong right-skew in global sales. The vast majority of both Sports and Shooter games sell in the lower brackets (0 to 1 million copies), making mega-hits exceptionally rare.

**Critic Scores**: With unrated games removed, the sorted top-tier games show that Sports games maintain a marginally higher average critic score compared to Shooter games, indicating slightly more consistent favorable critical reception.

**3. Directory Structure**

**data/:** Contains documentation on the raw data source (Video_Games_Sales.csv) and retrieval instructions.

**munge/**: Documents the SQL data transformation processes, specifically mutating (rounding) sales data, filtering for valid critic scores (>0), and arranging the data in descending order.

**src/:** Contains documentation of the Hive aggregations used to group and count the cleaned data.

**reports/:** Contains the final Excel dashboard (.xlsx) featuring the clustered histogram and average score pie chart.
