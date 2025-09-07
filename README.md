# Language Modeling with RNN and LSTM  

## Overview  
This project implements and compares **Recurrent Neural Networks (RNNs)** and **Long Short-Term Memory (LSTM)** models on the **Tiny Shakespeare dataset**. The goal is to explore how these models learn sequential patterns in text and evaluate their performance both quantitatively (loss, perplexity, training efficiency) and qualitatively (generated text).  

The project also includes ablation studies to examine the effects of **dropout** and **tokenization strategies**.  

---

## Features  
- Train and evaluate RNN and LSTM models for next-word prediction.  
- Compare model performance using:  
  - Training/validation/test loss  
  - Perplexity (PPL)  
  - Training time efficiency  
- Generate sample Shakespeare-like text at different temperatures.  
- Ablation studies:  
  - Dropout (0.2 vs 0.0)  
  - Word-level vs character-level tokenization  

---

## Requirements  
- Python 3.8+  
- PyTorch  
- NumPy  
- Matplotlib  
- tqdm  

Install dependencies with:  
```bash
pip install torch numpy matplotlib tqdm
