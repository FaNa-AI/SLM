# 🧠 Sentence-Level Masking (SLM) - Transformer Language Modeling

This project implements a **Sentence-Level Masking (SLM)** technique for training and evaluating transformer-based masked language models. It leverages the power of Hugging Face's 🤗 `transformers` and PyTorch for building and testing simple yet effective language modeling workflows.

---

## 📌 Features

- 🔠 Sentence-level token masking for language modeling
- 🧪 Research-friendly and easy to modify
- 🤗 Integrated with Hugging Face Transformers
- ⚙️ Clean modular notebook code
- 🧠 Ideal for LLM pretraining experimentation

---

## 🛠️ Dependencies

Install required packages using:

```bash
pip install transformers datasets torch tqdm
````

---

## 🚀 How It Works

1. Load and tokenize a sample dataset.
2. Apply **sentence-level masking** to randomly selected tokens.
3. Train a masked language model using the prepared dataset.
4. Evaluate and visualize loss or model predictions.

---

## 📂 File Structure

```
slm.ipynb              # Main notebook (Sentence-Level Masking implementation)
data/                  # Optional: Folder to store preprocessed or downloaded datasets
```

---

## 📄 License

MIT License. Feel free to use, adapt, or build upon this code for your research or academic work.


