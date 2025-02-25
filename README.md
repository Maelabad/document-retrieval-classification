# Document-retrieval-classification

# Document Retrieval and Classification System

This repository contains a simple document retrieval system and a supervised learning-based document classifier. The system uses TF-IDF to rank documents by relevance and supports multiple queries, returning the top 3 most relevant documents for each query. Additionally, it includes a classification part to detect whether articles are fake news or not.

## Features

- **Document Retrieval:**
  - Preprocess and vectorize documents using TF-IDF.
  - Compute cosine similarity between queries and documents.
  - Return the top 3 most relevant documents for each query.

- **Document Classification:**
  - Train supervised learning models (e.g., Logistic Regression) to classify documents.

## Dataset

The system is built using the [FAKE_NEWS](https://www.kaggle.com/datasets/shubh0799/fake-news) dataset on kaggle, which contains articles labeled as fake news or not.

## Getting Started

### Requirements

- Python 3.x
- [NLTK](https://www.nltk.org/)
- [Scikit-learn](https://scikit-learn.org/)
- [Pandas](https://pandas.pydata.org/)
- [NumPy](https://numpy.org/)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/document-retrieval-classification.git


