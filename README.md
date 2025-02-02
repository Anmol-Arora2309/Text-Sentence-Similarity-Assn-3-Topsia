# Text-Sentence-Similarity-Assn-3-Topsia

# Sentence Similarity & Model Ranking with TOPSIS

This repository demonstrates how to compute sentence similarity using multiple transformer models and ranks them using the TOPSIS (Technique for Order of Preference by Similarity to Ideal Solution) method. The cosine similarity between sentence embeddings from different models is calculated, and the models are ranked based on these similarity scores.

## Overview

The code uses popular transformer models to generate sentence embeddings for a pair of input sentences. The cosine similarity between these embeddings is computed, and the models are ranked using the TOPSIS method to determine which model produces the most similar embeddings.

### Models Used
- ALBERT (`albert-base-v2`)
- RoBERTa (`roberta-base`)
- Sentence-BERT (`sentence-transformers/bert-base-nli-mean-tokens`)
- XLM-RoBERTa (`xlm-roberta-base`)
- DistilBERT (`distilbert-base-uncased`)

## Features
- Computes sentence embeddings using different transformer models.
- Calculates cosine similarity between the embeddings of two sentences.
- Implements TOPSIS to rank models based on their similarity scores.
- Saves the ranking results to a CSV file (`model_ranking.csv`).

## Dependencies

Ensure that you have the following packages installed:

```bash
pip install torch transformers scipy numpy
