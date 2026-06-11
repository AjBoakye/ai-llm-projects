# Lab 1 — Understanding LLM Architecture

## 🎯 Objective
To understand the internal structure of a Large Language Model (LLM), including tokenization, embeddings, transformer layers, and attention mechanisms.

## 🧠 Key Concepts Covered
- Tokenization (BPE, WordPiece)
- Embedding vectors
- Transformer architecture
- Self-attention
- Next-token prediction

## 🧪 Lab Steps

### 1. Tokenization
I tested how text is broken into tokens using a simple prompt:

**Input:**  
`"AI security is the future."`

**Output tokens (example):**  
`["AI", " security", " is", " the", " future", "."]`

**Takeaway:**  
LLMs do not understand words — they understand tokens.

---

### 2. Embedding Generation
I generated embeddings for a short sentence and compared vector similarities.

**Example:**  
- “cat” vs “dog” → high similarity  
- “cat” vs “car” → low similarity  

**Takeaway:**  
Embeddings encode semantic meaning, not spelling.

---

### 3. Transformer Layer Flow
I traced how a token flows through:

1. Embedding layer  
2. Multi-head attention  
3. Feed-forward network  
4. Residual connections  
5. Layer normalization  

**Takeaway:**  
Attention allows the model to “focus” on relevant context.

---

### 4. Next-Token Prediction
I tested how the model predicts the next token:

**Prompt:**  
`"Cybersecurity is all about"`  

**Model prediction:**  
`"protecting systems and data"`  

**Takeaway:**  
LLMs are probabilistic next-token predictors, not reasoning engines.

---

## 🔐 Security Relevance
Understanding architecture is essential for:

- Prompt injection  
- Model extraction  
- Adversarial prompting  
- RAG manipulation  
- Jailbreak detection  

---

## ✅ Summary
This lab established the foundation for understanding how LLMs process text, generate embeddings, and predict tokens — all critical for AI security work.
