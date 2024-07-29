# Movie Recommendation System

**Recommender System** is a system that predicts or filters preferences according to the user's choices. Recommender systems are used in various domains, including movies, music, news, books, and products. They produce a list of recommendations using either collaborative filtering or content-based filtering.

## Types of Filtering

- **Collaborative filtering:** Builds a model from the user's past behavior and similar decisions made by other users to predict items of interest.
- **Content-based filtering:** Uses a series of characteristics of an item to recommend additional items with similar properties based on the user's past preferences.

This project develops a basic recommendation system by suggesting movies that are most similar to a user's movie choice.

## Project Structure

1. **Import Libraries**
2. **Import Dataset**
3. **Feature Selection**
4. **Feature Text Conversion to Tokens**
5. **Similarity Score Calculation using Cosine Similarity**
6. **Movie Name Input and Closest Match Validation**
7. **Recommendation Score Calculation**
8. **Sort and Display Recommended Movies**

## Dependencies

- pandas
- numpy
- scikit-learn
- difflib

## Instructions

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/th3varun/Movie-Recommendation-System.git
   cd movie-recommendation-system

2. **Install Dependencies:**
   ```sh
   pip install -r requirements.txt

1. **Run the Jupyter Notebook:**
   Open the `Movie_Recommendation_System.ipynb` file in Jupyter Notebook or JupyterLab to see the complete analysis and   
   results.

## Data

The dataset used for this project can be found `here`. It includes the following features:

1. Movie_Genre
2. Movie_Keywords
3. Movie_Tagline
4. Movie_Cast
5. Movie_Director
6. Movie_Title
7. Movie_ID

## Results

### Feature Selection

The features used for this recommendation system are:

1. Movie_Genre
2. Movie_Keywords
3. Movie_Tagline
4. Movie_Cast
5. Movie_Director

## Cosine Similarity

The similarity score is calculated using cosine similarity, which computes the L2-normalized dot product of the feature vectors.

## Movie Recommendation

Given a favorite movie name, the system finds the closest match and recommends the top 30 most similar movies. Additionally, a top 10 recommendation system is implemented to provide more concise suggestions.

## License

This project is licensed under the MIT License.

## Acknowledgments

1. The dataset was sourced from the [YBI Foundation] (https://github.com/YBI-Foundation/Dataset/blob/main/Movies%20Recommendation.csv).
2. Special thanks to the creators and maintainers of the dataset.


