# 🧠 MiniGPT from Scratch — Inspired by Karpathy’s Zero-to-Hero LLM Series

Welcome to my implementation of a **Large Language Model (LLM)** from scratch, following the popular [Zero to Hero series by Andrej Karpathy](https://www.youtube.com/@AndrejKarpathy). This project builds a minimal yet functional GPT-like model using PyTorch, and trains it from scratch on a character-level dataset.

> 🚧 **Status**: Pretrained only — fine-tuning and deployment coming soon!

---

## 🧩 Features

- ✅ Transformer architecture implemented from scratch in PyTorch
- ✅ Training loop for character-level language modeling
- ✅ Tokenizer, dataset loading, and batching logic
- ✅ Basic inference script (generate text)
- ⏳ Fine-tuning interface (Coming Soon)
- ⏳ Web interface / chatbot integration (Planned)

---

## 📁 Project Structure


---

## 🧠 Model Details

| Component       | Description                                    |
|----------------|------------------------------------------------|
| Model Type      | Character-level GPT                            |
| Layers          | Configurable Transformer blocks (default: 6)   |
| Heads           | Multi-head self-attention                      |
| Positional Emb  | Learned sinusoidal positional embeddings       |
| Training Objective | Next character prediction (Causal LM)     |

---

## 🏁 Getting Started

### 1. Clone the Repo

```bash
git clone https://github.com/your-username/mini-llm-from-scratch.git
cd mini-llm-from-scratch

 Notes
This is a learning project meant for educational purposes.

The model is not fine-tuned or optimized for any specific downstream task yet.

The architecture is intentionally simple and easy to modify.


Acknowledgements
Huge thanks to Andrej Karpathy for the amazing Zero-to-Hero series and all open-source contributors in the ML/NLP community.

  
