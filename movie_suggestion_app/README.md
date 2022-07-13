## A Movie Suggestion App Implemented Using Cosine Similarity.


#### This made use of a collection of data, spanning various column features


#### A tactful feature engineering was carried out before relevant columns were selected such as genres,keywords,tagline,cast and the director columns.


#### This was subsequently combined before converting the text data into feature vectors in order to ease movie data pattern recognition using the TfidfVectorizer module.


#### The similarity scores had to be deciphered using cosine similarity.


#### NOTE that Cosine similarity measures the cosine of the angle btw 2 vectors projected in multi-dimensional space and tends to be more similar with small angle measures between 2 contextual angles.


#### Ultimately, a function encapsulating a methodology used in finding the close matches was implemented which of course incorporated a prompt requesting the movie title from the user while the difflib module awaits to compare the sequences already established by the cosine simiarity.
