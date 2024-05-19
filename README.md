# Movie Recommender System

## Overview
The Movie Recommender System is a Python-based project that provides personalized movie recommendations to users. Leveraging collaborative filtering and content-based filtering techniques, the system analyzes user preferences and movie features to suggest relevant and engaging movie options. This README provides an overview of the project, its functionalities, and instructions for usage.

## Features
- **Personalized Recommendations**: Users receive movie recommendations tailored to their preferences and interests.
- **Interactive User Interface**: The Streamlit web application offers an intuitive interface for exploring movie recommendations.
- **Efficient Decision Making**: Users can quickly discover new movies to watch without the hassle of searching through extensive lists.
- **Comprehensive Movie Data**: The system utilizes a rich dataset containing information about movie titles, genres, keywords, cast, crew, and more.

## Technologies Used
- **Python**: Primary programming language for development.
- **Pandas and NumPy**: Libraries for data manipulation and analysis.
- **Scikit-learn**: Machine learning library for implementing recommendation algorithms.
- **NLTK**: Natural language processing library for text preprocessing tasks.
- **Streamlit**: Web application framework for building interactive user interfaces.
- **Pickle**: Python module for serializing and deserializing Python objects.
- **TMDb API**: The Movie Database API for fetching movie posters and additional movie details.

## Usage
1. **Clone the Repository**: Clone the project repository to your local machine using Git.
   ```bash
   git clone https://github.com/Premaramkarthik/movie-recommendation-system.git
   ```
   
2. **Install Dependencies**: Install the required Python dependencies using pip.
   ```bash
   pip install -r requirements.txt
   ```
   
3. **Run the Application**: Start the Streamlit web application by running the following command in your terminal.
   ```bash
   streamlit run app.py
   ```
   
4. **Interact with the System**: Access the web application through your web browser. Select a movie from the dropdown menu and click the "Show Recommendation" button to view recommended movies along with their posters.

## Data Sources
- The movie data used in the project is sourced from the TMDb 5000 Movie Dataset available on Kaggle.

## Files
- **movie_recommender.py**: Contains the code for the movie recommendation system.
- **app.py**: Streamlit web application code for the user interface.
- **data/**: Directory containing CSV files with movie data.
- **pkl_files/**: Directory containing Pickle files for storing processed data and similarity matrices.

## Acknowledgements
- The TMDb API for providing access to movie data and posters.
- Kaggle for hosting the TMDb 5000 Movie Dataset used in the project.


---

Feel free to customize this README according to your project's specific details and requirements!
