# Movie Recommender System
A simple yet effective content-based movie recommender system made using Machine Learning. It recommends the top 5 movies and their posters based on the movie the user searches for. The model clubs all categorical data, i.e. genres, overview, keywords, cast, and crew, into a single tag for the movie. Common English language words, such as auxiliary verbs and prepositions are omitted from these tags by applying CountVectorizer. Vectorization gives us the numerical equivalent of the categorical fields included in the discussion. Words like dance, danced, and dancing, which practically signify the same thing are stemmed from their roots using "PorterStemmer" from the "nltk" library.  
We use the cosine distance between the vectors to calculate the similarity between the vectors. The lesser the distance, the more the similarity. Because of this, we get the movies closely related to the movie chosen by the user. 
The web app is created on a local host using the Streamlit library. The basic frontend of the app was made using various features of the Streamlit library, and posters of the recommended movies were added using Tmdb's API. 

Here are a few screenshots on how the app looks like. 

![image](https://github.com/makeitrex10/movie-recommender-system/assets/139851276/17a4c1e2-5eba-447b-a45c-2c0a51c152d5)
![image](https://github.com/makeitrex10/movie-recommender-system/assets/139851276/90a0617d-a294-4751-9828-3f79f70ab41b)
![image](https://github.com/makeitrex10/movie-recommender-system/assets/139851276/eb074d03-84ff-4e62-9e6e-5079bdefd0f4)
![image](https://github.com/makeitrex10/movie-recommender-system/assets/139851276/7339679d-300e-4407-b3d3-7b5c58022342)

# THANK YOU
