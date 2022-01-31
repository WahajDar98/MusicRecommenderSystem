![https://github.com/WahajDar98/MusicRecommenderSystem/blob/main/image/Music%20banner.jpeg](https://github.com/WahajDar98/MusicRecommenderSystem/blob/main/image/Music%20banner.jpeg)

# Music Recommender System

## Background
The reason I chose to do a music recommendation system is because I love listening to music. I mean who doesnt? So as I was doing some research I came across some very interesting finds like the health benefits of music. For example according to Healthline.com a study published in the Journal of Consumer Research, found that people tend to prefer sad music when they are experiencing a deep interpersonal loss such as the end of a relationship. The study stated that sad music provides a substitute for the lost relationship. They compared it to the preference most people have for an empathic friend — someone who truly understands what you’re going through. The American Music Therapy Association (AMTA) reports that music therapy programs can be designed to achieve goals such as managing stress, enhancing memory, and alleviating pain. Surprisingly enough research has shown a clear link that music can help people cope with physical pain. 

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
XXX

## Results
XXX

## Conclusions
XXX

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
1. [NAME](FILL IN LINK) 
2. [NAME](FILL IN LINK)
3. [NAME](FILL IN LINK)
4. [NAME](FILL IN LINK)
5. [NAME](FILL IN LINK)

## For More Information
Please review my analysis in my [Jupyter Notebook](FILL IN LINK) or [presentation deck](FILL IN LINK).
For additional questions, feel free to contact [me](https://www.linkedin.com/in/wahaj-dar-/).

## Repository Structure
```
├── data                   <- Source data .csv files
├── images                 <- Exported Notebook visualizations
├── notebooks              <- Technical and narrative documentation in Jupyter Notebook
└── README.md              <- Top-level README to review this project
```
