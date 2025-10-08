# COMP90042 - Natural Language Processing (2025)

This repository contains all my completed assignments for the University of Melbourne subject **COMP90042: Natural Language Processing**.

### 🧹 Assignment 1 — Text Preprocessing and Classification
Implemented a full pipeline for text normalization, TF-IDF vectorization, and classification using Naive Bayes, Logistic Regression, and SVM.  Score: 9 / 9

### 🎮 Assignment 2 — Language Modelling in Hangman
Built character-level n-gram language model for Hangman. Score: 7 / 8

### 🧠 Final Project — Scientific Fact-Checking System
Designed a two-stage system for scientific claim verification using:

- **Evidence Retrieval**: SVD-reduced Word2Vec + cosine similarity for top-200 pre-ranking, followed by a Transformer-based reranker.
- **Claim Classification**: Transformer classifier with attention pooling to assign one of four labels: `SUPPORTS`, `REFUTES`, `NOT_ENOUGH_INFO`, or `DISPUTED`.

Key highlights:

- Word2Vec outperformed BERT in this domain.
- Attention pooling and Transformer-based ranking/classification achieved 41.3% relative improvement in harmonic mean over the baseline.

Score: 40 / 42

---



