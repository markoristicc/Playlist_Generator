# Playlist_Generator

Current Ideas
  1. Seed word: given seed phrase, generate playlist based off phrase. would require running neural net over common words/phrases and generate connotation based off of words. From connotation need way to relate that to track characteristics. Current characteristics are acousticness, danceability, energy, instrumentalness, liveness, loudness, speechiness, & valence. We can also cross reference word/phrase connotations with a genre. Each word/phrase generates 4/5 connotation descriptors. From these we would then generate a range for each track characteristic and use spotify request to obtain results. Additionally would like to use connotation descriptors to generate seed artists and songs for requests or to filter through.
  2. Playlist Combination: given 2 playlists, generate combined playlist based off of statistical analysis of playlist (averages, deviations, correlations)
