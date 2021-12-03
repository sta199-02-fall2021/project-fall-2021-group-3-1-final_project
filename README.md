Loading in our data: 

Here's the link to our data csv and how to load them in. The links to the data is also in the Data folder in our repo. 

billboard <- 
  readr::read_csv('https://raw.githubusercontent.com/rfordatascience/tidytuesday/master/data/2021/2021-09-14/billboard.csv')
audio_features <-
  readr::read_csv('https://raw.githubusercontent.com/rfordatascience/tidytuesday/master/data/2021/2021-09-14/audio_features.csv')

Variable description:

Genre - is based on what genre Spotify puts the song into. Genre are categories that a song can put into based on musical techniques used, the cultural context behind the song and the spirit of the themes.

Danceability - describes how suitable a track is for dancing based on a combination of musical elements including tempo, rhythm stability, beat strength, and overall regularity. A value of 0.0 is least danceable and 1.0 is most danceable.

Energy - a measure from 0.0 to 1.0 and represents a perceptual measure of intensity and activity. Typically, energetic tracks feel fast, loud, and noisy. For example, death metal has high energy, while a Bach prelude scores low on the scale. Perceptual features contributing to this attribute include dynamic range, perceived loudness, timbre, onset rate, and general entropy.

Speechiness - detects the presence of spoken words in a track. The more exclusively speech-like the recording (e.g. talk show, audio book, poetry), the closer to 1.0 the attribute value. Values above 0.66 describe tracks that are probably made entirely of spoken words. Values between 0.33 and 0.66 describe tracks that may contain both music and speech, either in sections or layered, including such cases as rap music. Values below 0.33 most likely represent music and other non-speech-like tracks.

Valence - A measure from 0.0 to 1.0 describing the musical positiveness conveyed by a track. Tracks with high valence sound more positive (e.g. happy, cheerful, euphoric), while tracks with low valence sound more negative (e.g. sad, depressed, angry).

Tempo - The overall estimated tempo of a track in beats per minute (BPM). In musical terminology, tempo is the speed or pace of a given piece and derives directly from the average beat duration.

# Project Fall 2021
Project proposal due **October 15, 2021 by 11:59 PM**

You should make a reasonable attempt to have a draft done of each section of your analysis for the project by **November 17, 2021.** Peer review will take place in lab on **November 18, 2021** and will be due by **November 23, 2021.**

Final report due **December 3, 2021 at 11:59 PM**. 

Repo, slides, and video due by **December 10, 2021 at 11:59 PM**.

Questions for other group due by **December 13, 2021 at 9 AM**.
