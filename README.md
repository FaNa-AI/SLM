# 🧠 Sentence-Level Small Language Model (SLM) with GPT2

This project demonstrates a lightweight implementation of a **small language model (SLM)** using the **GPT2** architecture via Hugging Face 🤗 Transformers.

It supports **text generation** in both **Persian and English**, making it ideal for educational use, rapid experimentation, and low-resource environments.

---

## ✨ Features

- ✅ Based on the compact GPT2 model: `openai-community/gpt2`
- 🧠 Suitable as a **small language model** (SLM) for quick testing and concept validation
- 🗣️ Supports **bilingual prompts**: Farsi (فارسی) & English
- ⚡ Fast execution with minimal dependencies
- 🔁 Easily extendable for fine-tuning or creative applications (e.g., poetry, Q&A, storytelling)

---

## 📦 Installation

Install required packages using pip:

```bash
pip install transformers accelerate torch
````

---

## 🚀 How It Works

1. Load the GPT2 model and tokenizer from Hugging Face Hub
2. Define a generation function with parameters like temperature and top-p
3. Provide a **prompt in Farsi or English**
4. Generate text continuation using the `generate()` method

---

## 📋 Example Prompts

```python
# Persian example
prompt = "چرا آسمان آبی است؟"

# English example
prompt = "Write a short story about a brave knight and a dragon."
```

Sample output:

```
Prompt (فارسی): چرا آسمان آبی است؟
Generated: به دلیل پراکندگی نور خورشید توسط جو زمین، بیشتر نور آبی دیده می‌شود...

Prompt (English): Write a short story about a brave knight...
Generated: ...who ventured into the mountains to protect his village from the dragon...
```

---

## 📁 Project Structure

```
slm.py                # Main Python script for bilingual text generation
README.md             # Project description and instructions
```

---

## 💡 Use Cases

* Bilingual prompt testing
* Educational demos for language modeling
* Creative writing, poetry, or storytelling
* Exploring small LLM behavior in controlled setups

---

## 🛠️ Built With

* [Transformers](https://huggingface.co/docs/transformers)
* [PyTorch](https://pytorch.org/)
* [Accelerate](https://github.com/huggingface/accelerate)

---


