# NETFLIX-Data-Visualization
A comprehensive visualization of Netflix's data, showcasing patterns, trends, and insights about user behavior, content preferences, and streaming patterns.

![](https://upload.wikimedia.org/wikipedia/commons/thumb/6/69/Netflix_logo.svg/2560px-Netflix_logo.svg.png)

# About Dataset:
Netflix is one of the most popular media and video streaming platforms. They have over 8000 movies or tv shows available on their platform, as of mid-2021, they have over 200M Subscribers globally. This tabular dataset consists of listings of all the movies and tv shows available on Netflix, along with details such as - cast, directors, ratings, release year, duration, etc.<br>
- show_id', 'type', 'title', 'release_year', 'listed_in', and 'description' columns have no missing values.

- 'director' column has 2634 null values, indicating that the director information is missing for those entries.

- 'cast' column has 825 null values, indicating that the cast information is missing for those entries.

- 'country' column has 831 null values, indicating that the country information is missing for those entries.

- 'date_added' column has 10 null values, suggesting that the date when the title was added to Netflix is missing for those entries.

- 'rating' column has 4 null values, implying that the rating information is missing for those entries.

- 'duration' column has 3 null values, indicating that the duration information is missing for those entries.

[Notebook](https://github.com/khushiyadav2022/NETFLIX-Data-Visualization/blob/2e446117f4ccdaa04967876c4b9336ad12bb75df/netflix-data-visualization%20(1).ipynb)<br>
[Tableau Dashboard](https://github.com/khushiyadav2022/NETFLIX-Data-Visualization/blob/d355b0e91abae7540460d7b8b3d766e02909a69b/NETFLIX%20Data%20Visualization.twbx)

# Task:
- Content Type Analysis
- Director Analysis
- Country Analysis
- Release Year Analysis
- Rating Analysis
- Duration Analysis
- Genre Analysis
- Text Analysis

# Methodology:
**Data Understanding:** Dataset have 8807 rows and 12 columns. Null values in 6 columns.

**Data Preprocessing:** Here we change the datatype where needed. Dealing with missing value.

**Data Visualization:** Completed all tasks by different visualization.

# Conclusion:
- The majority of the content in the dataset consists of movies (6131 titles), while TV shows make up a smaller portion (2676 titles).
- The top 10 most prolific directors on Netflix are Rajiv Chilaka, Raúl Campos, Jan Suter, Suhas Kadav, Marcus Raboy, and Jay Karas, indicating their significant contribution to the Netflix content library.
- The United States has the highest number of titles on Netflix, followed by India, the United Kingdom, Japan, and South Korea, highlighting the top contributing countries to the platform's content.
- The year 2018 had the highest number of releases (1147 titles), followed by 2017 (1032 titles) and 2019 (1030 titles), making them the top three highest release years.
- TV-MA is the most common content rating, followed by TV-14, R, and PG-13, indicating the prevalence of mature and adult-oriented content on Netflix.
- The average duration of movies is approximately 99.53 minutes, while the average duration of TV shows is approximately 1.76 seasons.
- Approximately 46.78% of titles are classified as positive based on sentiment analysis, while 43.61% are classified as negative.
- The top five genres on Netflix are International Movies, Dramas, Comedies, International TV Shows, and Documentaries.
