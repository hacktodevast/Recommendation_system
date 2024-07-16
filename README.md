# Movie Recommendation System using Cosine Similarity

![resommendation sytem](https://github.com/01saurabhshukla/Movies-Recommendation-System/assets/88873969/658ab024-9702-4971-a9a6-88f5f868c2c5)


## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Cosine Similarity](#cosine-similarity)
- [Acknowledgments](#acknowledgments)

## Introduction

The Movie Recommendation System using Cosine Similarity is a Python-based application that suggests movies to users based on their preferences. The system utilizes the cosine similarity technique to measure the similarity between movies and provides personalized recommendations to each user.

The goal of this recommendation system is to enhance user experience by suggesting movies that are likely to align with their interests. Whether a user enjoys action-packed blockbusters or heartwarming romantic comedies, this system will analyze their past movie ratings and recommend similar movies they may not have discovered yet.

## Usage

1. Prepare the dataset: You can either use your movie dataset or leverage the provided example dataset.

2. Ensure you have Python installed on your machine.

3. Open a terminal or command prompt and navigate to the project directory.

4. Run the recommendation system:

```bash
streamlit run app.py
```

5. Follow the prompts to input your movie ratings.

6. The system will calculate the cosine similarity between movies and provide personalized recommendations based on your input.

## Dataset

The dataset used for this recommendation system contains movie ratings and features. It should be structured in a format that can be easily read into Python, such as CSV or JSON. Each row represents a movie, and the columns contain features like movie name, genre, and user ratings.

An example dataset is provided in `Dataset/tmdb_5000_credits.csv`, which you can use as a starting point for testing the system. If you opt to use your dataset, ensure it adheres to the appropriate format.

## Cosine Similarity

Cosine similarity is a measure used to determine the similarity between two non-zero vectors in an inner product space. In the context of this recommendation system, it helps identify movies that are similar based on their feature vectors.

To compute the cosine similarity between two movies, the system treats the movie attributes (e.g., genre, ratings) as vectors and calculates the cosine of the angle between these vectors. The closer the cosine similarity value is to 1, the more similar the movies are, and vice versa.

## Acknowledgments

- The Movie Recommendation System using Cosine Similarity is inspired by various tutorials and courses on recommendation systems.
- The example dataset used in this project is sourced from a publicly available movie dataset [[source link](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv)].

Feel free to explore and customize this Movie Recommendation System to fit your specific use case or integrate it into other applications for personalized movie suggestions. Remember, this is just one of many possible approaches to building recommendation systems, and there are numerous opportunities for further improvement and optimization. Enjoy recommending great movies to your users!
