# Text Mining Yelp Reviews

Analyze text data on users’ review of restaurants and perform sentiment analyses. 

The dataset is based on a collection of reviews and accompanying star ratings from Yelp.  To keep the project manageable, a sample of the original dataset (over 8 million reviews by over a million users for 160K+ businesses) is used here. More details on the data are available from https://www.yelp.com/dataset

We examine the effectiveness of different sentiment ‘dictionaries’ (AFFIN, Bing, NRC) and develop classification models to help predict sentiment polarity (negative, positive). First, using each dictionary we obtain an aggregated positiveScore and a negativeScore for each review and then predict sentiment based on these aggregated scores. Later, we use star ratings to indicate the sentiment label (by converting the 1-5 scale rating values to {positive(1), negative(0)} values) and then build classification models to predict review sentiment.

Lastly, we take few interesting attributes and summarize how many restaurants are there by values of these attributes and check how prediction accuracy vary by certain restaurant attributes.
