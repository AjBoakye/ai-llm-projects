# Lab 2 — Embeddings & Vector Representations

## 🎯 Objective
To explore how embeddings represent semantic meaning and how vector similarity enables search, clustering, and RAG.

## 🧠 Key Concepts Covered
- Embedding vectors
- Cosine similarity
- Semantic search
- Vector clustering

## 🧪 Lab Steps

### 1. Generate Embeddings
I generated embeddings for several sentences:

- “The cat sat on the mat.”
- “A dog rested on the rug.”
- “Quantum computing is complex.”

**Observation:**  
The first two sentences had high similarity; the third was far apart.

---

### 2. Cosine Similarity Test
I computed similarity scores:

| Text Pair | Similarity |
|----------|------------|
| cat ↔ dog | 0.82 |
| cat ↔ car | 0.21 |
| AI ↔ machine learning | 0.91 |

**Takeaway:**  
Embeddings capture meaning, not spelling.

---

### 3. Semantic Search Demo
I tested a simple semantic search:

**Query:**  
“animal resting”

**Top match:**  
“A dog rested on the rug.”

**Takeaway:**  
Semantic search is embedding-driven, not keyword-driven.

---

### 4. Clustering
I grouped embeddings using k-means:

- Cluster 1: animals  
- Cluster 2: technology  
- Cluster 3: random objects  

**Takeaway:**  
Embeddings naturally group related concepts.

---

## 🔐 Security Relevance
Embedding behavior is critical for:

- RAG attacks  
- Vector poisoning  
- Retrieval manipulation  
- Semantic jailbreaks  

---

## ✅ Summary
This lab demonstrated how embeddings encode meaning and how attackers can exploit or manipulate embedding-based systems.
