# Inference Parameters Demo

## 🎯 Objective
To explore how inference parameters (temperature, top‑k, top‑p) affect LLM output.

## 🧪 Steps

### 1. Baseline Prompt
Explain AI security in one sentence.


### 2. Temperature Test
- **T = 0.0** → deterministic  
- **T = 1.0** → creative  
- **T = 1.5** → chaotic  

### 3. Top‑k Sampling
- **k = 10** → predictable  
- **k = 50** → more diverse  

### 4. Top‑p Sampling
- **p = 0.5** → conservative  
- **p = 0.9** → expressive  

### 5. Observations
- Higher randomness = more hallucination  
- Lower randomness = safer, more factual  
- Safety filters can be bypassed with certain sampling settings  

## 🔐 Security Relevance
Attackers exploit inference settings to:
- Increase hallucinations  
- Trigger unsafe outputs  
- Bypass guardrails  

## ✅ Summary
Inference parameters shape model behavior and can be manipulated for attacks or controlled for safety.
