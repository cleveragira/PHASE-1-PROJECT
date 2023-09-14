# PHASE-1-PROJECT

by Cleve Ragira Mwebi

Overview
This project aims to dissect movie data to generate strategic insights for Microsoft's entrance into film. The key business goal is determining success factors and potential openings within the industry. The data encompasses movie titles, release years, genres, ratings, votes, studios, and domestic and international earnings. Techniques like data visualization, correlation analysis, and studio assessments are utilized. Findings show a weak positive link between ratings and domestic revenue, plus a skewed distribution of domestic earnings. Popular genres are also identified, and top studios ranked by domestic revenue. Recommended focus areas include high-revenue genres, optimal runtimes, partnerships with top studios, and accounting for market trends. In summary, by analyzing critical performance metrics and industry benchmarks, this project derives data-driven intelligence to inform Microsoft's movie venture strategy and prospects for gain.
Business Problem
Microsoft aims to launch a new movie studio but lacks expertise on current market trends. Our objective is to leverage data to recommend optimal film styles and genres for production based on recent box office performance. By analysing metrics on top-grossing movies over the past several years, we can identify patterns related to elements like genre, budget, release timing, and audience demographics. These data-driven insights will inform Microsoft's studio strategy to align film projects with proven formulas for financial success. Our goal is to translate current industry benchmarks into actionable guidance that boosts Microsoft's probability of producing prosperous films.

To tackle this problem, I will be analysing three datasets namely, bom.movie_gross.csv, imdb.title.basics.csv, and imdb.title.ratings.csv. These datasets will help me answer the questions below:
1.	What are the most popular movie genres?
2.	Which movie genres have the highest average ratings?
3.	What is the relationship between movie budget and revenue?
4.	Which movie studios have produced the most successful films?
   
Data Understanding
3 datasets will be used namely bom.movie_gross.csv, imdb.title.basics.csv, and imdb.title.ratings.csv.
1. bom.movie_gross.csv – contains data on title of the movie, domestic and foreign revenue accrued, and year of movie production. 
2. imdb.title.basics.csv – contains data on title of the movie, runtime minutes and genres   
3. imdb.title.ratings.csv – contains the movie id, average rating of the movie and the number of votes for every movie
These datasets contain relevant attributes like genre, studio, and ratings to inform film production decisions and maximize box office success. The target variable - revenue - will be merged from the bom.movie_gross.csv dataset. Key properties are categorical variables such as genres, studios, directors and continuous variables like ratings, budget, revenue. Pre-processing is required to extract, clean, and transform the data into a suitable format for analysis. By combining these datasets and identifying relationships between factors like genre and revenue, we can derive actionable insights to guide Microsoft's studio strategy and film selection. The end goal is optimizing decisions to boost financial performance based on data-driven intelligence about historical trends.

Methods
•	The project made use of both descriptive and analytic techniques in conducting its EDA. 
•	This was done with the help of different python packages such as pandas, numpy, matplotlib, seaborn and others. 
•	Some of the aspects of analysis involved description of trends through visualization and data modelling
•	Modelling of data involved merging of datasets, identifying and dropping missing values.
•	To uncover insights into trends and variable relationships visualizations were used and they included a scatter plot, bar charts, and histogram.

Results
•	The bar chart shows a decreasing trend in annual movie releases, hitting a peak in 2011. This trend analysis can inform business competition and market understanding.
•	The scatter plot indicates a weak positive link between average rating and domestic revenue. There is a skew with most movies having lower domestic earnings, and few achieving high revenues.
•	The histogram displays runtimes predominantly between 80 to 120 minutes, peaking around 100 minutes.
•	The genre distribution bar plot shows Drama, Comedy, and Action as the most prevalent genres. This provides useful audience preference insights for businesses.
•	While these models fit the data well and deliver valuable business intelligence, the results may not generalize beyond this specific dataset. Further validation through expanded analysis and testing is recommended.
•	Overall, the models enable businesses to understand audience trends and preferences for informed movie production and distribution choices.
Conclusions
In summary, this analysis offers useful intelligence on profitable genres, foreign markets, and other industry trends to empower data-driven decision-making. However, limitations exist regarding external variables, time frame, and geographic constraints. Future enhancements could incorporate more diverse data sources, expanded time periods, and global markets to improve scope. Additionally, machine learning models could be leveraged to forecast movie success based on attributes like genre, runtime, cast, budget, release timing, etc. While imperfect, these findings provide meaningful perspective into key drivers and patterns within the complex movie industry landscape. Broadening the analytical techniques will enable more comprehensive insights to inform long-term strategic planning.


Recommendations
1.	Investigate rating connections with revenue, genre, runtime. Determine whether higher ratings increase revenue/popularity. Leverage findings to guide content selection.
2.	Review historical release fluctuations. Identify periods of high/low production and contributing factors. Assist strategic release timing decisions.
3.	Study runtime patterns and trends. Calculate average or preferred durations and correlate with ratings and earnings. Optimize movie length based on insights.
4.	Explore genre popularity over time among audiences. Analyze distribution across movies and consistently in-demand categories. Use to inform production and acquisition choices.
5.	Examine domestic and foreign earnings distributions. Identify factors like genre, studio, release year and ratings driving higher revenues. Pinpoint profitable genres and trends to guide investments.
