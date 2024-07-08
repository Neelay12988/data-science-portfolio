# Topic Modeling Comparison

This project compares various topic modeling techniques using the 20 Newsgroups dataset.

## Dataset

The [20 Newsgroups dataset](https://scikit-learn.org/0.19/datasets/twenty_newsgroups.html) is used for this comparison. It contains approximately 20,000 newsgroup documents, partitioned across 20 different newsgroups.

## Models

- LDA (Latent Dirichlet Allocation): LDA is a generative probabilistic model that assumes each document is a mixture of topics, and each topic is a mixture of words.
- NMF (Non-negative Matrix Factorization): NMF is a linear algebra technique that factorizes the document-term matrix into non-negative matrices. It’s useful for parts-based representation.
- LSA (Latent Semantic Analysis): LSA uses Singular Value Decomposition (SVD) to reduce the dimensionality of the document-term matrix, capturing the underlying structure in the data.

## Visualizations

- **Topics**: Shows topics geenrated.
- **Category Distribution**: Shows the distribution of documents across different categories.
- **Wordclouds**: Visual representations of the most important words in the topics.
