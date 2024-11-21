# "Movies Dataset Analysis and Machine Learning Insights"
 Movies Dataset Analysis and Machine Learning Project
This repository contains a data analysis and machine learning project based on a movies dataset. The project demonstrates data cleaning, exploratory data analysis (EDA), and building machine learning models to gain insights and predict movie-related attributes such as ratings and revenue.

Features of the Project
Dataset Analysis and Cleaning:
Handling missing values in columns like RATING, RunTime, and Gross.
Standardizing data formats in YEAR, VOTES, and GENRE.
Removing unnecessary characters (e.g., \n, commas) for clean data.
Exploratory Data Analysis (EDA):
Visualizations of ratings, genres, and movie runtimes.
Trends in movie releases over the years.
Relationship between votes, gross revenue, and ratings.
Machine Learning Applications:
Predicting movie ratings based on features like GENRE, RunTime, and VOTES.
Exploring revenue prediction using attributes like RATING and GENRE.
Dataset Description
The dataset contains information about movies and shows, including their titles, genres, ratings, votes, and revenue. Below is an overview of the dataset's attributes:

Feature	Description
MOVIES	Title of the movie/show.
YEAR	Year of release (may include ranges).
GENRE	Genre(s) of the movie/show.
RATING	IMDb rating (out of 10).
ONE-LINE	Short description of the movie/show.
STARS	Cast and crew associated with the movie/show.
VOTES	Number of votes or reviews for the movie/show.
RunTime	Runtime in minutes.
Gross	Gross revenue (may contain missing or inconsistent values).


Cleaning the Data:
Standardized inconsistent year formats (e.g., (2021– ), -2021).
Converted VOTES and Gross columns to numeric formats.
Key Insights from EDA:
Trends in movie ratings over time.
Genres with the highest grossing movies.
Correlation between votes, runtime, and ratings.
Model Building:
Predicted movie ratings with a Random Forest Classifier.
Explored revenue predictions using regression models.
Acknowledgments
Dataset: Custom movies dataset (uploaded by the user).
Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn.
