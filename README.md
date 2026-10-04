
# 🦤 Pelican: Training an LLM from Scratch

> A complete, hands-on recipe for understanding, building, and training Large Language Models (LLMs) from absolute scratch using PyTorch.

---

## 🌟 Highlights

* **Zero-to-Hero Guide:** Built without high-level abstraction libraries so you understand every single line of code.
* **Interactive Notebook:** Complete implementation available directly in [`Pelican.ipynb`](./Pelican.ipynb).
* **End-to-End Pipeline:** Covers everything from raw text ingestion to multi-head attention mechanisms and checkpointed training loops.

---

## 📌 What's Covered

| Step | Topic | Description | Key Modules |
| :--- | :--- | :--- | :--- |
| **01** | **Environment Setup** | Setting up PyTorch, verifying GPU/CUDA availability, and configuring reproducible random seeds. | `torch`, `cuda` |
| **02** | **Data Pipeline** | Ingesting raw corpus data, cleaning text, building tokenizers, and creating vocabulary mappings. | Tokenizer, Datasets |
| **03** | **Batching & Sequence Slicing** | Constructing PyTorch `DataLoader` objects, handling context windows, padding, and dynamic batching. | `DataLoader`, Context Windows |
| **04** | **Model Architecture** | Building Multi-Head Self-Attention, Positional Embeddings, LayerNorm, and Feed-Forward Networks from scratch. | Transformer, Attention |
| **05** | **Hyperparameters & Optimization** | Configuring AdamW optimizers, learning rate schedules with warmup, and cross-entropy loss functions. | AdamW, Cosine Scheduler |
| **06** | **Training Loop & Generation** | Executing training iterations, tracking loss curves, saving model checkpoints, and generating sample text. | Training Loop, Checkpoints |

---

## 🚀 Quick Start

### 1. Clone the Repository
```bash
git clone [https://github.com/Frankenstein-hsa/Pelican.git](https://github.com/Frankenstein-hsa/Pelican.git)
cd Pelican


