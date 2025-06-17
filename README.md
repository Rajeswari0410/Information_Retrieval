📁 Enron Information Retrieval Projects
  This repository contains a series of IR-focused implementations using the Enron email dataset, covering core retrieval methods, graph-based algorithms, and modern embedding techniques.

📄 File Descriptions:

01_retrieval_models.py:
  Implements traditional information retrieval techniques:
    Text preprocessing and tokenization
    Boolean retrieval model
    Vector space model using TF-IDF
    BM25 ranking algorithm
    Compares ranking results across models

02_graph_ir_pagerank_hits.py:
  Focuses on graph-based IR algorithms:
    Parses email metadata and builds communication graph
    Implements PageRank to rank nodes based on connectivity
    Implements HITS algorithm (hubs and authorities)
    Analyzes structure and influence in the Enron email network

03_embeddings_llms_recommendation.py:
  Explores modern embedding-based IR approaches:
    Generates document and word embeddings
    Implements basic content-based recommendation
    Investigates LLM applications (e.g., vector search, reranking)
    Connects classical IR concepts to emerging retrieval paradigms
