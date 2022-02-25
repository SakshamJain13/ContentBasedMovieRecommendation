# ContentBasedMovieRecommendation
This movie recommendation algorithm uses 4 factors (director, lead actors, keywords &amp; genres) to give a movie recommendation.
A cosine similarity function is used to find similarity between two movies based on the above mentioned factors. Each movie is compared with the entire dataset and then based on
the similarity score the movie titles are arranged in descending order. The first title will be the movie itself with similarity score 1 so we exclude it from the recommendation.
The credits.csv file was too big to upload and has been uploaded as a rar file.
