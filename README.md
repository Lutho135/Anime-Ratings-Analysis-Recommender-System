## ⛩️Anime Ratings 〽️Analysis & 🤖Recommender System[[
https://www.bing.com/images/search?view=detailV2&ccid=ErfTselF&id=6311EC843F71AFB33143677317C55D29F3DE1D0D&thid=OIP.ErfTselFpyGTbFn-ZHVibQHaEu&mediaurl=https%3a%2f%2fwallpapercave.com%2fwp%2fwp5306618.jpg&cdnurl=https%3a%2f%2fth.bing.com%2fth%2fid%2fR.12b7d3b1e945a721936c59fe6475626d%3frik%3dDR3e8yldxRdzZw%26pid%3dImgRaw%26r%3d0&exph=850&expw=1332&q=anime+pictures+boy+and+girl+collage+of+6&simid=608034359298891349&FORM=IRPRST&ck=71C062AD039D2F6E54C2170A97C337D9&selectedIndex=70&itb=0



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
