# Unsupervised-ML_Project_Clustering-Songs

Moosic is a little start-up that creates playlists curated by music experts and specialists in old and new trends. Users can subscribe to their website and listen to these playlists through their preferred Music App (be it Spotify, Apple Music, YouTube Music…). They love the fact that their playlists have a personal touch and that each playlist encapsulates a certain “mood” or “style”.

But business is scaling up fast and the music experts are slow in creating new playlists. Here we have a clear mission: use Data Science to add a degree of automatisation to the creation of playlists.

We're using a dataset that has been collected from the Spotify API and contains the audio features (tempo, energy, danceability…) for a few thousand songs and use a basic clustering algorithm such as K-Means to divide the dataset into a few clusters (which will become playlists).

## Business Questions

- _Are Spotify’s audio features able to identify “similar songs”, as defined by humanly detectable criteria?_ 
When you listen to two rock ballads, two operas or two drum & bass songs, you identify them as similar songs. Are these similarities detectable using the audio features from Spotify? 

- _Is K-Means a good method to create playlists?_ 
Would you stick with this algorithm moving forward, or explore other methods to create playlists?
