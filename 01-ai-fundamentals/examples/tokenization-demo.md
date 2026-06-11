# Tokenization Demo

## 🎯 Objective
To understand how text is broken into tokens before being processed by an LLM.

## 🧪 Steps

### 1. Input Text
AI security is the future.

Code
### 2. Tokenization Output (Example)

["AI", " security", " is", " the", " future", "."]


### 3. Observations
- Tokens are not always whole words  
- Spaces matter  
- Punctuation becomes separate tokens  
- LLMs operate on tokens, not words  

### 4. Why Tokenization Matters
- Affects cost (token count = billing)  
- Affects context window  
- Affects model behavior  
- Impacts prompt injection vectors  

## 🔐 Security Relevance
Attackers exploit tokenization quirks to:
- Bypass filters  
- Hide malicious instructions  
- Trigger unexpected model behavior  

## ✅ Summary
Tokenization is the first step in every LLM pipeline and a key part of understanding model behavior.
