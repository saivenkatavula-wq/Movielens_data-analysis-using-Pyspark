# Movielens_data-analysis-using-Pyspark
---

## MovieLens 100k Dataset

This repository contains the MovieLens 100k dataset, a benchmark dataset widely used for research in recommendation systems and collaborative filtering. The dataset includes 100,000 ratings from 943 users on 1,682 movies, collected by the GroupLens Research Project at the University of Minnesota.

### Dataset Details

- **Source**: [MovieLens 100k Dataset](http://files.grouplens.org/datasets/movielens/ml-100k.zip)
- **Ratings**: 100,000 ratings
- **Users**: 943 users
- **Movies**: 1,682 movies
- **Format**: Tab-separated values (TSV)

### Files

- `u.data`: The full u data set, 100,000 ratings by 943 users on 1,682 items. Each user has rated at least 20 movies. Users and items are numbered consecutively from 1. The data is randomly ordered. This is a tab-separated list of:
  - user id
  - item id
  - rating
  - timestamp
- `u.info`: The number of users, items, and ratings in the u data set.
- `u.item`: Information about the items (movies); this is a tab-separated list of:
  - movie id
  - movie title
  - release date
  - video release date
  - IMDb URL
  - 19 genres (each 0 or 1)
- `u.user`: Demographic information about the users; this is a tab-separated list of:
  - user id
  - age
  - gender
  - occupation
  - zip code

### Jupyter Notebook: `dataAnalysisMovieLens_2023.ipynb`

This repository also includes a Jupyter Notebook (`dataAnalysisMovieLens_2023.ipynb`) that provides an in-depth analysis of the MovieLens 100k dataset. The notebook covers various aspects of data exploration and analysis, including:

- **Loading the Dataset**: Instructions on how to load and preprocess the data from the provided files.
- **Exploratory Data Analysis (EDA)**: Visualizations and statistical analysis to understand user behavior, movie popularity, rating distributions, and more.
- **Recommendation System Implementation**: Examples of implementing different recommendation algorithms, such as collaborative filtering and content-based filtering.
- **Performance Evaluation**: Methods to evaluate the performance of recommendation systems using metrics like RMSE, MAE, precision, and recall.

### Usage

This dataset and the accompanying notebook can be used for building and evaluating recommendation systems, collaborative filtering algorithms, and other machine learning models related to user preferences and item ratings. The notebook serves as a comprehensive guide for performing data analysis and implementing recommendation systems using the MovieLens 100k dataset.

### References

For more information and to download the dataset, visit the [MovieLens Dataset page](http://files.grouplens.org/datasets/movielens/ml-100k.zip).

---

