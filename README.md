# Tiny-llama-text-summarizer
A lightweight text summarization tool using TinyLlama (1.1B Chat) with Hugging Face Transformers and PyTorch.


# TinyLlama Text Summarizer

This project is a text summarization application created in **Google Colab** using the **TinyLlama-1.1B-Chat-v1.0** model from Hugging Face. It allows users to input long paragraphs and generate short, clear summaries using a causal language model.

---

## Project Details

- Developed in: Google Colab  
- Model Source: Hugging Face  
- Model Used: TinyLlama/TinyLlama-1.1B-Chat-v1.0  
- Framework: PyTorch  
- Library: Hugging Face Transformers  

The model is loaded directly from Hugging Face Model Hub and used for inference.

---

## Installation

Install the required dependencies:

```bash
pip install transformers accelerate torch huggingface_hub
```

---

## How It Works

1. Load the TinyLlama model from Hugging Face.  
2. Accept user input text.  
3. Format prompt for summarization.  
4. Generate summary using text generation.  
5. Display clean summarized output.

---

## How to Run

Run the script in Google Colab or a local Python environment:

```bash
python app.py
```

Paste the paragraph when prompted and press Enter to get the summary.

---

## Project Structure

```
tinyllama-text-summarizer/
│
├── app.py
└── README.md
```

---

## Requirements

- Python 3.8+  
- Google Colab or local environment  
- GPU recommended for faster inference  

---

## Purpose

This project demonstrates:

- Loading a pretrained model from Hugging Face  
- Text generation for summarization  
- Prompt engineering basics  
- Running transformer models in Google Colab  

---

⭐ If you found this helpful, consider giving the repository a star!
