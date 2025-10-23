# Movie_Recommender System using Machine Learning
A content-based movie recommendation system that suggests movies similar to a given title using **Natural Language Processing (NLP)** and **cosine similarity**. 


## **Introduction**
The Movie Recommender System project is designed to suggest movies that are most similar to a user’s selected movie using content-based filtering and Natural Language Processing (NLP) techniques. The system leverages textual data such as genres, cast, director, keywords, and movie descriptions to identify similarities between films. By applying cosine similarity on vectorized text features, the model effectively recommends movies with related content and themes, enhancing user discovery and engagement.

## **Dataset**
The dataset used for this project is the **TMDB 5000 Movies and Credits Dataset**, which contains detailed metadata for over 5,000 films, including cast, crew, plot keywords, genres, and production details. The datasets are merged based on movie IDs to create a unified and rich source of information for feature extraction and analysis.

## **Preprocessing**
The preprocessing steps include:

* Extracting key features such as **genres**, **cast**, **crew**, **keywords**, and **overview**
* Cleaning and transforming text data into a uniform format
* Combining these attributes into a single textual representation (“tags”)
* Applying **TF-IDF** or **Bag-of-Words (BoW)** vectorization to convert text into numerical form

## **Model**
The model computes the **cosine similarity** between the vectorized representations of movies to measure their closeness. A recommendation function is then implemented to return the top five most similar movies for any given input title. The system provides highly relevant movie suggestions based on content similarity rather than user ratings.

## **Web Interface (Optional)**
A simple web application can be developed using **Flask** or **Streamlit** to allow users to enter a movie name and view the recommended results instantly, possibly along with movie posters or metadata fetched via the TMDB API.

## **Conclusion**
The Movie Recommender System demonstrates the power of NLP and machine learning in building intelligent recommendation engines. By combining text-based features with similarity metrics, the model efficiently identifies and recommends movies that align with user preferences, offering a personalized and engaging experience.
