# Netflix-Data-Analysis
Project Overview
This project involves an Exploratory Data Analysis (EDA) on a dataset of over 9,000 movies. The analysis aims to understand patterns in movie genres, popularity, and ratings to provide insights that could help in making informed business decisions, similar to how Netflix utilizes data science and machine learning for recommendation models.

Dataset
The dataset (mymoviedb.csv) contains approximately 9,827 movie records with the following columns:
Release_Date: The date the movie was released.
Title: The name of the movie.
Overview: A brief summary of the movie.
Popularity: A score representing the movie's popularity.
Vote_Count: Number of votes received.
Vote_Average: Average rating of the movie.
Original_Language: The language the movie was originally filmed in.
Genre: Categorical genres associated with the movie.

Key Analysis & Insights
The following questions were addressed during the analysis:
Most Frequent Genre: Drama is the most frequent genre in the dataset.
Highest Vote Average: Kung Fu Master Huo Yuanjia has the highest average vote of 10.0.
Highest Popularity Movie: Spider-Man: No Way Home. Its genres are Action, Adventure, Science Fiction.
Lowest Popularity Movie: The United States vs. Billie Holiday. Its genres are Music, Drama, History.
Year with Most Filmed Movies: 2021 was the year with the most movie releases in this dataset.

Exploratory Data Analysis (EDA) Steps
The analysis performed in the Netflix data analysis.ipynb notebook includes:
Data Cleaning: Handling data types (specifically converting Release_Date to datetime and extracting the year).
Handling Multi-valued Attributes: Splitting and "exploding" the Genre column to count individual genre occurrences accurately.

Data Visualization: * Distribution of genres using count plots.
Distribution of average votes.
Histogram of movie releases over the years.
Outlier Detection: Identification of significant outliers in the Popularity column.

Conclusion
The data highlights that Drama remains a dominant genre in terms of volume, and 2021 saw a peak in movie releases within this dataset. Popularity metrics are heavily influenced by major blockbuster releases like Spider-Man: No Way Home, while high ratings can sometimes be found in niche martial arts films.
