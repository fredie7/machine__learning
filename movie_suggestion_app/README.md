## A Movie Suggestion App Implemented Using Cosine Similarity.


#### This made use of a collection of data, spanning various column features


#### A tactful feature engineering had to be carried out before relevant columns were selected such as genres,keywords,tagline,cast and the director columns.


#### This was later combined before converting the text data into feature vectors to ease movie data pattern recognition using the TfidfVectorizer module.


#### The similarity scores had to be deciphered using cosine similarity 


#### NOTE that Cosine similarity measures the cosine of the angle btw 2 vectors projected in multi-dimensional space and tends to be more similar with small angle measures between 2 contextual angles


#### Finally, a function which implemented the movie selection had to be put together which of course encapsulated a methodology used in finding the close matches for the movie name entered by the user as difflib module would compare the sequences alread established by the cosine simiarity
