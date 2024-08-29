
# Cinematic Genius: Movie Recommender System

## Overview

Cinematic Genius is a movie recommender system that leverages collaborative and content-based filtering techniques to provide personalized movie recommendations. The application allows users to search for movies by title, view detailed information about recommended movies, and explore recommendations based on their preferences. The system uses advanced machine learning techniques and integrates with The Movie Database (TMDb) API to fetch additional movie details.

## Features

- **Movie Search**: Search for movies by title using an intuitive search bar.
- **Recommendation Algorithms**: Supports both collaborative filtering and content-based filtering for personalized recommendations.
- **Movie Details**: Displays detailed information about recommended movies, including title, release date, rating, main characters, and a movie poster.
- **Responsive UI**: Provides a user-friendly interface using Streamlit, allowing easy interaction and exploration of movie recommendations.
- **Hybrid Recommender System**: Combines collaborative and content-based filtering for improved recommendation accuracy.

## Technologies Used

- **Streamlit**: For building the interactive web application.
- **Pandas**: For data manipulation and analysis.
- **Scikit-learn**: For implementing machine learning algorithms like TruncatedSVD and cosine similarity.
- **Requests**: For making API requests to The Movie Database (TMDb) for movie details.
- **Pickle**: For loading preprocessed movie data.

## Installation

To set up the project locally, follow these steps:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Ishu011/Cinematic-Genius-Movie-Recommender-System.git
   cd Cinematic-Genius-Movie-Recommender-System


  **Set Up a Virtual Environment (optional but recommended):**

python -m venv venv

source venv/bin/activate  # On Windows use `venv\Scripts\activate`

**Install Required Packages:**


pip install -r requirements.txt

**Obtain TMDb API Key:**

Sign up at The Movie Database and get your API key.

Replace the placeholder API key in the code with your own key.

**Prepare Data:**

Place your movies_metadata.csv, ratings_small.csv, and movie_dict_with_titles.pkl files in the project directory.

**Run the Application:**


streamlit run app.py

**Usage**

Search for a Movie:

Enter the movie title in the search bar and select a movie from the list.

Get Recommendations:

Choose the recommendation type (collaborative or content-based) and the number of recommendations.

Click the "Recommend" button to view personalized movie recommendations.

View Movie Details:

For each recommended movie, view detailed information including the poster, title, release date, rating, main characters, and an overview.

**Contributing**

Contributions to the project are welcome! To contribute, please fork the repository and create a pull request with your changes. Ensure that your code adheres to the project's coding standards and includes appropriate tests.

**License**
This project is licensed under the MIT License - see the LICENSE file for details.

