# Lab 3 — Inference & Model Behavior

## 🎯 Objective
To understand how LLMs generate outputs during inference and how temperature, top-k, and top-p affect behavior.

## 🧠 Key Concepts Covered
- Inference pipeline
- Temperature
- Top-k sampling
- Top-p (nucleus) sampling
- Deterministic vs stochastic outputs

## 🧪 Lab Steps

### 1. Baseline Inference
**Prompt:**  
“Explain AI security in one sentence.”

**Output:**  
“AI security focuses on protecting models, data, and systems from misuse and attacks.”

---

### 2. Temperature Test
I tested temperature values:

- **T = 0.0** → deterministic, factual  
- **T = 1.0** → creative, varied  
- **T = 1.5** → chaotic, less reliable  

**Takeaway:**  
Temperature controls randomness.

---

### 3. Top-k Sampling
I tested top-k = 10 vs top-k = 50.

- Lower k → safer, more predictable  
- Higher k → more creative, more risk of hallucination  

---

### 4. Top-p Sampling
I tested top-p = 0.9 vs 0.5.

- Lower p → conservative  
- Higher p → more expressive  

---

### 5. Behavior Analysis
I observed:

- LLMs can hallucinate when sampling is too open  
- Safety filters reduce harmful outputs  
- Prompt phrasing heavily influences behavior  

---

## 🔐 Security Relevance
Inference behavior matters for:

- Jailbreak attempts  
- Prompt injection  
- Safety bypasses  
- Output manipulation  
- Hallucination-based attacks  

---

## ✅ Summary
This lab showed how inference parameters shape model behavior and how attackers can exploit these settings.
