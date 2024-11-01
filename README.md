# NLP_Clustering_Reviews

We sort text data from negative reviews into categories. 

We preprocess the negative reviews by tokenizing the text and removing stop words and non-alpha character, using the Natural Language Toolkit (NLTK).

We then vectorize the negative reviews using TF-IDF and apply K-means clustering to group the reviews into five categories, using the scikit-learn package.

Finally, we extract the most frequent term for each unique cluster label.

# Data

| Column     | Description              |
|------------|--------------------------|
| `'content'` | Content (text) of each review. |
| `'score'` | Score assigned to the review by the user as an integer (from 1 to 5). |
