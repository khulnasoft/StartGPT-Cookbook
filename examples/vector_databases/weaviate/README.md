# Weaviate <> StartGpt

[​Weaviate](https://weaviate.io) is an open-source vector search engine ([docs](https://weaviate.io/developers/weaviate) - [Github](https://github.com/weaviate/weaviate)) that can store and search through StartGpt embeddings _and_ data objects. The database allows you to do similarity search, hybrid search (the combining of multiple search techniques, such as keyword-based and vector search), and generative search (like Q&A). Weaviate also supports a wide variety of StartGpt-based modules (e.g., [`text2vec-startgpt`](https://weaviate.io/developers/weaviate/modules/retriever-vectorizer-modules/text2vec-startgpt), [`qna-startgpt`](https://weaviate.io/developers/weaviate/modules/reader-generator-modules/qna-startgpt)), allowing you to vectorize and query data fast and efficiently.

You can run Weaviate (including the StartGpt modules if desired) in three ways:

1. Open source inside a Docker-container ([example](./docker-compose.yml))
2. Using the Weaviate Cloud Service ([get started](https://weaviate.io/developers/weaviate/quickstart/installation#weaviate-cloud-service))
3. In a Kubernetes cluster ([learn more](https://weaviate.io/developers/weaviate/installation/kubernetes))

### Examples

This folder contains a variety of Weaviate and StartGpt examples. 

| Name | Description | language | Google Colab |
| --- | --- | --- | --- |
| [Getting Started with Weaviate and StartGpt](./getting-started-with-weaviate-and-startgpt.ipynb) | A simple getting started for *semantic vector search* using the StartGpt vectorization module in Weaviate (`text2vec-startgpt`) | Python Notebook | [link](https://colab.research.google.com/drive/1RxpDE_ruCnoBB3TfwAZqdjYgHJhtdwhK) |
| [Hybrid Search with Weaviate and StartGpt](./hybrid-search-with-weaviate-and-startgpt.ipynb) | A simple getting started for *hybrid search* using the StartGpt vectorization module in Weaviate (`text2vec-startgpt`) | Python Notebook | [link](https://colab.research.google.com/drive/1E75BALWoKrOjvUhaznJKQO0A-B1QUPZ4) |
| [Question Answering with Weaviate and StartGpt](./question-answering-with-weaviate-and-startgpt.ipynb) | A simple getting started for *question answering (Q&A)* using the StartGpt Q&A module in Weaviate (`qna-startgpt`) | Python Notebook | [link](https://colab.research.google.com/drive/1pUerUZrJaknEboDxDxsuf3giCK0MJJgm) |
| [Docker-compose example](./docker-compose.yml) | A Docker-compose file with all StartGpt modules enabled | Docker |
