# GPT-2 Style Language Model from Scratch

This repository contains a **Jupyter Notebook** that implements the architecture of **GPT-2** from scratch in **PyTorch**, with clear explanations and detailed definitions of every component.

The goal is to give a complete, educational look into how modern **transformer-based Large Language Models** work — from **tokenization** to **attention mechanisms** to **text generation**.

---

## 📂 Project Structure
```
├── gpt2_from_scratch.ipynb   # Main Jupyter notebook with full implementation
├── gutenberg.txt             # Data File
├── README.md                 # Project documentation
```

---

## 🧠 Model Configuration
- **Architecture:** GPT-2  
- **Parameters:** ~121M  
- **Layers:** 12  
- **Attention Heads:** 12  
- **Embedding Dimension:** 768  
- **Context Length:** 512  
- **Vocabulary Size:** 50,257  

---

## 📚 Dataset
- **Source:** 100 bedtime stories from Project Gutenberg  
- **Tokens:** ~30,000 after BPE tokenization  
- **Tokenizer:** Byte Pair Encoding (BPE)  

---

## ⚙️ Training Setup
- **Framework:** PyTorch  
- **Device:** CPU (Intel Core i7-11800H, 8 cores)  
- **Training Time:** ~30 minutes  

---

## 🚀 Features
- Byte-Pair Encoding (**BPE**) implementation for subword tokenization  
- **Transformer blocks** with multi-head self-attention  
- **Positional embeddings** and token embeddings  
- **Residual connections** & **layer normalization**  
- Cross-entropy loss and **perplexity evaluation**  
- Fully commented code for easy learning and modification  

---

## 📓 How to Use
1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/gpt2-from-scratch.git
   cd gpt2-from-scratch
   ```
2. **Open the notebook**
   ```bash
   jupyter notebook gpt2_from_scratch.ipynb
   ```
3. **Run all cells** to train and generate text.  
   *(You can also plug in your own dataset.)*

## 📜 License
This project is open-source feel free to use and modify it for your own experiments.
