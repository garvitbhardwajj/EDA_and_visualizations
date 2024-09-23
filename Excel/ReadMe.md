# Entertainment

### **CinemaScope Analytics: Unveiling the Dynamics of Movie Success**

### **Background:**

Hollywood Insights Inc. is a data analytics firm specializing in the film and entertainment industry. The company provides in-depth analysis and insights into movie trends, box office earnings, and audience preferences. With an extensive dataset covering various aspects of the movie industry, including movie titles, genres, directors, stars, production companies, budgets, gross earnings, and IMDb scores, Hollywood Insights Inc. plays a crucial role in guiding film studios, independent filmmakers, and media analysts in making informed decisions. As the film industry evolves with emerging trends and changing audience tastes, the need for comprehensive data analysis becomes increasingly vital for predicting success, understanding market dynamics, and identifying key factors that contribute to a movie's popularity and financial success.

### **Objective:**

The project aims to perform a thorough analysis of Hollywood Insights Inc.'s comprehensive movie dataset to uncover insights into the dynamics of the movie industry. Students will use advanced Excel techniques to explore various facets of the dataset, including trends in movie genres, financial analysis of movie budgets and earnings, and the impact of directors and stars on movie success. Key tasks involve data cleaning, manipulation, visualization, and the creation of an interactive dashboard that captures the essence of the movie industry's trends and patterns. This project is intended to enhance Hollywood Insights Inc.'s ability to provide strategic guidance to its clients, enabling better decision-making in film production, marketing, and distribution. The analysis will also contribute to understanding the evolving landscape of the movie industry, potentially influencing future trends in filmmaking and audience engagement.

### **Data Source:**

