

# Project Introduction: CineSuggest - Your Personalized Movie Recommendation Companion

## Introduction

**Background:**
In a world inundated with an overwhelming variety of movies and TV shows, finding the perfect film to watch can be a daunting task. "CineSuggest" emerges as the solution to this common predicament, offering a seamless and personalized movie recommendation experience. Utilizing the power of machine learning, CineSuggest is designed to cater to your unique cinematic preferences, ensuring that every movie night is a memorable one.

**Project Description:**
"CineSuggest" is a sophisticated machine learning-based movie recommendation system that takes the guesswork out of choosing your next cinematic adventure. This project employs state-of-the-art algorithms to analyze your viewing history, taste, and preferences, making use of a diverse array of data sources, including user ratings, movie metadata, and genre information.

**How it Works:**

1. **Input Your Favorite Movie:** To get started, simply tell CineSuggest about your favorite movie or a few films you've enjoyed in the past.

2. **Machine Learning Algorithm:** The heart of CineSuggest is its powerful machine learning algorithm, which processes your profile data along with movie data from an extensive database.

3. **Recommendation List:** After deep analysis, CineSuggest generates a list of movie suggestions tailored to your preferences, which you can browse and select from.

**API I Used:**
The details of the movies (title, genre, runtime, rating, poster, etc.) are fetched using an API provided by TMDB (The Movie Database). You can find more information about this API at [TMDB API Documentation](https://www.themoviedb.org/documentation/api).

**Check out the live demo:** [CineSuggest Live Demo](https://cine-suggest-personalized-movie-suggestions.streamlit.app/)

- If you can't find the movie you're searching for through auto-suggestions while typing, there's no need to worry. Simply type the name of the movie and press "enter". Even if you make some typos, it should still work fine.

---

## Project Phases

**Phase 1: Data Exploration**
Commencing with a comprehensive examination of the dataset, our primary task is to acquire an in-depth comprehension of the variables and identify potential patterns and correlations.

**Phase 2: Data Preprocessing**
To render the data amenable to machine learning, we will embark on data cleaning, transformation, and normalization. This encompasses addressing missing data, encoding categorical variables, and standardizing numerical features.

**Phase 3: Feature Selection**
We will undertake the judicious selection of pertinent features that significantly contribute to precise predictions while eliminating extraneous noise.

**Phase 4: Model Development**
Leveraging a spectrum of machine learning algorithms, we will engage in the construction of predictive models, fine-tuning them to achieve optimal performance.

**Phase 5: API Integration**
API integration plays a crucial role in our project. We fetch movie details such as title, genre, runtime, rating, poster, and more using an API provided by TMDB (The Movie Database). This integration allows us to enhance the movie recommendation process. You can find more information about this API at [TMDB API Documentation](https://www.themoviedb.org/documentation/api).

**Phase 6: Deployment**
Upon achieving a high-performing model, our focus will shift toward deployment, ensuring that it can be effectively utilized for real-time movie recommendations. For this purpose, we will use Streamlit, a user-friendly web app framework for creating interactive and intuitive interfaces.



---
## Dataset

**Dataset Name:** Top-Rated TMDB Movies Dataset (as of 26-July-2022)

**Dataset Description:**
This dataset consists of information about 10,000 top-rated movies listed on the TMDB (The Movie Database) platform. The data includes details such as movie IDs, titles, genres, original language, overviews, popularity, release dates, vote averages, and vote counts for each movie. It is a valuable resource for anyone interested in analyzing and exploring top-rated movies on TMDB.

**Data Fields:**
The dataset includes the following fields:

1. **ID:** Movie ID number on the TMDB website. (Integer)
2. **Title:** Movie name. (String)
3. **Genre:** Movie genre, which can include categories such as crime, adventure, and more. (String)
4. **Original Language:** The original language in which the movie was released. (String)
5. **Overview:** A summary or description of the movie. (Text)
6. **Popularity:** A measure of the movie's popularity. (Float)
7. **Release Date:** The date on which the movie was released. (Date)
8. **Vote Average:** The average vote or rating given to the movie. (Float)
9. **Vote Count:** The number of votes or ratings the movie has received. (Integer)

**Data Sample:**

Here is a sample of the dataset to illustrate its structure:

| ID   | Title                 | Genre          | Original Language | Overview                                       | Popularity | Release Date | Vote Average | Vote Count |
|------|-----------------------|----------------|-------------------|-------------------------------------------------|------------|--------------|--------------|------------|
| 1    | The Shawshank Redemption | Crime, Drama | English           | Two imprisoned men bond over several years, finding solace and eventual redemption through acts of common decency. | 30.546    | 1994-09-23   | 8.7        | 24112      |
| 2    | The Godfather           | Crime, Drama | English           | The aging patriarch of an organized crime dynasty transfers control of his clandestine empire to his reluctant son.   | 27.137    | 1972-03-15   | 8.6        | 17471      |
| 3    | The Dark Knight         | Action, Crime, Drama, Thriller | English | When the menace known as The Joker emerges from his mysterious past, he wreaks havoc and chaos on the people of Gotham. | 31.835 | 2008-07-16 | 8.6        | 19533      |
| ...  | ...                   | ...            | ...               | ...                                            | ...        | ...          | ...          | ...        |


**Sources of the datasets:**
You can access this dataset on Kaggle at [Top Rated TMDB Movies (10K)](https://www.kaggle.com/datasets/ahsanaseer/top-rated-tmdb-movies-10k).


---
**Similarity Score:**

How does it decide which item is most similar to the item the user likes? Here come the similarity scores.

It is a numerical value ranging between zero to one which helps to determine how much two items are similar to each other on a scale of zero to one. This similarity score is obtained by measuring the similarity between the text details of both of the items. So, the similarity score is the measure of similarity between the given text details of two items. This can be done by cosine similarity.

**How Cosine Similarity Works?**

Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, the higher the cosine similarity.

![70401457-a7530680-1a55-11ea-9158-97d4e8515ca4](https://github.com/NikhilPanda01/CineSuggest_A_Personalized_Movie_Suggestion_System/assets/114555468/6e4ddfe0-5cf8-43b9-ae02-a04cf75f731a)


---
## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://nikhilpanda01.github.io/My_portfolio.io/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nikhil-panda-b78255170/)
