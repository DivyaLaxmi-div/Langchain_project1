# 📈 Equity Research Analysis using RAG

A Retrieval-Augmented Generation (RAG) application that answers questions from financial news articles using **LangChain**, **Groq LLM**, **Hugging Face Embeddings**, and **FAISS**.

---

## 🚀 Features

- Load news articles directly from URLs
- Split documents into chunks for efficient retrieval
- Generate embeddings using Hugging Face
- Store embeddings in a FAISS vector database
- Retrieve relevant information based on user queries
- Generate accurate answers using Groq LLM
- Reduce hallucinations by answering only from the retrieved context

---

## 🛠️ Tech Stack

- Python
- LangChain
- Groq (Llama 3.1)
- Hugging Face Embeddings
- FAISS
- UnstructuredURLLoader
- Google Colab

---



## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/DivyaLaxmi-div/Langchain_project1.git
```

Move into the project folder

```bash
cd Langchain_project1
```

Install the required packages

```bash
pip install -r requirements.txt
```

---

## 🔑 Setup

Create a **Groq API Key** from:

https://console.groq.com

Set the API key before running the notebook.

Example:

```python
import os

os.environ["GROQ_API_KEY"] = "YOUR_GROQ_API_KEY"
```

---

## ▶️ How It Works

1. Load news articles from URLs
2. Split the articles into smaller chunks
3. Generate embeddings using Hugging Face
4. Store embeddings in FAISS
5. Retrieve the most relevant chunks
6. Use Groq LLM to answer the user's question

---

## 💬 Example Questions

- What is the price of Tiago iCNG?
- Why did Tesla shares rise?
- Summarize both news articles.
- Compare the two articles.
- Which article discusses the automobile industry?

---

## 📌 Future Improvements

- Streamlit web application
- Chat history support
- Multiple document upload
- PDF and CSV support
- Persistent vector database using ChromaDB

