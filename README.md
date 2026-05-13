# semantic-search-engine
# Semantic Search Engine using ChromaDB

A simple AI-powered Semantic Search Engine built using ChromaDB and Sentence Transformers.

This project demonstrates how embeddings and vector databases can be used to perform meaning-based search instead of traditional keyword matching.

---

#  Features

- Generate text embeddings using Sentence Transformers
- Store embeddings in Chroma Vector Database
- Perform semantic similarity search
- Retrieve top matching documents
- Understand vector-based information retrieval
- Beginner-friendly implementation

---

#  Technologies Used

- Python
- ChromaDB
- Sentence Transformers
- Vector Databases
- Semantic Search
- Embeddings

---

#  Concepts Covered

- Embeddings
- Vector Databases
- Semantic Search
- Cosine Similarity
- Similarity Matching
- Information Retrieval
- AI Search Systems

---

#  Installation

##  Clone Repository

```bash
git clone https://github.com/your-username/semantic-search-engine.git
cd semantic-search-engine
```

#  Recommended Environment

This project is developed as a `.ipynb` notebook file.

Recommended platforms:

- Google Colab
- Jupyter Notebook
---

#  Requirements

```txt
chromadb
sentence-transformers
```

---

#  How It Works

1. Documents are converted into embeddings (vectors)
2. Embeddings are stored in ChromaDB
3. User query is also converted into an embedding
4. Similarity search is performed
5. Most relevant documents are returned

---

#  Example Query

```python
query = "How to build muscle?"
```

---

#  Sample Output

```text
Top Results:

1. Strength training builds muscle mass.
2. Exercise improves brain function and memory.
3. Eating healthy food helps in weight management.
```

---
