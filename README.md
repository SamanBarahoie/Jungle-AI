# Jungle-AI
A Collection of Language Models in the Wild



Welcome to **Jungle AI**, a curated repository of efficient and scalable **language models** trained from scratch on small datasets, optimized for research, education, and rapid experimentation.

This repository centralizes efforts across the following projects:

* 🔬 [`nano_llama-3.1`](https://github.com/SamanBarahoie/nano_llama-3.1): A faithful re-implementation of LLaMA-style transformer blocks, optimized for training on TinyStories. Includes:

  * Causal self-attention with RoPE (Rotary Position Embeddings)
  * Streaming dataset support
  * Flash attention (optional)
  * Full test suite (`pytest + coverage`)
  * Modular and reproducible training loop with mixed precision

* 🧠 [`NanoLanguageModel`](https://github.com/SamanBarahoie/NanoLanguageModel): Minimalistic PyTorch implementation of a GPT-style model, focused on readability and educational value. Includes:

  * Basic tokenizer support
  * Vanilla transformer training loop
  * Early experiments with tiny datasets

---

### 🧠 Goals

* 🪶 **Lightweight**: All models are trainable on a single GPU (rtx 3090 or even lower-spec).
* 🧪 **Experimental**: Ideal for quick iterations, toy tasks, and conceptual learning.
* 🧱 **Modular**: Easy to extend components such as attention, normalization, positional encodings, etc.

---





### 🧪 Datasets

Currently supported datasets:

* 🧒 TinyStories (default for training and validation)
* 🧾 Custom tokenized `.pt` files
* (Soon) WikiText and Code datasets

---

### 📊 Evaluation

Coming soon:

* Perplexity and accuracy benchmarks
* BLEU-style text generation tests
* Synthetic reasoning tasks

---

### 📬 Contact & Contributions

Open to collaborations and contributions. If you're building or extending compact language models for low-resource settings, feel free to open a PR or issue.

🐦 Twitter: [@SamanBarahoie](https://twitter.com/SamanBarahoie)

---

### 🧩 License

MIT License. Use freely with attribution.

---
