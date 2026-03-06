# Talk to your PDF - Multilingual RAG System

A powerful Retrieval-Augmented Generation (RAG) system built with Python, designed to extract and search through PDF content using state-of-the-art semantic processing.

## 🚀 Features

- **Advanced PDF Extraction**: Robust text extraction using `PyPDF2` with intelligent whitespace and hyphenation cleaning.
- **Semantic Chunking**: Beyond naive splitting, this system uses embedding similarity to identify topic shifts and create contextually coherent chunks.
- **Multilingual Support**: Optimized for both English and German text processing.
- **Fast Vector Search**: Leverages `FAISS` for high-performance similarity search.
- **Gradio Interface**: Easy-to-use web interface for document interaction.

## 🛠️ Tech Stack

- **NLP**: `sentence-transformers` (paraphrase-multilingual-MiniLM-L12-v2)
- **Vector DB**: `FAISS`
- **PDF Core**: `PyPDF2`
- **UI**: `Gradio`
- **Backend**: Python, NumPy, Torch

## 📦 Installation

```bash
pip install transformers accelerate bitsandbytes sentence-transformers faiss-cpu PyPDF2 gradio langdetect
```

## 📖 Usage

1. Open `talktopdf.ipynb`.
2. Run the cells to initialize the models and functions.
3. Upload your PDF and start chatting!

---
Developed as a demonstration of modern RAG techniques.
