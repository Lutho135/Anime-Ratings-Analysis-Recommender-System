## ⛩️Anime Ratings 〽️Analysis & 🤖Recommender System

![image](https://github.com/user-attachments/assets/f8a2423b-70da-4504-9d2c-fd60d6783e0e)



Trello: https://trello.com/invite/b/678feaa484f8accb36ff7726/ATTI2d03148c835cac678e9cab516919cc0c62AE427D/unsupervised-learning-project

Overview
Every streaming content has its own viewers and each content has its rating. Viewers leave ratings for the content they like. However, viewers can spend hours scrolling through hundreds, sometimes thousands, of anime titles but never find content they like. Businesses need to provide suggestions based on viewers' likings and needs to create a better streaming environment that boosts revenue and increases the time spent on the website.

About the Dataset
This dataset contains information on user preference data from 73,516 users on 12,294 anime. Each user is able to add anime to their completed list and give it a rating. This dataset is a compilation of those ratings.

anime.csv
anime_id: MyAnimeList.net's unique ID identifying an anime.

name: Full name of the anime.

genre: Comma-separated list of genres for this anime.

type: Movie, TV, OVA, etc.

episodes: Number of episodes in this show. (1 if it's a movie).

rating: Average rating out of 10 for this anime.

members: Number of community members that are in this anime's "group".

rating.csv
user_id: Non-identifiable randomly generated user ID.

anime_id: The anime that this user has rated.

rating: Rating out of 10 this user has assigned (-1 if the user watched it but didn't assign a rating).

Importing Libraries
python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import warnings

warnings.filterwarnings('ignore')
