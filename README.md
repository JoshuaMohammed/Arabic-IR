# Arabic Information Retrieval System

A complete **Arabic Information Retrieval (IR) system** combining traditional retrieval models with **AraBERT neural re-ranking** to improve semantic relevance.

## Features
- Arabic text preprocessing and indexing
- Boolean, TF-IDF, and BM25 retrieval
- Query expansion
- AraBERT-based neural re-ranking
- Evaluation on a 26,992-document corpus

## Summary
The system retrieves documents using TF-IDF or BM25, then re-ranks the top 100 candidates with AraBERT. This improves ranking quality while keeping computation efficient.

## Technologies
Python · Scikit-learn · AraBERT · NLP · Information Retrieval
