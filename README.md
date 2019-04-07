# Recommending-Song-Playlists

<a href="https://github.com/michaelmallon/Recommending-Song-Playlists"><img src="spotify_logo.png" align="left" alt="Spotify Logo" height="200" /></a>


**This Project is my Final Year Project for Computer Science with Data Science in UCD**
**Michael Mallon - 15438708 - michael.mallon@ucdconnect.ie**

The outcome of the project was a playlist continuation system ran through [Juypter Notebooks](https://jupyter.org)  in Python.

The results are reproducable, to run them on a different system run each python notebook from folders 000-300 and their contents in numberical order from 000-???.
&nbsp;



Detailed in the main is a file requirements.txt which contains all of the packages installed for the project.

To gain access to the data used in this project email: michael.mallon@ucdconnect.ie

&nbsp;

The data was provided via the [ACM RecSys Challange (2018)](https://recsys.acm.org/recsys18/),

The dataset provided in a .JSON format contained contained 1 million unique playlists,

2.2+ million unique songs with 66+million songs in total,

Additional audio features were also scraped for each of the 2.2+ million unique songs in the dataset.

## Contents

<!-- START_TOC -->

### [Part 1 : Data Preperation](000_Preperation)
Loads All of the Dataframes and Saves Them as Pickle Files for Later Analysis
* [Loading Playlists](000_Preperation/100_load_Playlist.ipynb)
* [Loading Tracks](000_Preperation/110_load_Tracks.ipynb)
* [Loading Track Elements](000_Preperation/120_load_Track_elems.ipynb)
* [Loading Audio Features](000_Preperation/130_load_Audio_features.ipynb)



### [Part 2 : Data Analysis](100_Analysis)
2 Performs Advanced Analysis An Each of The Dataframes
* [Playlist Analysis](100_Analysis/100_Playlist_Analysis.ipynb)
* [Track Analysis](100_Analysis/110_Track_Analysis.ipynb)
* [Track Elements Analysis](100_Analysis/120_Track_elems_Analysis.ipynb)
* [Audio Feature Analysis](100_Analysis/130_Audio_feature_Analysis.ipynb)
* [Average Artist Analysis](100_Analysis/200_Average_Artist.ipynb)
* [Average Playlist Analysis](100_Analysis/210_Average_Playlist.ipynb)

### [Part 3 : Data Mining](200_Data_Mining)
Creates Two New Data Mined Features, Popularity Ranking and Clusters
* [K-Means Cluster Songs](200_Data_Mining/100_KMeans_Clustering.ipynb)
* [K-Means Clustering Analysis](200_Data_Mining/110_KMeans_Clustering_Analysis.ipynb)
* [Popularity Rankings](200_Data_Mining/200_Popularity_Rankings.ipynb)
* [Popularity Ranking Evalutation](200_Data_Mining/210_Popularity_Ranking_Evaluation.ipynb)
* [K-Means Clustering Playlist & Analysis](200_Data_Mining/300_Playlist_Cluster.ipynb)

### [Part 4 : Recommender System](300_Recommender_System)
Implements 5 Recommender Systems containing the Project Goal a **Playlist Contunation System**
* [Preparing Cosine Similarity Dataframe](300_Recommender_System/000_Cosine_Dataframe.ipynb)
* [Audio Feature Recommender System](300_Recommender_System/100_Audio_Feature_RS.ipynb)
* [Audio Feature and Popularity Recommender System](300_Recommender_System/200_Audio_Popularity_RS.ipynb)
* [Audio Feature, Popularity and Cluster Recommender System](300_Recommender_System/300_Audio_Popularity_Cluster_RS.ipynb)
* [Song Recommender System](300_Recommender_System/400_Song_Recommender.ipynb)
* [Playlist Continuation System](300_Recommender_System/500_Playlist_Continuation_System.ipynb)
