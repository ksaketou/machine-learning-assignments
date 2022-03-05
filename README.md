# Machine Learning Assignments

This repository contains the three assignments created in terms of the Applied Machine Learning course.  
Below you can see a short description of each one of them.  

## Exploring the Weather in Athens  

This assignment aims to study the weather in Athens during the period from 1955 to 2020. Data from different datasets have been used for this analysis. The assignment explores four different weather scenarios  

* Summer Temperatures
* Evolution of Daily Temperatures
* Extreme Heat Events
* Precipitation

## Belief in Supernatural Evil and Guns  

This assignment aims to study the belief of people in supernatural evil and guns based on the below study conducted in the United States:  
<br>
Christopher G. Ellison, Benjamin Dowd-Arrow, Amy M. Burdette, Pablo E. Gonzalez, Margaret S. Kelley, Paul Froese,
"Peace through superior firepower: Belief in supernatural evil and attitudes toward gun policy in the United States", Social Science Research, Volume 99, 2021, https://doi.org/10.1016/j.ssresearch.2021.102595.  

The assignment attempts to analyze thiw topic the same way the above study does, using the same dataset.

## Dissecting Spotify Valence  

In this assignment we try to further understand the valence metric used by Spotify to understand the happiness of a song. Using a dataset obtained from the Spotify API, we analyze the influence of several song features on the valence metric.  
<br>
Also, three methods where used to predict the valence of a song based on our data. these methods are:  

* Decision Trees
* Random Forests
* Stochastic Gradient Descent

Apart from those three methods, a simple neural nertwork was created to further form our predictions. Along with the notebook and in order to execute it, several files are also necessary.

* `charts` : contains all the songs used for the analysis
* `tracks_with_features.csv` : contains the features of the songs of the `charts` folder
* `spotify_ids.txt` : contains the song ids we will use for further evaluation
* `given_tracks_features.csv` : contains the features of the songs given at the `spotify_ids.txt` file
