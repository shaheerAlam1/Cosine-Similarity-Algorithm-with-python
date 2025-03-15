# Cosine Similarity Algorithm

This repository contains a Python implementation of the **Cosine Similarity algorithm** without using any machine learning libraries. The implementation ranks documents based on their similarity to a given query using **TF-IDF (Term Frequency - Inverse Document Frequency)** and **cosine similarity**.

## Features
- Splits documents into tokens and calculates term frequencies.
- Computes inverse document frequency (IDF) for each term.
- Calculates TF-IDF weights for documents and the query.
- Computes cosine similarity scores to rank documents based on relevance.
- Visualizes the similarity scores using a bar chart.

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/shaheerAlam1/Cosine-Similarity-Algorithm-with-python.git
   cd Cosine-Similarity-Algorithm-with-python
   ```
2. Install dependencies (if not already installed):
   ```bash
   pip install pandas matplotlib
   ```
3. Run the notebook or script to see the ranking results.

## Example
### Query:
```
"stock exchange pakistan"
```
### Documents:
1. "Market of stock exchange is affected by brokers."
2. "Pakistan stock market is very popular."
3. "Stock exchange Pakistan is in loss nowadays."

### Output:
The algorithm ranks the documents based on their relevance to the query using cosine similarity, with the highest-ranking document being the most relevant.

## Dependencies
- Python 3
- `pandas`
- `matplotlib`
