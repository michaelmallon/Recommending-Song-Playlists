# Recommending-Song-Playlists

<a href="https://github.com/michaelmallon/Recommending-Song-Playlists"><img src="spotify_logo.png" align="left" alt="Spotify Logo" height="200" /></a>


**This Project is my Final Year Project for Computer Science with Data Science in UCD**


&nbsp; 

The outcome of the project was a playlist continuation system ran through Juypter Notebooks in Python.

The results are reproducable, to run them on a different system run each python notebook from folders 000-300 and their contents in numberical order from 000-?00.



&nbsp;

The data was provided via the ACM RecSys Challange (2018),

The dataset provided in a .JSON format contained contained 1 million unique playlists,

2.2+ million unique songs with 66+million songs in total,

Additional audio features were also scraped for each of the 2.2+ million. unique songs in the dataset

## Contents

<!-- START_TOC -->

### [Part 1 : Data Preperation](000_Preperation)

* [Loading Playlists](000_Preperation/100_load_Playlist.ipynb)
* [Loading Tracks](000_Preperation/110_load_Tracks.ipynb)
* [Loading Track Elements](000_Preperation/120_load_Track_elems.ipynb)
* [Loading Audio Features](000_Preperation/130_load_Audio_features.ipynb)



### [Part 2 : Data Analysis](100_Analysis)

* [Playlist Analysis](100_Analysis/100_Playlist_Analysis.ipynb)
* [Track Analysis](100_Analysis/110_Track_Analysis.ipynb)
* [Track Elements Analysis](100_Analysis/120_Track_elems_Analysis.ipynb)
* [Audio Feature Analysis](100_Analysis/130_Audio_feature_Analysis.ipynb)
* [Average Artist Analysis](100_Analysis/200_Average_Artist.ipynb)
* [Average Playlist Analysis](100_Analysis/210_Average_Playlist.ipynb)

### [Part 3 : Data Mining](200_Data_Mining)

* [K-Means Cluster Songs](200_Data_Mining/100_KMeans_Clustering.ipynb)
* [K-Means Clustering Analysis](200_Data_Mining/110_KMeans_Clustering_Analysis.ipynb)
* [Popularity Rankings](200_Data_Mining/200_Popularity_Rankings.ipynb)
* [Popularity Ranking Evalutation](200_Data_Mining/210_Popularity_Ranking_Evaluation.ipynb)
* [K-Means Clustering Playlist & Analysis](200_Data_Mining/300_Playlist_Cluster.ipynb)

### [Part 4 : Recommender System](300_Recommender_System)

* [Preparing Cosine Similarity Dataframe](300_Recommender_System/000_Cosine_Dataframe.ipynb)
