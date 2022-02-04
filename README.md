![https://github.com/WahajDar98/MusicRecommenderSystem/blob/main/Images/Music%20banner.jpeg](https://github.com/WahajDar98/MusicRecommenderSystem/blob/main/Images/Music%20banner.jpeg)

# Music Recommender System

Author: [Wahaj Dar](https://www.linkedin.com/in/wahaj-dar-/)

## Background
The reason I chose to do a music recommendation system is because I love listening to music. I mean who doesn't? So as I was doing some research I came across some very interesting finds like the health benefits of music. For example according to Healthline.com a study published in the Journal of Consumer Research, found that people tend to prefer sad music when they are experiencing a deep interpersonal loss such as the end of a relationship. The study stated that sad music provides a substitute for the lost relationship. They compared it to the preference most people have for an empathic friend — someone who truly understands what you’re going through. The American Music Therapy Association (AMTA) reports that music therapy programs can be designed to achieve goals such as managing stress, enhancing memory, and alleviating pain. Surprisingly enough research has shown a clear link that music can help people cope with physical pain. 

## Overview
This project is to help if you have ever been in a  situation where you are listening to a song and you instantly fall in love with it. Then you’re listening to it over and over again and then you finally get tired of that song. Well if you have ever found yourself in that situation this would greatly benefit you. 

The reason I chose to only use data from Spotify is:

- Spotiify is the number one music streaming service with 47.7 million monthly users with a database of over 70 million songs
- The algorithm-based audio analysis (song features) provides an amazing  opportunity for song analysis
- ID and URI are included with the songs to identify them which also organizes tracking

Spotify audio features are extracted and used in order to find similar songs for recommendation. For what each of these audio features means refer to the [documentation](https://developer.spotify.com/documentation/web-api/reference/#/operations/get-several-audio-features) for an in-depth explanation of each:

- Acousticness, danceability, energy, instrumentalness, liveness, loudness, speechiness, tempo (BPM), valence

## Business Objective 
This will help users with a Spotify account to be able to listen to new music. This includes users who are indecisive or sometimes tired of what they have been listening to that need some new songs but also resonates with the kind of taste in music they already have. 

## Data
The datasets that I used were 5 files that were taken from [Kaggle](https://www.kaggle.com/) called "[Spotify dataset](https://www.kaggle.com/vatsalmavani/spotify-dataset?select=data)".

## Methods
This project uses a Correlation-Heatmap, Pearson Correlation Coefficient, One Hot Encoder, Decision Tree Regressor, GridSearchCV, Tuning a Decision Tree, Random Forest Regressor and lastly  K-means Clustering. Exploratory data analysis and visualizations are conducted on the cleaned data.

## Results
The best model was a Decision Tree with r2-score of Train Dataset ≈ 97% and Test Dataset ≈ 74%

## Conclusions
The recommendation system works pretty well. In the Song Recommendation  notebook you will be able to see I tested 3 different songs that returns 5 song reccomendations each. Based on those song recommendations you can see that the artists that are recommended also have songs in the similar genre as the songs that were put into the recommender system. 

## Limitations
A limitation with this project is that it does not give song recommendations based off mood. Also, it does not use the the song's lyrics to predict similar songs as well. 

## Next Steps
If this project is worked on in the future, these next steps should be taken:

- Using a [Spotify API](https://developer.spotify.com/documentation/web-api/.) call.
- Use Natural Language Processing ([NLP](https://machinelearningmastery.com/natural-language-processing/)) to find similar songs by the song's lyrics.
- Use more data from a website like [Kaggle](https://www.kaggle.com/) where you can access their [datasets](https://www.kaggle.com/datasets). 
- Deploying the final model function to a mobile app or web app like [Streamlit](https://docs.streamlit.io/) or [Flask](https://flask.palletsprojects.com/en/2.0.x/).

## Sources
The online resources that I used in order to get a better understanding of this project:
1. [Correlation-Heatmap](https://www.geeksforgeeks.org/how-to-create-a-seaborn-correlation-heatmap-in-python/) 
2. [Pearson Correlation Coefficient](https://www.scikit-yb.org/en/latest/api/target/feature_correlation.html)
3. [One Hot Encoder](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.OneHotEncoder.html)
4. [Decision Tree Regressor](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeRegressor.html)
5. [GridSearchCV](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html)
6. [Tuning Decision Tree](https://medium.com/@mohtedibf/indepth-parameter-tuning-for-decision-tree-6753118a03c3)
7. [Random Forest Regressor](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html)
8. [K-means Clustering](https://en.wikipedia.org/wiki/K-means_clustering)

## For More Information
Please review my analysis in my [Jupyter Notebook](https://github.com/WahajDar98/MusicRecommenderSystem/blob/main/Notebooks/Final%20Notebook.ipynb) or [presentation deck](https://docs.google.com/presentation/d/1WU6WAefsTRtd4woIdrnaSvJZtnCRFtAHkxMi2i-IUqE/edit#slide=id.p1).
For additional questions, feel free to contact [me](https://www.linkedin.com/in/wahaj-dar-/).

## Repository Structure
```
├── Data                        <- Source data .csv files
├── Images                      <- Exported Notebook visualizations
├── Notebooks                   <- Technical and narrative documentation in Jupyter Notebook
├── Capstone_presentation.pdf   <- PDF version of project presentation (FIX DEPENDING WHERE IT GOES)
└── README.md                   <- Top-level README to review this project
```
