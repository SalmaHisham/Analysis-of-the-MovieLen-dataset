# MovieLens Analysis Project

## Overview

This comprehensive team work project explores the MovieLens dataset (1M version) to uncover valuable insights into user behavior, demographics, movie popularity, and community structures. Various tasks, including data preprocessing, clustering, community detection, and recommendation systems, provide a holistic understanding of the dataset.

## Problem Definition

The project addresses multiple tasks to gain a comprehensive understanding of user preferences and behaviors:

1. **Data Preprocessing with MapReduce**
2. **PageRank for Movie Popularity Analysis**
3. **Locality Sensitive Hashing for Similar Movie Discovery**
4. **Clustering**
5. **Community Detection**
6. **Recommendation Systems**

## Dataset

- **Source:** [MovieLens 1M](https://grouplens.org/datasets/movielens/1m/)
- **Content:** User ratings, movie metadata (genres, titles), and user information.
- **Size:** 1M version

## Tools and Technologies

- **Programming Language:** Python
- **Data Processing:** MapReduce
- **Analysis:** PageRank Algorithm, Locality Sensitive Hashing, K-means Clustering, Louvain Method, Matrix Factorization
- **Visualization:** Matplotlib, Seaborn

## Insights

- **Top-Rated Movies:**
  - Identify movies with the highest average ratings.
- **Popular Genres:**
  - Analyze the most popular genres based on total ratings.
- **Gender Preferences:**
  - Visualize user preferences by gender and genre.
- **User Demographics:**
  - Explore user activity by state and genre.

## Tasks

### 1. Data Preprocessing with MapReduce

- **Objective:** Extract key information from the dataset.
- **Implementation:** Use MapReduce to filter and aggregate data.

<img src="https://github.com/SalmaHisham/Analysis-of-the-MovieLen-dataset/assets/55672969/c070bcc7-9a0a-4490-9aca-4b7eeec85593" alt="Image" width="450" height="300"/>

<img src="https://github.com/SalmaHisham/Analysis-of-the-MovieLen-dataset/assets/55672969/be5328e7-6290-47b9-b61b-de6a21e18d60" alt="Image" width="450" height="300"/>

### 2. PageRank for Movie Popularity Analysis

- **Objective:** Rank movies based on user ratings.
- **Implementation:** Construct a graph and apply a modified PageRank algorithm.

<img src="https://github.com/SalmaHisham/Analysis-of-the-MovieLen-dataset/assets/55672969/e1b0dff3-965e-4886-92b7-2ec1d5f02304" alt="Image" width="600" height="400" />

### 3. Locality Sensitive Hashing for Similar Movie Discovery

- **Objective:** Group similar movies based on user ratings.
- **Implementation:** Create high-dimensional vectors and implement LSH for clustering.

<img src="https://github.com/SalmaHisham/Analysis-of-the-MovieLen-dataset/assets/55672969/ec9022cb-be02-4268-8de2-e245cadac7c4" alt="Image" width="600"/>
  
### 4. Clustering

- **Objective:** Understand user preferences and group similar users based on their movie ratings.
- **Task:** Perform clustering on users based on their movie rating patterns.
- **Implementation:** Use K-means clustering on normalized user rating data and analyze resulting clusters.

<img src="https://github.com/SalmaHisham/Analysis-of-the-MovieLen-dataset/assets/55672969/14aa2714-4d50-4b7b-893c-874a5a94efb1" alt="Image" width="600" height="400"/>

### 5. Recommendation Systems

- **Objective:** Develop a recommendation system to suggest movies to users based on their past ratings.
- **Task:** Build and evaluate a movie recommendation system.
- **Implementation:** Implement a collaborative filtering model using matrix factorization and evaluate its performance using RMSE on a split test set.

## Conclusion

This team work analysis provides a thorough understanding of user demographics, movie popularity, similar movie discovery, clustering, community detection, and recommendation systems within the MovieLens dataset.

