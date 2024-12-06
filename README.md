# Content-Based Movie Recommender System
This repository contains a Content-Based Movie Recommender System built using Streamlit for an interactive and user-friendly web interface. The system leverages the TMDB 5000 Movie and TMDB 5000 Credits datasets from Kaggle to recommend movies based on cosine similarity between feature vectors.

This project was undertaken as a personal project to apply and enhance my knowledge of machine learning, data preprocessing, and web application development.

Features
Content-Based Recommendations: Suggests movies similar to a user-selected movie.
Dataset Integration: Uses TMDB 5000 Movie and TMDB 5000 Credits datasets for rich metadata, including actors, directors, and genres.
Streamlit Web Interface: An intuitive and interactive front-end for seamless user interaction.
Methodology

## Dataset
Datasets sourced from Kaggle:
TMDB 5000 Movies: Contains movie details like titles, genres, overview, etc.
TMDB 5000 Credits: Provides information on cast and crew (actors, directors, etc.).

## Preprocessing
Cleaned and combined datasets for feature engineering.
Key features: Genres, Keywords, Director, and Top Actors.
Recommendation Engine

Employed Cosine Similarity to calculate similarity between movies based on feature vectors.
Movies with the highest similarity scores are recommended.
Streamlit Application

Built a responsive front-end using Streamlit.
Users can select a movie from a dropdown and view recommended movies instantly.
Installation
Follow these steps to set up the project locally:

Clone the Repository

bash
Copy code
git clone https://github.com/yourusername/movie-recommender-system.git  
cd movie-recommender-system  
Install Dependencies
Create a virtual environment (optional but recommended):

bash
Copy code
python -m venv env  
source env/bin/activate  # On Windows: env\Scripts\activate  
Install required Python packages using the provided requirements.txt file:

bash
Copy code
pip install -r requirements.txt  
Run the Application

bash
Copy code
streamlit run app.py  

##Requirements
The following Python packages are required and listed in the requirements.txt file:

numpy
pandas
scikit-learn
seaborn
matplotlib
nltk
streamlit

## Usage
Open the Streamlit app in your browser.
Select a movie from the dropdown menu.
View recommendations based on your selection.

##Datasets
TMDB 5000 Movies
TMDB 5000 Credits
Both datasets are available on Kaggle.

## Technologies Used
Python
Pandas for data manipulation
Streamlit for web development
Scikit-learn for cosine similarity computation

##Screenshots
Add relevant screenshots of your Streamlit app here.

## Future Enhancements
Add user ratings and collaborative filtering for hybrid recommendations.
Incorporate a search bar for better navigation.
Deploy the app using platforms like Heroku or Streamlit Cloud.

##Contributing
As this is a personal project, contributions are welcome or any kind of feedbacks. Feel free to fork the repository and create a pull request if you'd like to improve or extend the project.

