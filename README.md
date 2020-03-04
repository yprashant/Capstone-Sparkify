# Capstone-Sparkify
Capstone Sparkify Udacity Project

## 1. Installation <a name="installation"></a>
Notebook for this article was developed using Python v3.6.3, Pyspark v2.4.3, Pandas v0.23.3, Matplotlib v2.1.0 and Seaborn v0.8.1.

## 2. Project Motivation <a name="motivation"></a>
Purpose of this notebook/article is, using Spark framework, to predict whether users of a fictitious audio streaming platform, Sparkify, are likely to unsubscribe. This is a capstone project for the Udacity data scientist nanodegree program.

## 3. File Descriptions <a name="filedesc"></a>
* _Sparkify.ipynb_ contains all the code allowing data load, manipulation, and graph generation.
* _Sparkify.html_ is the same as above but in HTML format.
* _mini_sparkify_event_data.zip_ is a 128 MB copy of the dataset used for our notebook (JSON format).

Article is available on [Medium](https://medium.com/@iprash31/capstone-sparkify-predicting-churn-967e4bcc6f8b).

## 4. Results <a name="results"></a>
After testing different machine learning classifiers with default parameters, we achieved a F1-score of 0.7; after fine-tuning parameters (using a grid search with a random forest classifier), we could improve this to 0.73.

From an analysis perspective, we could notice that the most important features used by the classifier are the number of "thumbs up" / "thumbs down" given by user per song, number of friends added per session, percentage of songs added to playlists, number of adverts and number of songs per session; these are in line with the features we identified as most relevant during data exploration, and indeed seem to represent well customers' satisfaction or dissatisfaction with the service.


