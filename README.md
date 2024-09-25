Movie Genre and Duration Analysis Project
Overview
This project analyzes the relationship between movie genres, their duration, and ratings. Using a dataset of movies, the goal is to identify patterns in the film industry, particularly focusing on which types of movies are rated the highest and how genres with different durations tend to perform. Key insights are drawn from both qualitative and quantitative aspects of movie production and reception.

Key Findings
Highly Rated Genres: Animated movies, which are often expensive and effort-intensive to produce, tend to have the highest ratings with an optimal runtime around 90 minutes.
Risk in Production: Dramas, which are cheaper to produce, are made in higher quantities, but they generally do not perform as well unless they become breakout hits.
Wide Appeal vs. Niche Audiences: Movies targeting a broad audience, like animated films, perform better, while niche genres like Westerns, despite requiring significant investment, tend to have fewer productions and lower ratings.
Duration Matters: Movies with runtimes of around 90 minutes seem to hit a sweet spot in terms of viewer satisfaction, particularly for genres like animation.
Tools and Libraries Used
Python: Primary programming language used for data analysis.
Pandas: For data cleaning, manipulation, and aggregation.
Matplotlib/Seaborn: For data visualization, including bar charts and histograms.
Jupyter Notebook: For writing and executing code, as well as documenting the process.
Installation and Setup
Clone the repository to your local machine:

bash
Copy code
git clone <repository-link>
cd <repository-folder>
Install the required Python libraries:

bash
Copy code
pip install pandas matplotlib seaborn
Ensure you have the dataset in CSV format. For this project, the dataset is assumed to have the following columns:

Genres: Contains movie genres (comma-separated if multiple).
Duration: In the format "X h Y m" (e.g., "1 h 45 m").
Rating: Average user rating for each movie.
Run the Jupyter notebook or Python script to execute the analysis.

How to Use
Data Cleaning: The Duration column is cleaned and converted from hours and minutes to total minutes for analysis.

Genre Filtering: Only genres with 50 or more movies are considered for the analysis to avoid skewing results with underrepresented genres.

Average Rating and Duration:

A pivot table is created to analyze the average rating and duration per genre.
The data is visualized using bar charts and histograms to show the distribution of ratings and movie counts by genre.
Visualization: The results are visualized through bar charts to showcase the number of movies per genre and their average duration.

Results
Average Movie Duration: A chart shows the average movie length for each genre.
Movie Counts: A histogram displays the number of movies in each genre, with only genres containing at least 50 movies being considered.
Conclusion: Movies that invest more time and resources, particularly animations, tend to achieve higher ratings, while niche genres like Westerns tend to have lower ratings and longer durations.
Future Work
Genre Popularity Over Time: Explore how the popularity of certain genres has evolved over time in response to cultural phenomena or major film releases.
External Factors: Investigate how current events (e.g., major historical moments, technological advancements) influence genre trends and movie ratings.
Limitations
The dataset does not include information about budget, release date, or cultural impact, which could further explain the success or failure of certain movies.
Only genres with at least 50 movies were considered, which might leave out some significant but niche genres.



