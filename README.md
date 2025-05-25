# 🧠 Machine Learning Projects

This repository contains my implementations of foundational machine learning models and experiments. Many of these are inspired by Andrej Karpathy’s tutorials and research papers I’ve studied.

---

## 1. Micrograd – Autodiff Engine from Scratch

Based on [Andrej Karpathy’s micrograd](https://github.com/karpathy/micrograd) and his [YouTube tutorial](https://www.youtube.com/watch?v=VMj-3S1tku0).

**What’s inside:**
- A minimal automatic differentiation engine
- Manual backpropagation
- A simple MLP trained on toy data

**Credits:** Original concept by Andrej Karpathy – MIT License

---

## 2. Makemore – Character-Level Language Model

Inspired by Karpathy’s [makemore series](https://github.com/karpathy/makemore). I implemented three versions:

- **Version 1 – Bigram:** Pure frequency-based character predictions
- **Version 2 – MLP:** A single-layer neural net predicting next characters
- **Version 3 – Deep MLP:** Includes embeddings and deeper architecture (like a mini GPT)

**Credits:** Based on the Makemore project by Andrej Karpathy – MIT License

---

## 3. Transformer – Uzbek-English Translator

This project implements the original Transformer model (Vaswani et al., 2017) using PyTorch. I built this with a few friends after studying the paper.

**What’s inside:**
- Encoder-decoder transformer
- Custom tokenizer and positional encoding
- Trained on Uzbek-English sentence pairs

**Team:** Built with peers as a learning project  
**Credits:** Inspired by the "Attention is All You Need" paper

---

## 4. Predicting Unemployment Rates + Factor Ranking

A self-directed project where I used an MLP (Multi-Layer Perceptron) to predict unemployment rates based on socioeconomic indicators. I also applied **Garon’s algorithm** to rank the most influential factors contributing to unemployment.

**What’s inside:**
- Dataset preprocessing and feature engineering
- MLP model trained to predict unemployment rates
- Application of Garon’s algorithm to interpret and rank input features

**Use case:** Aimed to identify the top contributors to unemployment for economic analysis and policymaking.

---

## 📄 License

- **Code:** MIT License  
- **Text & Explanations:** © Abrorbek Nematov – [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)
