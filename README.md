# Movie Recommendation System

This project implements a movie recommendation system using natural language processing and cosine similarity. It utilizes movie metadata such as genres, keywords, cast, and crew to generate tags for movies and then recommends similar movies based on user input.

## Dependencies

- Python 3.x
- numpy
- pandas
- nltk
- scikit-learn

## Data Sources
The system uses the following datasets:

tmdb_5000_movies.csv: Movie metadata
tmdb_5000_credits.csv: Movie credits

# Data Preprocessing
The code performs the following preprocessing steps:

-Merging movie and credit datasets
-Extracting genres, keywords, cast, and crew information
-Stemming and lowercasing text data
-Vectorizing text using CountVectorizer

# Recommendation Algorithm
The recommendation algorithm is based on cosine similarity between movie tags. Tags are generated from movie overviews, genres, keywords, cast, and crew information.


## Installation

1. Clone the repository:

```bash
git clone https://github.com/Vaibhav-2401/movie-recommendation.git
cd movie-recommendation
