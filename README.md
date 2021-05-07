# musicrecommender
Created a music recommendation tool relying on machine learning to identify similar songs

## Outline
The task was to create a working MVP for a music recommendation company.
The company wanted to recommend songs to it's user based on their listening interest.
The user inputs a song title, and the programm will check wether or not this song is currently in the hot 100.
If it is in the hot 100, the program will recommend another top 100 song.

If it is not in the hot 100, the programm will analyse the audiofeatures of the song via the spotify api.
It will then run the audiofeatures through a machine learning clustering algorithm, and sort the song into a cluster.
The program will then recommend a song with similar audio features, based on the clusters.

The machine learning algorithm is based on 10.000 songs scraped via the spoitfy api, that are used to create initial clusters.


To run the programm do the following:

- Clone repo
- Run the "clustering_songs_and_recommendation.ipynb" jupyter notebook stored in the notebooks folder
- Change paths in the file to the local paths that the data in you data folder is stored in
- Run the whole notebook. It will cluster the songs, run the machine learning algorithm, and the last cell is the function for the song recommender
- Call the song recommender function and get a recommendation from more than 10.000 songs stored in the database!


Have fun using the program!

Yours truly,
Thamo
