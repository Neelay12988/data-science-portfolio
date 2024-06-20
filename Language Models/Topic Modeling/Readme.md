# Topic Modeling Comparison

This project compares various topic modeling techniques using the 20 Newsgroups dataset. The techniques compared are:

- **Latent Dirichlet Allocation (LDA)**
- **Non-negative Matrix Factorization (NMF)**
- **Latent Semantic Analysis (LSA)**
- **BERTopic**

## Dataset

The [20 Newsgroups dataset](https://scikit-learn.org/0.19/datasets/twenty_newsgroups.html) is used for this comparison. It contains approximately 20,000 newsgroup documents, partitioned across 20 different newsgroups.

## Models

### LDA (Latent Dirichlet Allocation)

LDA is a generative probabilistic model that assumes each document is a mixture of topics, and each topic is a mixture of words.

### NMF (Non-negative Matrix Factorization)

NMF is a linear algebra technique that factorizes the document-term matrix into non-negative matrices. It’s useful for parts-based representation.

### LSA (Latent Semantic Analysis)

LSA uses Singular Value Decomposition (SVD) to reduce the dimensionality of the document-term matrix, capturing the underlying structure in the data.

### BERTopic

BERTopic leverages BERT embeddings and clustering algorithms to identify topics in text data. It captures nuanced meanings in documents due to advanced contextual embeddings.

## Evaluation

The models are evaluated using coherence scores for LDA and BERTopic, and the top words for each topic.

## Results

The results and visualizations provide insights into the topics identified by each model and their interpretability.

## Visualizations

- **Category Distribution**: Shows the distribution of documents across different categories.
- **Document Length Analysis**: Shows the distribution of document lengths.
- **Wordclouds**: Visual representations of the most important words in the topics for LDA, NMF, and LSA.
- **BERTopic Visualization**: Visualizes topics identified by BERTopic.
- **Coherence Score Comparison**: Compares coherence scores of LDA and BERTopic models.

## Installation

To run this project, you need to install the following libraries:

```bash
pip install numpy pandas scikit-learn gensim spacy nltk pyLDAvis bertopic wordcloud matplotlib seaborn
python -m spacy download en_core_web_sm
