1. Sentiment Analysis on IMDB Reviews
   
In this project, I used a hybrid NLP approach to classify movie reviews from the IMDB dataset as positive or negative. I extracted contextual embeddings using the pre-trained MiniLM model and fed them into a Histogram Gradient Boosting Classifier for supervised learning. This combination allowed for efficient and accurate sentiment classification, demonstrating the power of integrating modern Transformer-based models with traditional machine learning.

2. Music Genre Similarity Analysis
   
This project analyzes the relationships between different music genres using embeddings and UMAP for dimensionality reduction. With Wikidata's dataset of music genres, I generated numeric embeddings for each genre using a Sentence Transformer model. I then visualized these embeddings in a 2D scatterplot and computed cosine similarities to identify the most similar genres to a given genre(e.g. "Argentine tango"). This workflow highlights the flexibility of combining Transformer-based embeddings with classical similarity measures for exploratory data analysis.