[movies.csv](https://prod-files-secure.s3.us-west-2.amazonaws.com/d1e1bc70-9ede-4c69-84fd-42c5605803a0/b6a256a5-ab42-4e44-a91a-c9ec379d5eef/movies.csv)

The "movies.csv" file contains data about various movies. Here's an overview of its structure and the type of data it includes:

1. **name**: Movie name (String)
2. **rating**: Movie rating (String)
3. **genre**: Genre of the movie (String)
4. **year**: Year of release (Integer)
5. **released**: Release date (String, includes country)
6. **score**: IMDb score (Float)
7. **votes**: Number of votes on IMDb (Float)
8. **director**: Director's name (String)
9. **writer**: Writer's name (String)
10. **star**: Main star's name (String)
11. **country**: Country of origin (String)
12. **budget**: Production budget (Float)
13. **gross**: Gross earnings (Float)
14. **company**: Production company (String)
15. **runtime**: Runtime in minutes (Float)

### **Part 1: Excel Data Analysis: Manipulation, Formulas and Functions**

1. **Missing Data Handling:** Identify and address missing data in the movies dataset. Are there any patterns in the missing data that can be noted?
2. **Data Sorting and Filtering:** Sort the movies by year of release and by gross earnings. Then, filter the dataset to show only movies with an IMDb score greater than 8.0.
3. **Analysis of Movie Genres:** Analyze the distribution of movies across different genres. Which genre has the most movies, and which has the least?
4. **Budget and Gross Earnings Comparison:** Compare the budget and gross earnings of movies. Create a scatter plot to visualize if there's a correlation between them.
5. **IMDb Score Categorization:** Categorize movies into 'High', 'Medium', and 'Low' based on their IMDb scores. Define the thresholds for these categories.
6. **Country-wise Movie Production:** Analyze which countries have produced the most movies. Create a pie chart to represent this data.
7. **Director Analysis:** Who are the top 5 directors with the highest average gross earnings? Use formulas to calculate and sort this information.
8. **Runtime Analysis:** Calculate the average runtime of movies. How does this vary across different genres?
9. **Top Grossing Movies by Year:** Identify the top grossing movie of each year in the dataset.
10. **Rating Popularity Over Time:** Analyze how the popularity of different movie ratings (G, PG, PG-13, R, etc.) has changed over the years.
11. **Conditional Formatting for High Budget Movies:** Use conditional formatting to highlight movies with budgets above a certain threshold.
12. **Star Impact Analysis:** Investigate if there's a trend between the main star of a movie and its gross earnings or IMDb score.
13. **Profitability Calculation:** Create a new column to calculate the profitability of each movie (gross earnings minus budget).
14. **Decade-wise Movie Analysis:** Categorize movies into decades based on their release year and analyze the trend of average movie scores and gross earnings per decade.
15. **Pivot Table for Genre Analysis:** Use a pivot table to analyze the average budget and gross earnings for each genre.
16. **Correlation Analysis:** Determine if there's any correlation between the runtime of a movie and its IMDb score.
17. **Budget Evolution Over Time:** Analyze how the average movie budget has changed over the years.
18. **Top Companies in Movie Production:** Which production companies have released the most movies? Create a bar chart to represent this data.
19. **Analysis of Movie Release by Month:** Investigate if there is a preferred month or season for releasing movies. Does this trend differ by genre?
20. **Score-based Movie Segmentation:** Segment movies into different categories based on their IMDb score and analyze the average budget and gross earnings in each segment.
21. **Time-Series Analysis of Genre Popularity:** Conduct a time-series analysis to evaluate the popularity of movie genres over the years. (Organize the data by year and genre, then calculate the number of movies or total gross earnings per genre per year. Create a line chart or area chart to visualize the trends over time.)
22. **Predictive Analysis for Future Gross Earnings:** Use the historical data to predict the future gross earnings of movies based on genre, budget, and IMDb score.(Utilize Excel's advanced forecasting tools.)
23. **Revenue and Budget Ratio Analysis Over Time**: Calculate and analyze the ratio of total yearly gross earnings to the total yearly budgets of all movies released each year. How has this ratio evolved over the years covered in the dataset?(Aggregate data year-wise, calculate the total gross earnings and total budgets for each year, and then compute the ratio. Then conduct a trend analysis to understand how this profitability indicator has changed over time. Creating a line chart to visualize this trend would be essential.)
24. **Network Analysis of Directors and Stars:** Analyze the network of collaborations between directors and stars. Identify which pairs of directors and stars most frequently work together and the average gross earnings of their movies. (Use advanced data manipulation to create this matrix and then apply functions to calculate frequencies and averages.)

(Note: Show Visualizations wherever possible in Part 1)

### **Part 2: Building an Excel Dashboard**

Develop a comprehensive and interactive Excel dashboard that integrates key metrics and insights derived from the "movies.csv" dataset. The dashboard should provide a holistic view of the movie industry trends, focusing on movie performance, genre popularity, director and star impact, and financial analysis of movie earnings.

### **Key Elements to Include:**

1. **Movie Performance Overview**:
    - Display key metrics like total number of movies, average IMDb score, and distribution of movies by rating. Include a breakdown of movies by decade.
2. **Genre Popularity Tracker**:
    - Include metrics such as the number of movies per genre, average gross earnings by genre, and a ranking of genres based on popularity and financial success.
3. **Director and Star Analysis Panel**:
    - Visualize key data points such as top directors and stars based on average gross earnings and IMDb scores. Include a feature to select a director or star to view their movie portfolio.
4. **Financial Analysis of Movies**:
    - Create a financial summary showing total gross earnings, average budget, and profitability of movies. Include a comparison of budget versus gross earnings for top-performing movies.
5. **Interactive Features**:
    - Implement slicers, dropdowns, and timeline controls to allow users to filter data across different dimensions (e.g., time periods, genres, directors, stars). Ensure functionality for dynamic interaction with the data.
6. **Design and Usability**:
    - Ensure the dashboard is user-friendly, with a clean layout, coherent color scheme, and clear labels. Use dynamic charts and graphs for visualization, such as scatter plots for budget vs. gross earnings, bar charts for genre analysis, and line charts for trend analysis over time.
