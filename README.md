# Mid-bootcamp-project

Project: What are the features of a popular song, and are there any noticeable trends?

To try and answer this question I performed an analysis on the Spotify top200 and viral50 daily charts for the period 1 Jan 2017 to 31 Aug 2021.

During my initial exploration of the dataset (1_Initial Exploring.ipynb), I extracted a unique list of track id’s to obtain their audio features via Spotify API.  
See 2_features.ipynb for the coding I used for this purpose.  The outcome of this process resulted in separate csv files containing audit features, and this has been combined in one csv file.

Together with the genre information I had available, I combined this into one dataframe – see 3_Combined dataframes.ipnyb.  The outcome of this is included in the folder charts_clean.
Further exploratory analysis was performed in notebook (4_Exploratory analysis.ipynb) as well as in Tableau.   
Due to the size of the dataframe, I divided the dataframe into smaller sections which I used further in my analysis/data visualization.  

I tested my hypothesis ("Do the audio features drive the popularity of a track?") in notebook 5_Test hypothesis.ipynb.

Sources and supporting docs:
charts.csv → Spotify top200 and viral50 daily charts for the period 1 Jan 2017 to 31 Aug 2021
combined-csv-files.csv → audio features for tracks obtained from Spotify API
data.csv → includes the genre for certain track id’s
Difference between US and global rows → recon of question that came up during exploratory analysis
null_audio_features → list of tracks that returned null from Spotify API
track_id → unique list of track id’s from the Spotify top200 and viral50 daily charts

Dataset and sources used:
From <https://www.kaggle.com/dhruvildave/spotify-charts> 
From <https://developer.spotify.com/documentation/web-api/reference/#object-audiofeaturesobject> 
From <https://levelup.gitconnected.com/extracting-and-analysing-spotify-tracks-with-python-d1466fc1dfee
From <https://www.kaggle.com/ivannatarov/spotify-daily-top-200-songs-with-genres-20172021> 



