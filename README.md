# Music-Album-Popularity-Prediction--Kaggle-Competition
Applying different approaches including Feature Scaling, Feature Importance, PCA and Hyperparameter Tuning on different Machine Learning models to best predict the popularity albums' scores.

CONTEXT

Spotify provides an API service that allows us to access data from their archive of millions of songs. Their API gives the users the ability to download all the possible information about Albums, Episodes, Playlists, Tracks, Users, etc. These features include attributes such as a song’s tempo, level of acoustics, how danceable a song is, and many more similar ones.

ATTRIBUTES

ID: A unique identifier for every row
Name: Name of the album
Release Date: Release date of the album
Artists: All the artists of the album
Total_tracks: Number of total tracks of the album
T_name: Name of the track
Duration: Duration of the track (in ms)
Danceability: Danceability describes how suitable a track is for dancing based on a combination of musical elements. A value of 0.0 is least danceable and 1.0 is the most danceable.
Energy: Energy is a measure from 0.0 to 1.0 and represents a perceptual measure of intensity and activity.
Key: The key the track is in. Integers map to pitches using standard Pitch
Mode: Mode indicates the modality (major or minor) of a track, the type of scale from which its melodic content is derived. Major is represented by 1 and minor is 0.-
Speechiness: Speechiness detects the presence of spoken words in a track. The more exclusively speech-like the recording, the closer to 1.0 the attribute value. Values above 0.66 describe tracks that are probably made entirely of spoken words. Values between 0.33 and 0.66 describe tracks that may contain both music and speech, either in sections or layered, including such cases as rap music. Values below 0.33 most likely represent music and other non-speech-like tracks.
Acousticness: A confidence measure from 0.0 to 1.0 of whether the track is acoustic. 1.0 represents high confidence the track is acoustic.
Instrumentalness: Predicts whether a track contains no vocals. The closer the instrumentalness value is to 1.0, the greater likelihood the track contains no vocal content. Values above 0.5 are intended to represent instrumental tracks, but confidence is higher as the value approaches 1.0.
Liveness: Detects the presence of an audience in the recording. Higher liveness values represent an increased probability that the track was performed live. A value above 0.8 provides a strong likelihood that the track is live.
Valence: A measure from 0.0 to 1.0 describing the musical positiveness conveyed by a track. Tracks with high valence sound more positive, while tracks with low valence sound more negative (e.g. sad, depressed, angry).
Tempo: The overall estimated tempo of a track in beats per minute (BPM). In musical terminology, the tempo is the speed or pace of a given piece and derives directly from the average beat duration.
Time Signature: An estimated overall time signature of a track. The time signature (meter) is a notational convention to specify how many beats are in each bar (or measure).
BENEFICIARES

Music production companies like Universal Music Group, Sony Music Entertainment, T-Series, etc, are some of the probable beneficiaries of this analysis.
If they somehow get to know that say danceability helps to increase the popularity of the album, then they can think about producing albums with such tracks.
Consider another situation in which they got to know that inclusion of tracks of a certain artist can help increase the popularity of an album, and hence, they would approach such artists more.
Music applications like Spotify, Prime Music, Deezer, YouTube Music, SoundCloud, etc can also benefit from this kind of analysis. In the current scenario, the popularity is calculated on the basis of number of likes, number of playbacks, etc.
But if these apps can acquire the information about these attributes of albums from say, music critics, artists themselves, etc, then they can predict the albums which are more likely to be popular in the near future, and hence, can focus on promoting such albums to a greater extent.
