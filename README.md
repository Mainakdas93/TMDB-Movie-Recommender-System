# Category-Based TMDB Movie Recommender Project

# Overview
Welcome to the Category-Based TMDB Movie Recommender project! This project leverages a dataset from TMDB (The Movie Database) available on Kaggle to provide personalized movie recommendations to users based on their selected movie. The recommendation system is built using Jupyter Lab, incorporating various data preprocessing and analysis techniques, including exploratory data analysis (EDA) with scikit-learn and NLTK (Natural Language Toolkit).

# Data Sources
The project utilizes a dataset sourced from Kaggle, specifically the TMDB dataset. This dataset includes essential information about movies, such as genres, movie ID, keywords, title, overview, cast, and crew details.

# Recommendation System
## Features Considered
The recommendation system incorporates multiple features to enhance the accuracy and relevance of movie suggestions. These features include:

*Genre*: Categorizes movies based on their genres.
*ID*: Unique identifier for each movie in the dataset.
*Keywords*: Important keywords associated with each movie.
*Title*: The title of the movie.
*Overview*: A brief summary of the movie.
*Cast* and *Crew*: Extracting information from the top three actor names and the director name.

# Text Processing
To unify and process the textual data, the project employs the PorterStemmer library from NLTK for stemming words. This step is crucial for improving the model's accuracy by reducing words to their root forms.

# Vectorization and Similarity
Scikit-learn's Count Vectorizer is utilized to convert the processed textual data into a numerical format suitable for machine learning. The cosine similarity metric is then employed to determine the similarity between movies, allowing for the identification of the top 5 K-nearest neighbors (KNN) to the user's selected movie.

# Implementation
The project is implemented in Jupyter Lab, streamlining the entire process from data exploration to model building. PyCharm is utilized for code-app development, ensuring an efficient and organized workflow. The final output is transformed into an interactive web application using Streamlit.

# Deployment
The application is deployed using Heroku, providing users with a user-friendly interface to interact with the movie recommendation system. Users can input their favorite movie, and the system will promptly generate and display the top 5 recommended movies based on the selected film.

# How to Use
Input: Provide the name of your favorite movie.
Output: Receive a list of the top 5 recommended movies based on the selected movie's features.
Explore the repository to delve into the codebase, understand the data processing steps, and witness the power of the Category-Based TMDB Movie Recommender.

Feel free to contribute, offer suggestions, or report issues. Enjoy discovering new movies tailored to your taste!
