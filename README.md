# llm-pdf-qa
LLM-based PDF Q&amp;A chatbot using Gradio and FLAN-T5

# 📄 PDF Question Answering Bot

This project is a proof-of-concept for integrating LLM-based Q&A over PDF documents using semantic search and Gradio interface.

## 🚀 Features

- Upload PDF and interact with it using natural questions
- Semantic search using `LlamaIndex` + `SentenceTransformer`
- Local LLM answering using `google/flan-t5-base`
- Clean Gradio interface for interaction

## 📁 Folder Structure

- `notebook.ipynb` – Main working code
- `pdf_samples/` – Sample PDFs used for testing
- `report.pdf` – Short report explaining implementation
- `requirements.txt` – Python dependencies

## 🧠 Technologies Used

- Python
- LlamaIndex
- HuggingFace Transformers (Flan-T5)
- SentenceTransformers
- Gradio

  | Tool/Library         | Purpose                                     |
|----------------------|---------------------------------------------|
| `LlamaIndex`         | Document indexing, chunking, and retrieval |
| `SentenceTransformers` | Semantic embedding of queries and chunks |
| `Transformers (FLAN-T5)` | Lightweight open-source LLM             |
| `Gradio`             | Interactive web UI for Q&A session         |
| `Google Colab`       | Development and testing environment        |

## 🛠️ How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/llm-pdf-qa.git
   cd llm-pdf-qa

   # Install dependencies
pip install -r requirements.txt
