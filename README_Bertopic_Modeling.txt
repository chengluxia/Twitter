BERT Topic Modeling with Federal Reserve.ipynb
This notebook will using federal reserve stream to do BERT Topic Modeling and tune BERTopic to get the optimal coherence scores which will also show you visualizations of the optimal result.

List of required packages:
os, pandas, numpy, sys, gcsfs, json, networkx, scipy, matplotlib.pyplot, cdlib, re, string, date time, warnings, nltk, wordcloud, bertopic, sentence_transformers, gensim, umap, hdbscan.

This notebook will also use preprocessing.py as preprocessing function to preprocess text column.

We suggest you run the all chunks step by step
Following is the structure of this notebook:
1. Load Dataset
2. Preprocessing text Column
2.1 Clean text column for topic modeling
2.2 WordCloud
3. BERT Topic Modeling
3.1 BERTopic modeling with default setting
3.2 Tuning BERTopic model parameter-n_neighbors
3.3 Tuning BERTopic model parameter-nr_topics
3.4 Get the Optimal BERTopic model
3.5 Visualizations
4. Conclusion
