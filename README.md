# Recommendation System - Unsupervised Learning Project
This repository contains a Python-based recommendation system that uses unsupervised learning techniques, specifically focusing on simple and collaborative filtering approaches. The project is divided into two sections:

## Sections Overview:
Section 1: Simple Recommendation System using Python

Section 2: Collaborative Filtering Recommendation Model

- Section 1: Simple Recommendation System using Python
In this section, we will develop a basic recommendation system using Python and pandas. The goal is to suggest items that are most similar to a given item. We will utilize the corrwith() method from pandas to compute correlations between two pandas series, which will help identify items that are most similar.

Objective: To provide a basic recommendation by identifying items with the highest correlation.

Approach:

Use pandas to load and manipulate data.

Calculate correlations between items (e.g., movies or products).

Sort and suggest the most similar items.

Code: You can find the code for this section in the following notebook:
Recommendation Sys.ipynb

- Section 2: Collaborative Filtering Rec
In this section, we will explore collaborative filtering, a popular technique used in recommendation systems. Collaborative filtering is based on user behavior data, such as ratings or interactions with products.

There are two main types of collaborative filtering:

1. Memory-based collaborative filtering:

User-Item Filtering: Recommends items based on user similarities.

Item-Item Filtering: Recommends items based on item similarities.

2. Model-based collaborative filtering:

Singular Value Decomposition (SVD): A matrix factorization technique to reduce the dimensionality of the data.

SVD++: An extension of SVD that incorporates implicit feedback (such as clicks or views).

Code: You can find the code for this section in the following notebook:
Collaborative Filtering Recommender Model.ipynb

### Dataset: Ratings of Electronics
This project uses the "Ratings of Electronics" dataset, which can be downloaded from Kaggle. The dataset includes ratings from users for various electronic products. It is used in the collaborative filtering approach to generate personalized recommendations.

Dataset Link: Ratings of Electronics - [Kaggle](https://www.kaggle.com/datasets/pritech/ratings-electronics?resource=download)
