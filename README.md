## ⛩️Anime Ratings 〽️Analysis & 🤖Recommender System

![Uploading InCollage_20250203_194436730.jpg…]()



Trello: https://trello.com/invite/b/678feaa484f8accb36ff7726/ATTI2d03148c835cac678e9cab516919cc0c62AE427D/unsupervised-learning-project

Every streaming content has its own viewers and each content has it's rating. Viewers leave some good ratings for the content if they like it. But where does it apply? Viewers can spend hours scrolling through hundreds, sometimes thousands of anime's but never getting a content they like. Businesses need to provide suggestions based on viewers likings and needs in order to create a better streaming environment that boosts revenue and increases the time spent on a website.

# About Data Set

This dataset contains information on user preference data from 73,516 users on 12,294 anime. Each user is able to add anime to their completed list and give it a rating and this dataset is a compilation of those ratings.

anime.csv

anime_id : myanimelist.net's unique id identifying an anime.

name : full name of anime.

genre : comma separated list of genres for this anime.

type : movie, TV, OVA, etc.

episodes : how many episodes in this show. (1 if movie).

rating : average rating out of 10 for this anime.

members : number of community members that are in this anime's "group".

rating.csv


user_id : non identifiable randomly generated user id.

anime_id : the anime that this user has rated.

rating : rating out of 10 this user has assigned (-1 if the user watched it but didn't assign a rating).


# Importing Libraries

import numpy as np

import pandas as pd

import matplotlib.pyplot as plt

import seaborn as sns

import warnings

warnings.filterwarnings('ignore')
