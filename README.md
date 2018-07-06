# song_recommendation_system

Make sure to unzip the data folder before running the python notebook.

This is a very simple song recommendation system. 

# Dataset
We have used the FMA- Music analysis dataset for this task. We used the acoustic features of the song for classification.

# Preprocessing
Since we wanted to make it a binary classification for a starting project, we have created the labels by using 1 and 0. 1 showing that user liked the song and 0 showing that the user disliked the song.

We have created the labels based on a user interest of genres, that is randomized on every run. 
We have also added a bias for the number of 1's that are assigned to the songs in a specific genre. This bias was added because we understand that one cannot like all the songs in a specific genre.

# Models
We have used three different models for classification namely k-Nearest Neighbors, Linear Regression and Multi Layer Perceptron (MLP).

# Results
We have computer accuracy and confusion matrix for all the models and also plotted the graphs of the types of songs that are suggested to the user. 
