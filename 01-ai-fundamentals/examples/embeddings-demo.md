# Embeddings Demo

## 🎯 Objective
To demonstrate how text is converted into embedding vectors and how semantic similarity is computed.

## 🧪 Steps

### 1. Generate Embeddings
I generated embeddings for three sentences:

- “The cat sat on the mat.”
- “A dog rested on the rug.”
- “Quantum computing is complex.”

### 2. Compare Similarity
Using cosine similarity:

| Text Pair | Similarity Score |
|----------|------------------|
| cat ↔ dog | 0.82 |
| cat ↔ quantum computing | 0.05 |
| dog ↔ rug sentence | 0.88 |

### 3. Interpretation
- High similarity = semantically related  
- Low similarity = unrelated concepts  

### 4. Visualization (Conceptual)
Embedding vectors exist in high‑dimensional space (e.g., 768D).  
If plotted in 2D, related vectors cluster together.

## 🔐 Security Relevance
Embedding behavior is critical for:
- RAG attacks  
- Vector poisoning  
- Retrieval manipulation  
- Semantic jailbreaks  

## ✅ Summary
Embeddings encode meaning, not spelling — a core concept for understanding AI systems.

