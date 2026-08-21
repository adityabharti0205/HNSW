# HNSW: Hierarchical Navigable Small World

A Python implementation and exploration of **Hierarchical Navigable Small World (HNSW)** graphs for efficient Approximate Nearest Neighbor (ANN) search.

## Overview

HNSW is a graph-based indexing algorithm used for fast similarity search over high-dimensional vectors. Instead of comparing a query against every vector, it navigates through a hierarchical graph to efficiently find the nearest neighbors.

This project explores the core concepts behind HNSW, including graph construction, vector similarity, and approximate nearest-neighbor search.

## Key Concepts

* Hierarchical graph-based indexing
* Approximate Nearest Neighbor (ANN) search
* Vector similarity and distance calculations
* Trade-off between search speed and accuracy
* Parameters such as `M`, `ef_construction`, and `ef_search`

## Project Structure

```text
HNSW/
├── hnsw.ipynb
└── README.md
```

## Technologies

* Python
* NumPy
* Jupyter Notebook

## Applications

HNSW is commonly used for:

* Semantic search
* Vector databases
* Recommendation systems
* Retrieval-Augmented Generation (RAG)
* Embedding-based information retrieval

## Getting Started

Clone the repository:

```bash
git clone https://github.com/adityabharti0205/HNSW.git
cd HNSW
```

Install dependencies:

```bash
pip install numpy jupyter
```

Launch the notebook:

```bash
jupyter notebook
```

Open `hnsw.ipynb` and run the cells.

## Author

**Aditya Bharti**

GitHub: [@adityabharti0205](https://github.com/adityabharti0205)
