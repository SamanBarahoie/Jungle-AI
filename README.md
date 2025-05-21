
# 🐾 Jungle-AI

*A Collection of Lightweight Language Models in the Wild*

Welcome to **Jungle-AI** — a curated collection of efficient, small-scale **language models** built from scratch, optimized for **low-resource training**, **educational use**, and **rapid experimentation**.

This repository centralizes open, modular implementations of transformer-based models trained on small yet meaningful datasets like TinyStories.

---

## 🌴 Projects

### 🔬 [`nano_llama-3.1`](https://github.com/SamanBarahoie/nano_llama-3.1)

A faithful re-implementation of the LLaMA 3.1 architecture, designed for clarity and customization.

**Key Features:**

* Causal self-attention with RoPE (Rotary Position Embeddings)
* FlashAttention (optional, toggleable)
* Mixed-precision training (fp16/bf16)
* Streaming dataset support (efficient with large files)
* Fully testable (pytest + coverage)
* Reproducible and modular training loop

---

### 🦙 [`llama4`](https://github.com/SamanBarahoie/llama4)

A **compact LLaMA-style transformer** with \~771M parameters, trained from scratch on TinyStories.

**Highlights:**

* 12 transformer blocks with MoE at layer 6 (6 experts)
* 32 attention heads (8 key-value heads)
* Custom tokenizer with vocab size = 10,000
* Trained for 4 epochs on \~465M tokens
* Final training loss: `1.66`, validation loss: `1.49`

📄 Full documentation in [README](https://github.com/SamanBarahoie/-Llama-4)

---

### 🧠 [`NanoLanguageModel`](https://github.com/SamanBarahoie/NanoLanguageModel)

A minimalistic PyTorch GPT-style language model ideal for education and experimentation.

**Highlights:**

* Vanilla transformer implementation
* Lightweight tokenizer
* Clean training loop
* Focused on readability and conceptual learning

---

## 🧠 Philosophy & Goals

* 🪶 **Lightweight**: Trainable on a single GPU (e.g., RTX 3090 or lower)
* 🧪 **Experimental**: Ideal for toy datasets, rapid prototyping, and ablation studies
* 🧱 **Modular**: Easily replace components (e.g., attention, norm, embeddings)
* 📚 **Educational**: Code is simple, readable, and documented

---

## 📚 Supported Datasets

Currently integrated:

* 🧒 **TinyStories** (default)
* 📄 Custom `.pt` tokenized corpora
* 📘 (Coming Soon) WikiText and code datasets

---

## 📊 Evaluation (Planned)

* Perplexity and loss benchmarks
* Text generation metrics (BLEU-style, syntactic plausibility)
* Synthetic reasoning benchmarks

---

## 🤝 Contributions & Contact

We welcome collaboration from ML engineers, students, and researchers interested in small-scale or interpretable language models.

📬 **Pull requests** and **issues** are open!
🐦 Twitter: [@SamanBarahoie](https://twitter.com/SamanBarahoie)

---

## 🧩 License

MIT License — free for academic, educational, and commercial use with attribution.

---
