# Movie Recommendation System

![Movie Recommendation System](https://image.tmdb.org/t/p/w500/IMAGE_URL_HERE)

This is a Movie Recommendation System application built using [Streamlit](https://streamlit.io/), which recommends movies based on the movie you select from the dropdown.

## How it Works

1. A list of movies and their similarities is loaded from the `movies_list.pkl` and `similarity.pkl` files, respectively.

2. You can select a movie from the dropdown list of available movies.

3. Click on the "Show Recommend" button to get the top 5 recommended movies based on the selected movie's similarity.

4. The recommended movies' names and their posters will be displayed below the button.

## Prerequisites

Before running the application, make sure you have the following:

- Python installed on your system
- The required libraries mentioned in `requirements.txt` installed. You can install them using the following command:

  ```
  pip install -r requirements.txt
  ```

## How to Run

1. Clone this repository to your local machine.

2. Make sure you have the necessary Python libraries installed as mentioned in the prerequisites.

3. Run the Streamlit app using the following command:

   ```
   streamlit run app.py
   ```

4. The app will open in your default web browser, and you can start exploring the Movie Recommendation System.

## Credits

- The movie data and posters are fetched using [The Movie Database (TMDb) API](https://www.themoviedb.org/).

## Note

- This Movie Recommendation System uses similarity scores to recommend movies. The effectiveness of the recommendations depends on the quality of the similarity scores and the movie dataset used.

- The application may not work as expected if the required `movies_list.pkl` and `similarity.pkl` files are missing or if there are any issues with the TMDb API.

Feel free to explore, modify, and improve the Movie Recommendation System according to your needs and preferences. If you encounter any issues or have suggestions for improvement, please feel free to contribute or reach out to the project maintainers. Happy movie recommending!
