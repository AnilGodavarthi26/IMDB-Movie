# IMDB-Movie
Designed and developed a dynamic Power BI dashboard to analyze IMDB movie data across genre, director, rating, revenue, and metascore. Implemented Row-Level Security (RLS) based on film ratings, created calculated DAX measures (Revenue per Minute, Rating Category), and used drillthrough pages and bookmarks to enhance interactivity.
KPI Cards:

1.Total Movies
2.Overall Average Rating
3.Total Revenue (Millions)
4.Average Runtime (Minutes)

Visualizations:

1.Revenue (Millions) by Year (Line Chart): Show trends in revenue over time.
2.Average Rating by Year (Line Chart): Show trends in average movie ratings.
3.Top 10 Genres by Revenue (Bar Chart): Identify the most profitable genres.
4.Top 10 Directors by Total Revenue (Bar Chart): Highlight top-earning directors.
5.Top 10 Movies by Rating (Table Visual): Display the highest-rated movies with their Title, Director, Genre, Rating, Votes, and Revenue.

Performance Deep Dive (e.g., Ratings & Revenue)

1.Scatter Plot: Rating vs. Revenue (Millions): Explore potential correlations. Add Title to tooltips.
2.Histogram/Distribution of Rating: Understand the spread of movie ratings.
3.Histogram/Distribution of Revenue (Millions): Understand the distribution of revenue.
4.Table: Movies by Rating Range: Allow users to filter by rating range and see associated movies.

Actor & Director Analysis

1.Top N Actors by Total Revenue (Bar Chart): Who are the biggest box office draws?
2.Top N Directors by Average Rating (Bar Chart): Which directors consistently deliver highly-rated films?
3.Table: Movies by Selected Actor/Director: When an actor/director is selected, show all their movies, their Year, Rating, and Revenue.
4.Slicer for Actors and Directors: Allow users to select specific individuals.

Genre Analysis

1.Tree Map/Pie Chart: Genre Distribution (by Movie Count or Revenue): Visualize the proportion of different genres.
2.Bar Chart: Average Rating by Genre: Compare how different genres are critically received.
3.Table: Movies by Selected Genre: Show details for movies within a selected genre.
4.Slicer for Genre: Enable filtering by genre.

Slicers:
1.Year Slicer: Allow users to filter data by release year (range slider or list).
2.Genre Slicer: Filter by one or more genres.
3.Director Slicer: Filter by director.
4.Actors Slicer: Filter by actors.
5.Rating Slicer: Filter by rating range.
