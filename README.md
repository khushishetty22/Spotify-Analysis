# Spotify-Analysis
The primary data which the project uses is a rich dataset sourced from Spotify's Web API. The 
extracted data was converted to JSON datasets which offer comprehensive information about 
tracks in various playlists. This data encompasses:

• Track Details: Names, artists, and album information.
• Audio Features: Quantitative measures like danceability, energy, valence, tempo, 
loudness, and speechiness.
• Lyrics: Extracted from an external lyrics API, providing a textual dimension to the audio 
data.
I have also used other data for the sentiment analysis of the top 6 songs of the user. Data is 
hosted on Amazon S3, showing cloud storage utilization for the positive and negative word lists.
• Positive Words: Fetched from https://intro-datascience.s3.us-east2.amazonaws.com/positive-words.txt.
• Negative Words: Obtained from https://intro-datascience.s3.us-east2.amazonaws.com/negative-words.txt.
Another text file was used for emotion analysis on two of the playlists:
• The NRC Emotion Lexicon, obtained from saifmohammad.com, serves as a pivotal 
resource for emotion analysis in natural language processing. 
• The lexicon, encapsulated in the file "NRC-Emotion-Lexicon-Wordlevel-v0.92.txt," 
comprises an extensive collection of words associated with specific emotion categories.
• The lexicon includes a substantial vocabulary annotated with emotion categories, 
providing a comprehensive resource for sentiment and emotion analysis in natural 
language processing tasks.
