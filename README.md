# Power BI Project: Top 250 Movies Analysis

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools-used)
- [Data Cleaning/Preparation](#data-cleaningpreparation)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Results/Findings](#resultsfindings)
- [Recommendations](#recommendations)
- [Challenges Faced](#challenges-faced)
- [Future Work](#future-work)
- [Conclusion](#conclusion)
  
## Project Overview
 This project provides a comprehensive analysis of IMDb’s Top 250 Movies, utilizing Power BI for data extraction, transformation, and visualization. Through a series of advanced Power Query transformations, the dashboard highlights key insights on average ratings, decade-specific trends, and standout movies from different eras.
 
## Data Sources
- Movies Data: The primary dataset used is IMDb's "Top 250 Movies" list, extracted directly from IMDb’s [website](https://www.imdb.com/chart/top). 

## Tools Used
- Power BI: Used for data extraction, transformation, and interactive visualization.

## Data Cleaning/Preparation
### In the initial data preparation phase, we completed the following steps using Power Query in Power BI:

1. Data Loading and Inspection: Imported IMDb's HTML data table.
2. Promoted Headers: Set column headers for ease of use.
3. Type Changes and Column Splits: Assigned appropriate data types and split columns as needed.
4. Data Cleaning: Removed unnecessary columns, replaced values, trimmed text, and added custom columns for analysis.

## Exploratory Data Analysis (EDA)
Key questions explored during EDA included:

- #### What is the average rating of the top 250 movies?
- #### Which decades had the most top-rated movies?
- #### Which movies stand out with the highest ratings?

## Results/Findings
- Total Movies Analyzed: 250
- Average Rating: 8.25
- Top Decades by Movie Count: 2000s (48 movies), 2010s (43 movies), and 1990s (41 movies).
- Notable Movies: Your Name. (2016), Witness for the Prosecution (1957), Whiplash (2014), and WALL-E (2008) stand out for their ratings. 

## Recommendations
Based on the analysis, the following recommendations were made:

- Highlight Top Decades: Emphasize popular decades like the 2000s and 2010s in promotions.
- Target High-Rated Films: Feature highly rated classics and modern masterpieces.
- Set Rating Goals: Continue efforts to increase average ratings to meet target goals (8.50).

## Challenges Faced
- Data Source Limitations: Limited data on some movies, such as revenue or budget information, restricted certain parts of the analysis.
- Data Transformation: There were challenges in transforming HTML data into a usable format for Power BI, including handling duplicates and correcting erroneous values.

## Future Work
- Expand Dataset: Expanding the analysis to include more movies or additional IMDb data, like user and critic reviews, would allow for more comprehensive insights.
- Advanced Visualizations: Incorporating advanced Power BI visualizations, such as a time-series analysis of movie popularity or word clouds of common movie themes, could add depth to the analysis.

## Conclusion
This project provided valuable insights into the film industry, highlighting the importance of specific time periods and the performance of both classic and modern films. The analysis shows variance in movie ratings, suggesting that certain decades and genres may resonate more strongly with audiences and critics.
